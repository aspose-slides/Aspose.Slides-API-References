---
title: Ref()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat referensi ke objek DynamicWeakPtr. Digunakan oleh penerjemah saat melewatkan argumen fungsi dengan referensi.
type: docs
weight: 2458
url: /id/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) fungsi


Membuat referensi ke objek [DynamicWeakPtr](../dynamicweakptr/). Digunakan oleh penerjemah saat melewatkan argumen fungsi dengan referensi.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe pointee. |
| trunkMode | Mode smart pointer itu sendiri. |
| weakLeafs | Indeks argumen templat yang harus dipanggil metode SetTemplateWeakPtr. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | Smart pointer untuk membuat referensi ke. |

### Nilai Kembalian

Referensi smart pointer.

## System::Ref(T\&) fungsi


Fungsi pembantu untuk memperoleh referensi ke objek. Digunakan untuk memastikan bahwa [System::DynamicWeakPtr](../dynamicweakptr/) memperbarui objek yang direferensikan setelah penugasan.

```cpp
template<typename T> T & System::Ref(T &value)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe untuk membuat referensi ke. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | T\& | Nilai untuk membuat referensi ke. |

### Nilai Kembalian

Referensi ke nilai yang diberikan ke fungsi ini.

## Lihat Juga

* Kelas [DynamicWeakPtr](../dynamicweakptr/)
* Namespace [System](../)
* Perpustakaan [Aspose.Slides](../../)