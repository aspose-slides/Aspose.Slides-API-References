---
title: ToString()
second_title: Aspose.Slides voor C++ API-referentie
description: "Converteert de waarde van deze instantie naar een equivalente System::String met behulp van de opgegeven cultuurspecifieke opmaakinformatie."
type: docs
weight: 196
url: /nl/system/iconvertible/tostring/
---
## IConvertible::ToString(System::SharedPtr\<System::IFormatProvider\>) methode

Converteert de waarde van deze instantie naar een equivalente [System::String](../../string/) met behulp van de opgegeven cultuurspecifieke opmaakinformatie.

```cpp
virtual System::String System::IConvertible::ToString(System::SharedPtr<System::IFormatProvider> provider)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Een [System::IFormatProvider](../../iformatprovider/) interface-implementatie die cultuurspecifieke opmaakinformatie levert. |

### Retourwaarde

Een [System::String](../../string/) instantie equivalent aan de waarde van deze instantie.

## IConvertible::ToString() const methode

Analoge van de C# [Object.ToString()](../../object/tostring/) methode. Hiermee kunnen aangepaste objecten naar een string worden geconverteerd.

```cpp
virtual String System::Object::ToString() const
```

### Retourwaarde

[String](../../string/) representatie zoals geleverd door de definitieve klasse.

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [IConvertible](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)