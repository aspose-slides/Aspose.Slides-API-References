---
title: CreateIListWrapperImpl()
second_title: Aspose.Slides for C++ API Referansı
description: Referans tipleri için IListWrapper uygulama yardımcı programı.
type: docs
weight: 14
url: /tr/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() metodu

[IListWrapper](../../../system.collections/ilistwrapper/) referans tipleri için uygulama yardımcı programı.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() metodu

[IListWrapper](../../../system.collections/ilistwrapper/) değer tipleri için uygulama yardımcı programı.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() metodu

[IListWrapper](../../../system.collections/ilistwrapper/) diğer tipler için uygulama yardımcı programı.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IList](../../../system.collections/ilist/)
* Sınıf [ListExt](../)
* Yapı [IsSmartPtr](../../../system/issmartptr/)
* Yapı [IsBoxable](../../../system/isboxable/)
* Ad Alanı [System::Collections::Generic](../../)
* Kütüphane [Aspose.Slides](../../../)