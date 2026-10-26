---
title: ToType()
second_title: Aspose.Slides für C++ API-Referenz
description: "Konvertiert den Wert dieser Instanz in ein System::Object des angegebenen System::Type, das einen gleichwertigen Wert hat, unter Verwendung der angegebenen kulturspezifischen Formatierungsinformationen."
type: docs
weight: 209
url: /de/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) Methode

Konvertiert den Wert dieser Instanz in ein [System::Object](../../object/) des angegebenen System::Type, das einen gleichwertigen Wert hat, unter Verwendung der angegebenen kulturspezifischen Formatierungsinformationen.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | Der System::Type, in den der Wert dieser Instanz konvertiert wird. |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Eine [System::IFormatProvider](../../iformatprovider/)-Schnittstellenimplementierung, die kulturspezifische Formatierungsinformationen bereitstellt. |

### Rückgabewert

Eine [System::Object](../../object/)-Instanz vom Typ conversionType, deren Wert dem Wert dieser Instanz entspricht.

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Object](../../object/)
* Klasse [TypeInfo](../../typeinfo/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [IConvertible](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)