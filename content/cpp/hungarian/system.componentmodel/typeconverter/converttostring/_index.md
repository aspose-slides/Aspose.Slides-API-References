---
title: ConvertToString()
second_title: Aspose.Slides for C++ API referencia
description: Átalakítja az objektumot karakterlánccá.
type: docs
weight: 79
url: /hu/system.componentmodel/typeconverter/converttostring/
---
## TypeConverter::ConvertToString(const System::SharedPtr\<System::Object\>\&) metódus


Az objektumot karakterlánccá konvertálja.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<System::Object> &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) to convert. |

### Return Value

Konvertált objektum.

## TypeConverter::ConvertToString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Object\>\&) metódus


Az objektumot karakterlánccá konvertálja.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Object> &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) conversion context information. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) to convert. |

### Return Value

Konvertált objektum.

## TypeConverter::ConvertToString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) metódus


Az objektumot karakterlánccá konvertálja.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) conversion context information. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | A konvertáláshoz használandó kultúra. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) to convert. |

### Return Value

Konvertált objektum.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [Object](../../../system/object/)
* Osztály [TypeConverter](../)
* Osztály [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Névtér [System::ComponentModel](../../)
* Könyvtár [Aspose.Slides](../../../)