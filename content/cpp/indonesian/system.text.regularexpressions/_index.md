---
title: "System::Text::RegularExpressions"
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 989
url: /id/system.text.regularexpressions/
---
## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [Capture](./capture/) | Hasil pencocokan subekspresi tunggal. Objek dari kelas ini hanya boleh dialokasikan menggunakan [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [CaptureCollection](./capturecollection/) | Daftar capture yang dilakukan oleh grup penangkap tunggal. Objek dari kelas ini hanya boleh dialokasikan menggunakan [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [Group](./group/) | Hasil pencocokan yang dilakukan oleh grup penangkap tunggal. Objek dari kelas ini hanya boleh dialokasikan menggunakan [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [GroupCollection](./groupcollection/) | Daftar grup capture dalam satu pencocokan. Objek dari kelas ini hanya boleh dialokasikan menggunakan [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [GroupCollectionPtr](./groupcollectionptr/) | [Group](./group/) pointer koleksi. Tipe ini adalah pointer untuk mengelola penghapusan objek lain. Ia harus dialokasikan di stack dan diteruskan ke fungsi baik secara nilai maupun dengan referensi const. |
| [Match](./match/) | [Single](../system/single/) pencocokan regexp pada string. Objek dari kelas ini hanya boleh dialokasikan menggunakan [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [MatchCollection](./matchcollection/) | Koleksi pencocokan yang dilakukan dengan menerapkan regexp berulang kali pada string. Objek dari kelas ini hanya boleh dialokasikan menggunakan [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [Regex](./regex/) | Ekspresi reguler yang mengikuti sintaks mirip C#. Objek dari kelas ini hanya boleh dialokasikan menggunakan [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |

## Fungsi

| Fungsi | Deskripsi |
| --- | --- |
|  [ASPOSECPP_3RD_PARTY_UNCOPYBALE_TYPE_HOLDER](./asposecpp_3rd_party_uncopybale_type_holder/)(Detail::MatchHolder, MatchHolder, sizeof(Detail::DummyMatchHolder), Detail::DummyMatchHolder, MatchHolderAlias) | Pembungkus untuk menahan kelas MatchHolder tanpa menyertakannya serta PCRE2. |

## Enum

| Enum | Deskripsi |
| --- | --- |
| [RegexOptions](./regexoptions/) | [Regex](./regex/) opsi. |

## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [UStringPtr](./ustringptr/) | UnicodeString bersama untuk menghindari penyalinan. |
| [CapturePtr](./captureptr/) | Pointer ke objek capture tunggal. |
| [CaptureCollectionPtr](./capturecollectionptr/) | Pointer ke koleksi capture. |
| [GroupPtr](./groupptr/) | Pointer ke grup. |
| [RegexPtr](./regexptr/) | [Regex](./regex/) pointer. |
| [MatchPtr](./matchptr/) | [Match](./match/) pointer. |
| [MatchCollectionPtr](./matchcollectionptr/) | [Match](./match/) collection pointer. |
| [MatchEvaluator](./matchevaluator/) | Tipe delegate untuk mengevaluasi pencocokan. |