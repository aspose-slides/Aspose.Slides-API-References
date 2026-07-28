---
title: ConvertFrom()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Konwertuje obiekty.
type: docs
weight: 14
url: /pl/system.componentmodel/typeconverter/convertfrom/
---
## TypeConverter::ConvertFrom(const System::SharedPtr\<System::Object\>\&) metoda

Konwertuje obiekty.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<System::Object> &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) do konwersji. |

### Wartość zwracana

skonwertowany obiekt.

## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) metoda

Konwertuje obiekty.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informacje o kontekście konwersji. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura używana podczas konwersji obiektów. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) do konwersji. |

### Wartość zwracana

skonwertowany obiekt.

## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) metoda

Konwertuje ciąg znaków na obiekt.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informacje o kontekście konwersji. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura używana podczas konwersji obiektów. |
| value | const [System::String](../../../system/string/)\& | Wartość do konwersji. |

### Wartość zwracana

skonwertowany obiekt.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [TypeConverter](../)
* Klasa [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)