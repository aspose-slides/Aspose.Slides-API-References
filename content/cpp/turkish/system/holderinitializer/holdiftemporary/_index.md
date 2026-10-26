---
title: HoldIfTemporary()
second_title: Aspose.Slides for C++ API Referansı
description: rvalue (const) referansını döndürür
type: docs
weight: 14
url: /tr/system/holderinitializer/holdiftemporary/
---
## HolderInitializer::HoldIfTemporary(const T\&) metot

rvalue (const) referansını döndürür.

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(const T &value)
```

## HolderInitializer::HoldIfTemporary(T\&) metot

rvalue (non-const) referansını döndürür.

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &value)
```

## HolderInitializer::HoldIfTemporary(T\&&) metot

Geçilen lvalue'yi holder'a kopyalar, ardından holder referansını döndürür.

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &&value)
```

## İlgili

* Yapı [HolderInitializer](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)