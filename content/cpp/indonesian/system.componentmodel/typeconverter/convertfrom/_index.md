---
title: ConvertFrom()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi objek.
type: docs
weight: 14
url: /id/system.componentmodel/typeconverter/convertfrom/
---
## TypeConverter::ConvertFrom(const System::SharedPtr\<System::Object\>\&) metode


Mengonversi objek.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<System::Object> &value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) untuk dikonversi. |

### Nilai Kembali

objek yang dikonversi.

## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) metode


Mengonversi objek.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informasi konteks konversi. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Budaya yang digunakan saat mengonversi objek. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) untuk dikonversi. |

### Nilai Kembali

objek yang dikonversi.

## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) metode


Mengonversi string menjadi objek.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informasi konteks konversi. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Budaya yang digunakan saat mengonversi objek. |
| value | const [System::String](../../../system/string/)\& | Nilai untuk dikonversi. |

### Nilai Kembali

objek yang dikonversi.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [TypeConverter](../)
* Kelas [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Kelas [CultureInfo](../../../system.globalization/cultureinfo/)
* Kelas [String](../../../system/string/)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)