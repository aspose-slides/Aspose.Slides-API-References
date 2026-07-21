---
title: CreateIListWrapperImpl()
second_title: Справочник API Aspose.Slides для C++
description: Вспомогательная реализация IListWrapper для ссылочных типов.
type: docs
weight: 14
url: /ru/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() метод

[IListWrapper](../../../system.collections/ilistwrapper/) вспомогательная реализация для ссылочных типов.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() метод

[IListWrapper](../../../system.collections/ilistwrapper/) вспомогательная реализация для типов значений.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() метод

[IListWrapper](../../../system.collections/ilistwrapper/) вспомогательная реализация для других типов.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IList](../../../system.collections/ilist/)
* Класс [ListExt](../)
* Struct [IsSmartPtr](../../../system/issmartptr/)
* Struct [IsBoxable](../../../system/isboxable/)
* Пространство имён [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)