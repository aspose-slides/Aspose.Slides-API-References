---
title: ConvertTo()
second_title: Aspose.Slides for C++ API referencia
description: Objektumot egy adott típusra konvertál.
type: docs
weight: 53
url: /hu/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method

Az objektumot egy adott típusra konvertálja.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) a konvertálandó. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | A konvertálandó típus. |

### Visszatérési érték

Átalakított objektum.

## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method

Az objektumot egy adott típusra konvertálja.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) a konvertálási kontextus információi. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | a konvertáláshoz használandó kultúra. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) a konvertálandó. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | A konvertálandó típus. |

### Visszatérési érték

Átalakított objektum.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [TypeConverter](../)
* Osztály [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Névtere [System::ComponentModel](../../)
* Könyvtár [Aspose.Slides](../../../)