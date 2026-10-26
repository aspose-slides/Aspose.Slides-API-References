---
title: ConvertFromInvariantString()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert einen invariant-String in ein Objekt.
type: docs
weight: 27
url: /de/system.componentmodel/typeconverter/convertfrominvariantstring/
---
## TypeConverter::ConvertFromInvariantString(const System::String\&) Methode

Konvertiert einen invariant-String in ein Objekt.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromInvariantString(const System::String &text)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | Zu konvertierender Wert. |

### Rückgabewert

konvertiertes Objekt.

## TypeConverter::ConvertFromInvariantString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) Methode

Konvertiert einen invariant-String in ein Objekt.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromInvariantString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) Konvertierungskontext-Informationen. |
| text | const [System::String](../../../system/string/)\& | Zu konvertierender Wert. |

### Rückgabewert

konvertiertes Objekt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [String](../../../system/string/)
* Klasse [TypeConverter](../)
* Klasse [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Namensraum [System::ComponentModel](../../)
* Bibliothek [Aspose.Slides](../../../)