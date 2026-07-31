---
title: operator<()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyediakan semantik perbandingan kurang untuk kelas SmartPtr.
type: docs
weight: 235
url: /id/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const metode

Menyediakan semantik perbandingan kurang untuk kelas [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Y | Tipe pointer untuk dibandingkan dengan yang saat ini. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| p | Y * | Pointer untuk dibandingkan dengan yang saat ini. |

### Nilai Kembalian

benar jika objek yang dirujuk oleh [SmartPtr](../) 'less' daripada p dan salah sebaliknya.

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const metode

Menyediakan semantik perbandingan kurang untuk kelas [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Y | Tipe pointer untuk dibandingkan dengan yang saat ini. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | Pointer untuk dibandingkan dengan yang saat ini. |

### Nilai Kembalian

benar jika objek yang dirujuk oleh [SmartPtr](../) 'less' daripada x dan salah sebaliknya.

## Lihat Juga

* Kelas [SmartPtr](../)
* Ruang nama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)