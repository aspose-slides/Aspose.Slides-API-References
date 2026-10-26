---
title: HoldIfTemporary()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce un riferimento a rvalue (const)
type: docs
weight: 14
url: /it/system/holderinitializer/holdiftemporary/
---
## HolderInitializer::HoldIfTemporary(const T\&) metodo


Restituisce un riferimento a rvalue (const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(const T &value)
```

## HolderInitializer::HoldIfTemporary(T\&) metodo


Restituisce un riferimento a rvalue (non-const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &value)
```

## HolderInitializer::HoldIfTemporary(T\&&) metodo


Copia il lvalue passato nell'holder, quindi restituisce il riferimento all'holder.

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &&value)
```

## Vedi anche

* Struttura [HolderInitializer](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)