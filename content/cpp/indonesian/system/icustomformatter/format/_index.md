---
title: Format()
second_title: Aspose.Slides untuk C++ Referensi API
description: Mengembalikan representasi string dari nilai yang diwakili oleh objek saat ini menggunakan format yang ditentukan.
type: docs
weight: 1
url: /id/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) method


Mengembalikan representasi string dari nilai yang diwakili oleh objek saat ini menggunakan format yang ditentukan.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | [System::String](../../string/) | Format string |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | Objek yang akan diformat |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Objek yang menyediakan informasi pemformatan |

### Nilai Kembalian

Representasi string dari **arg** yang diformat menurut format yang ditentukan oleh **format** dan **formatProvider**

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [String](../../string/)
* Kelas [Object](../../object/)
* Kelas [IFormatProvider](../../iformatprovider/)
* Kelas [ICustomFormatter](../)
* Ruang Nama [System](../../)
* Pustaka [Aspose.Slides](../../../)