---
title: CreateIListWrapperImpl()
second_title: Aspose.Slides för C++ API-referens
description: IListWrapper-implementationshjälp för referenstyper.
type: docs
weight: 14
url: /sv/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() metod

[IListWrapper](../../../system.collections/ilistwrapper/) implementationshjälp för referenstyper.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() metod

[IListWrapper](../../../system.collections/ilistwrapper/) implementationshjälp för värdetyper.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() metod

[IListWrapper](../../../system.collections/ilistwrapper/) implementationshjälp för övriga typer.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IList](../../../system.collections/ilist/)
* Klass [ListExt](../)
* Struktur [IsSmartPtr](../../../system/issmartptr/)
* Struktur [IsBoxable](../../../system/isboxable/)
* Namnrymd [System::Collections::Generic](../../)
* Bibliotek [Aspose.Slides](../../../)