---
title: ToString()
second_title: Aspose.Slides für C++ API Referenz
description: "Konvertiert den Wert dieser Instanz in ein äquivalentes System::String unter Verwendung der angegebenen kulturspezifischen Formatierungsinformationen."
type: docs
weight: 196
url: /de/system/iconvertible/tostring/
---
## IConvertible::ToString(System::SharedPtr\<System::IFormatProvider\>) Methode

Konvertiert den Wert dieser Instanz in ein äquivalentes [System::String](../../string/) unter Verwendung der angegebenen kulturspezifischen Formatierungsinformationen.

```cpp
virtual System::String System::IConvertible::ToString(System::SharedPtr<System::IFormatProvider> provider)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Eine [System::IFormatProvider](../../iformatprovider/) Schnittstellenimplementierung, die kulturspezifische Formatierungsinformationen bereitstellt. |

### Rückgabewert

Eine [System::String](../../string/) Instanz, die dem Wert dieser Instanz entspricht.

## IConvertible::ToString() const Methode

Analog zur C# [Object.ToString()](../../object/tostring/) Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String.

```cpp
virtual String System::Object::ToString() const
```

### Rückgabewert

[String](../../string/) Darstellung, wie von der endgültigen Klasse bereitgestellt.

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [IConvertible](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)