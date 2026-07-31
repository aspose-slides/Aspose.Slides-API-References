---
title: "System::Runtime::Serialization"
second_title: Aspose.Slides untuk Referensi API C++
description: 
type: docs
weight: 794
url: /id/system.runtime.serialization/
---
## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [Details_SerializationException](./details_serializationexception/) |  |
| [FormatterConverter](./formatterconverter/) | Mewakili implementasi dasar dari antarmuka [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/). |
| [IFormatterConverter](./iformatterconverter/) | Menyediakan koneksi antara sebuah instance dari [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) dan kelas yang disediakan oleh formatter yang paling cocok untuk mengurai data di dalam [System::Runtime::Serialization::SerializationInfo](./serializationinfo/). |
| [ISerializable](./iserializable/) | Antarmuka objek yang dapat diserialisasi. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu balut kelas ini dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [SerializationInfo](./serializationinfo/) | Menyimpan sekumpulan bidang bernama yang mewakili objek yang diserialisasi. Tidak diimplementasikan. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu balut kelas ini dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [StreamingContext](./streamingcontext/) | Kelas tiruan untuk membuat kelas yang diterjemahkan yang menggunakan StreamingContext dapat dikompilasi. Jangan mengelola instance kelas ini dengan [SmartPtr](../system/smartptr/), mereka harus dialokasikan hanya di stack. |

## Definisi Tipe

| Definisi Tipe | Deskripsi |
| --- | --- |
| [SerializationException](./serializationexception/) |  |