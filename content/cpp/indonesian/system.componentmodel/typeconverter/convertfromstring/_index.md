---
title: ConvertFromString()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengonversi string menjadi objek.
type: docs
weight: 40
url: /id/system.componentmodel/typeconverter/convertfromstring/
---
## TypeConverter::ConvertFromString(const System::String\&) metode


Mengonversi string menjadi objek.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::String &text)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | Nilai yang akan dikonversi. |

### Nilai Kembalian

objek yang dikonversi.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) metode


Mengonversi string menjadi objek.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informasi konteks konversi. |
| text | const [System::String](../../../system/string/)\& | Nilai yang akan dikonversi. |

### Nilai Kembalian

objek yang dikonversi.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) metode


Mengonversi string menjadi objek.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &text)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informasi konteks konversi. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Budaya yang digunakan saat mengonversi objek. |
| text | const [System::String](../../../system/string/)\& | Nilai yang akan dikonversi. |

### Nilai Kembalian

objek yang dikonversi.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [String](../../../system/string/)
* Kelas [TypeConverter](../)
* Kelas [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Kelas [CultureInfo](../../../system.globalization/cultureinfo/)
* Ruang Nama [System::ComponentModel](../../)
* Pustaka [Aspose.Slides](../../../)