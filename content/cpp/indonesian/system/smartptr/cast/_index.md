---
title: Cast()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengkasting penunjuk ke tipe itu sendiri.
type: docs
weight: 287
url: /id/system/smartptr/cast/
---
## SmartPtr::Cast() const metode


Menguubah penunjuk ke tipenya sendiri.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| Y | Target type of pointed object. |
| Check | Flags to throw exception if no cast available. |

### Nilai Kembali

Pointer of changed type which is always in shared mode.

## SmartPtr::Cast() const metode


Menguubah penunjuk ke tipe dasar menggunakan static_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| Y | Target type of pointed object. |
| Check | Flags to throw exception if no cast available. |

### Nilai Kembali

Pointer of changed type which is always in shared mode.

## SmartPtr::Cast() const metode


Menguubah penunjuk ke tipe turunan menggunakan dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| Y | Target type of pointed object. |
| Check | Flags to throw exception if no cast available. |

### Nilai Kembali

Pointer of changed type which is always in shared mode. Melempar InvalidCastException bila tidak ada konversi yang tersedia.

## SmartPtr::Cast() const metode


Menguubah penunjuk ke tipe turunan menggunakan dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| Y | Target type of pointed object. |
| Check | Flags to throw exception if no cast available. |

### Nilai Kembali

Pointer of changed type which is always in shared mode. Mengembalikan nullptr bila tidak ada konversi yang tersedia.

## Lihat Juga

* Kelas [SmartPtr](../)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)