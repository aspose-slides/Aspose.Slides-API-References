---
title: ToType()
second_title: Aspose.Slides voor C++ API-referentie
description: "Converteert de waarde van deze instantie naar een System::Object van het opgegeven System::Type dat een equivalente waarde heeft, met behulp van de opgegeven cultuurspecifieke opmaakinformatie."
type: docs
weight: 209
url: /nl/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) method


Converteert de waarde van deze instantie naar een [System::Object](../../object/) van het opgegeven System::Type dat een gelijkwaardige waarde heeft, met behulp van de opgegeven cultuurspecifieke opmaakinformatie.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | Het System::Type waarop de waarde van deze instantie wordt geconverteerd. |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Een [System::IFormatProvider](../../iformatprovider/) interface-implementatie die cultuurspecifieke opmaakinformatie levert. |

### Retourwaarde

Een [System::Object](../../object/) instantie van type conversionType waarvan de waarde gelijk is aan de waarde van deze instantie.

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Object](../../object/)
* Klasse [TypeInfo](../../typeinfo/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [IConvertible](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)