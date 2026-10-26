---
title: CreateIListWrapperImpl()
second_title: Referencia de API de Aspose.Slides para C++
description: Asistente de implementación de IListWrapper para tipos de referencia.
type: docs
weight: 14
url: /es/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() método


[IListWrapper](../../../system.collections/ilistwrapper/) asistente de implementación para tipos de referencia.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() método


[IListWrapper](../../../system.collections/ilistwrapper/) asistente de implementación para tipos de valor.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() método


[IListWrapper](../../../system.collections/ilistwrapper/) asistente de implementación para otros tipos.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections/ilist/)
* Class [ListExt](../)
* Struct [IsSmartPtr](../../../system/issmartptr/)
* Struct [IsBoxable](../../../system/isboxable/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)