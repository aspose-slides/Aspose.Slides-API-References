---
title: ExplicitCastToObject()
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 222
url: /cpp/system/objectext/explicitcasttoobject/
---
## ObjectExt::ExplicitCastToObject(const T\&) method




```cpp
template<typename T> static std::enable_if<System::IsBoxable<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## ObjectExt::ExplicitCastToObject(const T\&) method




```cpp
template<typename T> static std::enable_if<System::IsSmartPtr<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Struct [IsBoxable](../../isboxable/)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)