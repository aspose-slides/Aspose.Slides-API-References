---
title: ExplicitCastToObject()
second_title: Riferimento API Aspose.Slides per C++
description: 
type: docs
weight: 235
url: /it/system/objectext/explicitcasttoobject/
---
## ObjectExt::ExplicitCastToObject(const T\&) metodo




```cpp
template<typename T> static std::enable_if<System::IsBoxable<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## ObjectExt::ExplicitCastToObject(const T\&) metodo




```cpp
template<typename T> static std::enable_if<System::IsSmartPtr<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Object](../../object/)
* Classe [ObjectExt](../)
* Struct [IsBoxable](../../isboxable/)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)