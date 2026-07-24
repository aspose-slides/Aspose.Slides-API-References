---
title: ExplicitCastToObject()
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 235
url: /de/system/objectext/explicitcasttoobject/
---
## ObjectExt::ExplicitCastToObject(const T\&) Methode




```cpp
template<typename T> static std::enable_if<System::IsBoxable<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## ObjectExt::ExplicitCastToObject(const T\&) Methode




```cpp
template<typename T> static std::enable_if<System::IsSmartPtr<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Object](../../object/)
* Klasse [ObjectExt](../)
* Struktur [IsBoxable](../../isboxable/)
* Struktur [IsSmartPtr](../../issmartptr/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)