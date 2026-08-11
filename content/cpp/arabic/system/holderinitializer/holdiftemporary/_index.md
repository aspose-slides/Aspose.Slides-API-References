---
title: HoldIfTemporary()
second_title: مرجع API Aspose.Slides للغة C++
description: يعيد مرجعًا إلى rvalue (const)
type: docs
weight: 14
url: /ar/system/holderinitializer/holdiftemporary/
---
## HolderInitializer::HoldIfTemporary(const T\&) طريقة
يعيد مرجعًا إلى rvalue (const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(const T &value)
```

## HolderInitializer::HoldIfTemporary(T\&) طريقة
يعيد مرجعًا إلى rvalue (non-const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &value)
```

## HolderInitializer::HoldIfTemporary(T\&&) طريقة
ينسخ lvalue الممرَّة إلى holder، ثم يعيد مرجع holder.

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &&value)
```

## انظر أيضًا

* هيكل [HolderInitializer](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)