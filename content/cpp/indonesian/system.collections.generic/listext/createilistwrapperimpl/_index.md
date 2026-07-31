---
title: CreateIListWrapperImpl()
second_title: Referensi API Aspose.Slides untuk C++
description: Pembantu implementasi IListWrapper untuk tipe referensi.
type: docs
weight: 14
url: /id/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() metode

[IListWrapper](../../../system.collections/ilistwrapper/) pembantu implementasi untuk tipe referensi.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() metode

[IListWrapper](../../../system.collections/ilistwrapper/) pembantu implementasi untuk tipe nilai.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() metode

[IListWrapper](../../../system.collections/ilistwrapper/) pembantu implementasi untuk tipe lainnya.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IList](../../../system.collections/ilist/)
* Kelas [ListExt](../)
* Struktur [IsSmartPtr](../../../system/issmartptr/)
* Struktur [IsBoxable](../../../system/isboxable/)
* Ruang Nama [System::Collections::Generic](../../)
* Perpustakaan [Aspose.Slides](../../../)