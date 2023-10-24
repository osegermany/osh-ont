<!--
SPDX-FileCopyrightText: 2023 Robin Vobruba <hoijui.quaero@gmail.com>

SPDX-License-Identifier: CC0-1.0
-->

# OSH Ontology

[![License: CC0-1.0](
    https://img.shields.io/badge/License-CC0--1.0-blue.svg)](
    LICENSE)
[![REUSE status](
    https://api.reuse.software/badge/github.com/OSEGermany/osh-ont)](
    https://api.reuse.software/info/github.com/OSEGermany/osh-ont)

[![In cooperation with Open Source Ecology Germany](
    https://raw.githubusercontent.com/osegermany/tiny-files/master/res/media/img/badge-oseg.svg)](
    https://opensourceecology.de)
[![In cooperation with ValueFlows](
    https://raw.githubusercontent.com/osegermany/tiny-files/master/res/media/img/badge-valueflows.svg)](
    https://valueflo.ws)

- OSH: **_Open Source Hardware_** (Machines and other things that free the user of the domination and control by the producer)
- Ontology: **_A way of showing the properties of a subject area and how they are related, by defining a set of terms and relational expressions that represent the entities in that subject area_**

## Why

The idea is, to share a general linguistic (and therefore social/human)
and machine-friendly structure,
that allows humans, organizations, software and standards
to speak common language in the field of OSH.

This hopefully leads to us communicating more precisely, with less misunderstanding.
It may also lead to different software applications -
independently developed from each other -
in the field,
to feel more similar to the user and developers,
and potentially even for them to be technically compatible.

If standards and specifications in the field refer to this ontologies vocabulary,
or even link to the RDF ontology,
It will also make it easier for humans and software to understand them (correctly),
and it might help in their credibility and adoption.

## Scope

So far:

- Designing & Documenting
- Assembling
- Using
- Manufacturing (planned)

Hopefully in the future:

- repairing
- recycling

## Technical details

The core of it all is our [RDF ontology](src/ontology/osh.ttl).
Apart from that,
we are focusing on manually crafted diagrams
to explain the ontology to humans.
For those, we also create some icons.

All of these can be found under the `src/` directory,
while the `res/` directory contains 3rd-party sources,
potentially modified a bit.

## Who is doing this?

Starting in October 2023, it is:

- Robin Vobruba from [Open Source Ecology Germany](https://wiki.opensourceecology.de) (OSEG)
- Lynn Foster from the [Valueflows](https://valueflo.ws) (VF) project

We are looking for more contributors!
