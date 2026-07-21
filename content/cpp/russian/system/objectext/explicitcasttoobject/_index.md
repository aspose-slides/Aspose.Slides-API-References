---
title: ExplicitCastToObject()
second_title: Справочник API Aspose.Slides для C++
description: 
type: docs
weight: 235
url: /ru/system/objectext/explicitcasttoobject/
---
## ObjectExt::ExplicitCastToObject(const T\&) method




```cpp
template<typename T> static std::enable_if<System::IsBoxable<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```


## ObjectExt::ExplicitCastToObject(const T\&) method




```cpp
template<typename T> static std::enable_if<System::IsSmartPtr<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## См. также

* Тип [SharedPtr](../../sharedptr/)
* Класс [Object](../../object/)
* Класс [ObjectExt](../)
* Структура [IsBoxable](../../isboxable/)
* Структура [IsSmartPtr](../../issmartptr/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)