---
title: ExplicitCastToObject()
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 235
url: /sv/system/objectext/explicitcasttoobject/
---
## ObjectExt::ExplicitCastToObject(const T\&) metod




```cpp
template<typename T> static std::enable_if<System::IsBoxable<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## ObjectExt::ExplicitCastToObject(const T\&) metod




```cpp
template<typename T> static std::enable_if<System::IsSmartPtr<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Klass [Object](../../object/)
* Klass [ObjectExt](../)
* Struct [IsBoxable](../../isboxable/)
* Struct [IsSmartPtr](../../issmartptr/)
* Namnrymd [System](../../)
* Library [Aspose.Slides](../../../)