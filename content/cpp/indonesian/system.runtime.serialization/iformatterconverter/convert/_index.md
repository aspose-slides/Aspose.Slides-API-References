---
title: Convert()
second_title: Aspose.Slides untuk Referensi API C++
description: Informasi RTTI.
type: docs
weight: 1
url: /id/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) metode


Informasi RTTI.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Objek yang akan dikonversi. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | [System::TypeInfo](../../../system/typeinfo/) yang akan dikonversi nilai ke dalamnya. |

### Nilai Kembalian

Nilai yang telah dikonversi.
## Keterangan


Mengonversi nilai ke [System::TypeInfo](../../../system/typeinfo/) yang diberikan. 
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) metode


Mengonversi nilai ke [System::TypeCode](../../../system/typecode/) yang diberikan.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Objek yang akan dikonversi. |
| typeCode | [TypeCode](../../../system/typecode/) | [System::TypeCode](../../../system/typecode/) yang akan dikonversi nilai ke dalamnya. |

### Nilai Kembalian

Nilai yang telah dikonversi.

## Lihat Juga

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [TypeInfo](../../../system/typeinfo/)
* Kelas [IFormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)