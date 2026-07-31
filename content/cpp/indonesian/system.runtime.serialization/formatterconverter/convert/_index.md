---
title: Convert()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengonversi nilai ke System::TypeInfo yang diberikan."
type: docs
weight: 1
url: /id/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) metode

Mengonversi nilai ke [System::TypeInfo](../../../system/typeinfo/) yang diberikan.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Objek yang akan dikonversi. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | [System::TypeInfo](../../../system/typeinfo/) tempat nilai akan dikonversi. |

### Nilai Kembali

Nilai yang telah dikonversi.

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) metode

Mengonversi nilai ke [System::TypeCode](../../../system/typecode/) yang diberikan.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Objek yang akan dikonversi. |
| typeCode | [TypeCode](../../../system/typecode/) | [System::TypeCode](../../../system/typecode/) tempat nilai akan dikonversi. |

### Nilai Kembali

Nilai yang telah dikonversi.

## Lihat Juga

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [TypeInfo](../../../system/typeinfo/)
* Kelas [FormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)