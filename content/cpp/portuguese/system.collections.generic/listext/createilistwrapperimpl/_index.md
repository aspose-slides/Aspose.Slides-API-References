---
title: CreateIListWrapperImpl()
second_title: Referência da API Aspose.Slides para C++
description: Auxiliar de implementação IListWrapper para tipos de referência.
type: docs
weight: 14
url: /pt/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() método


[IListWrapper](../../../system.collections/ilistwrapper/) auxiliar de implementação para tipos de referência.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() método


[IListWrapper](../../../system.collections/ilistwrapper/) auxiliar de implementação para tipos de valor.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() método


[IListWrapper](../../../system.collections/ilistwrapper/) auxiliar de implementação para outros tipos.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IList](../../../system.collections/ilist/)
* Classe [ListExt](../)
* Estrutura [IsSmartPtr](../../../system/issmartptr/)
* Estrutura [IsBoxable](../../../system/isboxable/)
* Espaço de nomes [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)