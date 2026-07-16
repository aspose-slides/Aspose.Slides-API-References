---
title: ExplicitCastToObject()
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 235
url: /fr/system/objectext/explicitcasttoobject/
---
## ObjectExt::ExplicitCastToObject(const T\&) méthode




```cpp
template<typename T> static std::enable_if<System::IsBoxable<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## ObjectExt::ExplicitCastToObject(const T\&) méthode




```cpp
template<typename T> static std::enable_if<System::IsSmartPtr<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Object](../../object/)
* Classe [ObjectExt](../)
* Structure [IsBoxable](../../isboxable/)
* Structure [IsSmartPtr](../../issmartptr/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)