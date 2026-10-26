---
title: ConvertFromString()
second_title: Aspose.Slides C++ API-referencia
description: Átalakítja a karakterláncot objektummá.
type: docs
weight: 40
url: /hu/system.componentmodel/typeconverter/convertfromstring/
---
## TypeConverter::ConvertFromString(const System::String\&) method


Átalakítja a karakterláncot objektummá.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::String &text)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | Átalakítandó érték. |

### Visszatérési érték

Átalakított objektum.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) method


Átalakítja a karakterláncot objektummá.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) konverziós kontextus információ. |
| text | const [System::String](../../../system/string/)\& | Átalakítandó érték. |

### Visszatérési érték

Átalakított objektum.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) method


Átalakítja a karakterláncot objektummá.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &text)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) konverziós kontextus információ. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Az a kultúra, amelyet objektumok átalakításakor használ. |
| text | const [System::String](../../../system/string/)\& | Átalakítandó érték. |

### Visszatérési érték

Átalakított objektum.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [String](../../../system/string/)
* Osztály [TypeConverter](../)
* Osztály [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Névtér [System::ComponentModel](../../)
* Könyvtár [Aspose.Slides](../../../)