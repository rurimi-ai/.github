<h1 align="center">RURIMI</h1>

<p align="center">
Language infrastructure for Kinyarwanda<br>
RURIMI AI LTD · Kigali, Rwanda
</p>

<p align="center">
<a href="https://rurimi.dev">rurimi.dev</a> ·
<a href="https://main.rurimi.pages.dev">Live demo</a> ·
<a href="mailto:hello@rurimi.dev">hello@rurimi.dev</a>
</p>

---

## RURIMI — Kinyarwanda, as it is actually spoken

Standard written Kinyarwanda does not consistently represent two features that can distinguish words: **tone and vowel length**.

For example, two words may be written identically in ordinary text while differing in tone or vowel length. A conventional spelling system therefore leaves information that is important for pronunciation and language technology implicit.

**RURIMI** is a computational lexicon and language engine designed to represent and restore this information for Kinyarwanda language technology.

It is being built as long-term language infrastructure—not as a demo.

* **Native-verified lexicon.** Lexical entries undergo native-speaker review. Where a distinction has not been established, RURIMI records it as *unknown* rather than guessing.
* **Tone and vowel length.** RURIMI represents lexical tone and vowel length and organizes verified patterns into reusable tone anchors, supported by recorded speech and acoustic analysis.
* **Morphology engine.** RURIMI analyzes noun classes, verb structure, derivation, and agreement. A written form can have multiple legitimate readings, so the system preserves ambiguity rather than forcing a single answer.
* **Evidence over assumption.** Lexical decisions are traceable to their evidence. Corpus data, dictionaries, grammars, and recordings contribute evidence; native-speaker judgement provides the highest level of lexical verification.

## Progress

| **Metric**                      | **Current status**                        |
| :------------------------------ | :---------------------------------------- |
| Native-verified lexicon entries | **353** and growing                       |
| Automated engine tests          | **160+ test files**, run on every change  |
| Tone anchors                    | **69** — 30 verbal, 39 non-verbal         |
| Status                          | **Active development**, updated regularly |

<sub>Last updated: October 2026</sub>

## IJWI — Kinyarwanda annotation engine

**IJWI** is RURIMI's Kinyarwanda annotation engine for tone, vowel length, and word-form analysis, developed alongside the RURIMI language engine.

## Who it is for

RURIMI is being developed as language infrastructure for:

* **Speech technology** — TTS and ASR
* **Machine translation**
* **Search and information retrieval**
* **Spell-checking and grammar-checking**
* **Language education**
* **AI and language models**
* Other applications that need reliable Kinyarwanda linguistic data

## A note on access

RURIMI's source code, Gold lexicon, and linguistic data are **proprietary** and are not published on GitHub. They represent ongoing native-speaker research, linguistic analysis, and data development.

Interested in **API access, research collaboration, licensing, or partnership**?

Contact [hello@rurimi.dev](mailto:hello@rurimi.dev).

<sub>RURIMI and IJWI are products of RURIMI AI LTD, founded by Dieudonné Niyompano. © 2026 RURIMI AI LTD. All rights reserved.</sub>

<p align="center"><i>Rwanda-first. Africa-ready.</i></p>
