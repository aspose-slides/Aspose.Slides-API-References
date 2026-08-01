---
title: HoldIfTemporary()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een referentie naar een rvalue (const)
type: docs
weight: 14
url: /nl/system/holderinitializer/holdiftemporary/
---
## HolderInitializer::HoldIfTemporary(const T\&) methode

Retourneert een referentie naar een rvalue (const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(const T &value)
```
## HolderInitializer::HoldIfTemporary(T\&) methode

Retourneert een referentie naar een rvalue (non-const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &value)
```
## HolderInitializer::HoldIfTemporary(T\&&) methode

Kopieert de doorgegeven lvalue naar de holder en retourneert vervolgens de holder-referentie.

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &&value)
```
## Zie ook

* Struct [HolderInitializer](../)
* namespace [System](../../)
* Library [Aspose.Slides](../../../)