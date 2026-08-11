---
title: HoldIfTemporary()
second_title: مرجع API Aspose.Slides برای C++
description: ارجاع به rvalue (const) را برمی‌گرداند
type: docs
weight: 14
url: /fa/system/holderinitializer/holdiftemporary/
---
## HolderInitializer::HoldIfTemporary(const T\&) متد

ارجاع به مقدار rvalue (const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(const T &value)
```

## HolderInitializer::HoldIfTemporary(T\&) متد

ارجاع به مقدار rvalue (non-const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &value)
```

## HolderInitializer::HoldIfTemporary(T\&&) متد

lvalue ارسال شده را به holder کپی می‌کند، سپس مرجع holder را برمی‌گرداند.

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &&value)
```

## موارد مرتبط

* ساختار [HolderInitializer](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)