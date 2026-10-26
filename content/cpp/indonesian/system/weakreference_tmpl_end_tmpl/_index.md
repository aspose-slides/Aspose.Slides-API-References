---
title: WeakReference<>
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili referensi lemah, yang mereferensikan sebuah objek sambil tetap memungkinkan objek tersebut dihapus.
type: docs
weight: 1522
url: /id/system/weakreference_tmpl_end_tmpl/
---
## WeakReference<> kelas

Mewakili referensi lemah, yang mereferensikan sebuah objek sambil tetap memungkinkan objek tersebut dihapus.

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | Mendapatkan indikasi apakah objek yang direferensikan oleh objek WeakReference saat ini telah dihapus. |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | Mendapatkan objek (target) yang direferensikan oleh objek WeakReference saat ini. |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Menetapkan objek (target) yang direferensikan oleh objek WeakReference saat ini. |
|  [WeakReference](./weakreference/)() | Konstruktor default. |
|  [WeakReference](./weakreference/)(std::nullptr_t) | Konstruktor dari nullptr. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Menginisialisasi instance baru dari kelas WeakReference, yang mereferensikan objek yang ditentukan. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Menginisialisasi instance baru dari kelas WeakReference, yang mereferensikan objek yang ditentukan. |

## Lihat Juga

* Ruang nama [System](../)
* Perpustakaan [Aspose.Slides](../../)