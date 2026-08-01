---
title: ExplicitCastToObject()
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 235
url: /nl/system/objectext/explicitcasttoobject/
---
## ObjectExt::ExplicitCastToObject(const T\&) methode




```cpp
template<typename T> static std::enable_if<System::IsBoxable<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## ObjectExt::ExplicitCastToObject(const T\&) methode




```cpp
template<typename T> static std::enable_if<System::IsSmartPtr<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Object](../../object/)
* Klasse [ObjectExt](../)
* Struct [IsBoxable](../../isboxable/)
* Struct [IsSmartPtr](../../issmartptr/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)