---
title: ExplicitCastToObject()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: 
type: docs
weight: 235
url: /th/system/objectext/explicitcasttoobject/
---
## ObjectExt::ExplicitCastToObject(const T\&) เมธอด

```cpp
template<typename T> static std::enable_if<System::IsBoxable<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```
## ObjectExt::ExplicitCastToObject(const T\&) เมธอด

```cpp
template<typename T> static std::enable_if<System::IsSmartPtr<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```
## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [Object](../../object/)
* คลาส [ObjectExt](../)
* Struct [IsBoxable](../../isboxable/)
* Struct [IsSmartPtr](../../issmartptr/)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)