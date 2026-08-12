---
title: HoldIfTemporary()
second_title: Aspose.Slides for C++ API संदर्भ
description: rvalue (const) का संदर्भ लौटाता है
type: docs
weight: 14
url: /hi/system/holderinitializer/holdiftemporary/
---
## HolderInitializer::HoldIfTemporary(const T\&) विधि


rvalue (const) का संदर्भ लौटाता है

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(const T &value)
```

## HolderInitializer::HoldIfTemporary(T\&) विधि


rvalue (non-const) का संदर्भ लौटाता है

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &value)
```

## HolderInitializer::HoldIfTemporary(T\&&) विधि


पास किया गया lvalue होल्डर में कॉपी करता है, फिर होल्डर का संदर्भ लौटाता है।

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &&value)
```

## देखें

* संरचना [HolderInitializer](../)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)