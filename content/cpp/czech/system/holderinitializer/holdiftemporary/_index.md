---
title: HoldIfTemporary()
second_title: Reference API Aspose.Slides pro C++
description: Vrací odkaz na rvalue (const)
type: docs
weight: 14
url: /cs/system/holderinitializer/holdiftemporary/
---
## HolderInitializer::HoldIfTemporary(const T&) metoda

Vrací odkaz na rvalue (const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(const T &value)
```

## HolderInitializer::HoldIfTemporary(T&) metoda

Vrací odkaz na rvalue (non-const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &value)
```

## HolderInitializer::HoldIfTemporary(T&&) metoda

Zkopíruje předaný lvalue do holderu a pak vrátí odkaz na holder.

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &&value)
```

## Viz také

* Struct [HolderInitializer](../)
* Namespace [System](../../)
* Knihovna [Aspose.Slides](../../../)