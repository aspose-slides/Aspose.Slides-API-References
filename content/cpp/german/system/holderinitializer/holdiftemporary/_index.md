---
title: HoldIfTemporary()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt Referenz auf rvalue zurück (const)
type: docs
weight: 14
url: /de/system/holderinitializer/holdiftemporary/
---
## HolderInitializer::HoldIfTemporary(const T\&) Methode


Gibt Referenz auf rvalue zurück (const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(const T &value)
```

## HolderInitializer::HoldIfTemporary(T\&) Methode


Gibt Referenz auf rvalue zurück (nicht const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &value)
```

## HolderInitializer::HoldIfTemporary(T\&&) Methode


Kopiert übergebenes lvalue in den Holder und gibt anschließend die Holder-Referenz zurück.

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &&value)
```

## Siehe auch

* Struktur [HolderInitializer](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)