---
title: ToType()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengonversi nilai instance ini menjadi System::Object dari System::Type yang ditentukan yang memiliki nilai yang setara, menggunakan informasi pemformatan spesifik budaya yang ditentukan."
type: docs
weight: 209
url: /id/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) metode

Mengonversi nilai dari instance ini menjadi [System::Object](../../object/) dari System::Type yang ditentukan yang memiliki nilai yang setara, menggunakan informasi pemformatan spesifik budaya yang ditentukan.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | System::Type ke mana nilai instance ini dikonversi. |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Implementasi antarmuka [System::IFormatProvider](../../iformatprovider/) yang menyediakan informasi pemformatan spesifik budaya. |

### Nilai Kembalian

Sebuah instance [System::Object](../../object/) bertipe conversionType yang nilainya setara dengan nilai instance ini.

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [Object](../../object/)
* Kelas [TypeInfo](../../typeinfo/)
* Kelas [IFormatProvider](../../iformatprovider/)
* Kelas [IConvertible](../)
* Ruang Nama [System](../../)
* Pustaka [Aspose.Slides](../../../)