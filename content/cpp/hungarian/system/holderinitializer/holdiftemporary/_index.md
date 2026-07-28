---
title: HoldIfTemporary()
second_title: Aspose.Slides C++ API-referencia
description: Visszaad egy referenciát az rvalue-ra (const)
type: docs
weight: 14
url: /hu/system/holderinitializer/holdiftemporary/
---
## HolderInitializer::HoldIfTemporary(const T\&) metódus

Visszaad egy referenciát az rvalue-ra (const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(const T &value)
```

## HolderInitializer::HoldIfTemporary(T\&) metódus

Visszaad egy referenciát az rvalue-ra (non-const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &value)
```

## HolderInitializer::HoldIfTemporary(T\&&) metódus

Átmásolja a átadott lvalue-t a holder-be, majd visszaadja a holder referenciáját.

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &&value)
```

## Lásd még

* Struktúra [HolderInitializer](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)