Unicode Proposals
=================

This repository collects (draft) proposals for new emojis and other Unicode characters.

Emoji
-----

A new emoji can be made in three different ways: 

* If rather original, it may require the assignment of an individual codepoint, usually in the upper areas of the Supplementary Multilingual Plane (SMP), U+1F9*xy*. This usually happens once a year with a new point release of the Unicode Technical Standard (where the next one is version 11.0 in 2018). The deadline for proposals is currently set to the end of June.
* An existing character can be repurposed by adding the `Emoji` property once and using Variation Selector 16 &lsquo;VS-16&rsquo; U+FE0F henceafter. 
* There are several types of canonic character sequences which can be registered. The most import type are multiple emojis forced to form a ligature by a Zero-Width Joiner &lsquo;ZWJ&rsquo; U+200D between components. Country flags use pairs of Regional Indicator Symbols and are added automatically if ISO 3166-1 changes, whereas their subdivisions are encoded with Tag Characters on a Waving Black Flag base using ISO 3166-2 codes.

The collection also contains templates, related sources, references and other material related to the Unicode standard.

Contribution
------------

You can contribute to an [existing issue](https://github.com/Crissov/unicode-proposals/issues) (e.g. for [animals](https://github.com/Crissov/unicode-proposals/issues?q=is%3Aissue+is%3Aopen+label%3Aanimal), [flags](https://github.com/Crissov/unicode-proposals/issues?q=is%3Aissue+is%3Aopen+label%3Aflag), [emoticons](https://github.com/Crissov/unicode-proposals/issues?q=is%3Aissue+is%3Aopen+label%3Aemoticon) or [food](https://github.com/Crissov/unicode-proposals/issues?q=is%3Aissue+is%3Aopen+label%3Afood)) or [raise a new one](https://github.com/Crissov/unicode-proposals/issues/new) to **wish for additional proposals**. 
The thing most direly needed in emoji proposals are example graphics that ideally can be used freely (even commercially) and without strong attribution requirements.

Your help is always appreciated, but &ndash; for emojis &ndash; please read about the [Unicode Proposal Process](http://unicode.org/emoji/selection.html) first. (Emojione has published a [synopsis](https://www.emojione.com/blog/so-you-want-to-propose-an-emoji-to-unicode-heres-how) that&rsquo;s probably easier and quicker to read.)

Drafted and Submitted Proposals
-------------------------------

See branches and pull requests for more work-in-progress items.

* [Fourth wise monkey: _Do-No-Evil Monkey_](fourth-monkey.md)
* [Missing emoji human body parts, mostly taboo one like genitalia, behind and female breasts](body-parts.md)
* [Make emoji flags for non-countries optional](dependent-regions.md)

* [**Template** for an Emoji Proposal](proposal.template.md)

Older white papers
------------------

Similar discussions are now found in the repository issues on Github.

* [New ZWJ sequences for choosing the primary color of emojis](color-selection.md)
* [Relationship and Family Emojis and Character Sequences](relationships.md)
* [More ZWJ sequences for emoji professions](professions.md)
* [Some ZWJ sequences and some unique emojis to replace current metaphors and line art](sexual-activities.md)
* [Conventional emoji “short names” (`:short_codes:`) as HTML named entities](emoji-entities.md)
* [Evidence of raunchy emoji metaphors in sexting etc.](references/sexting.md)
* [Emoji ligatures instead of Tag sequences for subregion flags](iso_3166-2-emoji.md)
