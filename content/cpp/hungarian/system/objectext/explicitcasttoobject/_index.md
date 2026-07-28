---
title: ExplicitCastToObject()
second_title: Aspose.Slides C++ API Referenciája
description: 
type: docs
weight: 235
url: /hu/system/objectext/explicitcasttoobject/
---
## ObjectExt::ExplicitCastToObject(const T\&) metódus




```cpp
template<typename T> static std::enable_if<System::IsBoxable<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## ObjectExt::ExplicitCastToObject(const T\&) metódus




```cpp
template<typename T> static std::enable_if<System::IsSmartPtr<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [Object](../../object/)
* Osztály [ObjectExt](../)
* Struktúra [IsBoxable](../../isboxable/)
* Struktúra [IsSmartPtr](../../issmartptr/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)