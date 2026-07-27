---
title: ExplicitCastToObject()
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 235
url: /pt/system/objectext/explicitcasttoobject/
---
## ObjectExt::ExplicitCastToObject(const T\&) método




```cpp
template<typename T> static std::enable_if<System::IsBoxable<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## ObjectExt::ExplicitCastToObject(const T\&) método




```cpp
template<typename T> static std::enable_if<System::IsSmartPtr<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## Ver também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Object](../../object/)
* Classe [ObjectExt](../)
* Estrutura [IsBoxable](../../isboxable/)
* Estrutura [IsSmartPtr](../../issmartptr/)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)