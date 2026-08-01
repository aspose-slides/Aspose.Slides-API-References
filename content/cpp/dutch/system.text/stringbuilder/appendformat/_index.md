---
title: AppendFormat()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een geformatteerde tekenreeks toe aan de builder.
type: docs
weight: 131
url: /nl/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String\&, const TArgs\&...) methode

Voegt een geformatteerde tekenreeks toe aan de builder.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TArgs | Argumenttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Opmaaktekenreeks. |
| args | const TArgs\&... | Argumenten om in de posities van de opmaaktekenreeks in te voegen. |

### Retourwaarde

Deze pointer.

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String\&, const TArgs\&...) methode

Voegt een geformatteerde tekenreeks toe aan de builder.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TArgs | Argumenttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>\& | Opmaakprovider; genegeerd. |
| format | const [String](../../../system/string/)\& | Opmaaktekenreeks. |
| args | const TArgs\&... | Argumenten om in de posities van de opmaaktekenreeks in te voegen. |

### Retourwaarde

Deze pointer.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [StringBuilder](../)
* Klasse [String](../../../system/string/)
* Klasse [IFormatProvider](../../../system/iformatprovider/)
* Naamruimte [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)