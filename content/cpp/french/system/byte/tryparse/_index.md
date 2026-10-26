---
title: TryParse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la chaîne spécifiée contenant la représentation textuelle d'un nombre en l'entier non signé équivalent de 8 bits.
type: docs
weight: 14
url: /fr/system/byte/tryparse/
---
## Byte::TryParse(const String\&, uint8_t\&) méthode


Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en l’entier non signé équivalent de 8 bits.

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |
| result | **uint8_t**\& | La référence à une variable entière non signée de 8 bits où le résultat de la conversion est placé. |

### Valeur de retour

Vrai si la conversion a réussi, sinon - faux.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) méthode


Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en l’entier non signé équivalent de 8 bits en utilisant les informations de formatage et le style de nombre fournis.

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison bit à bit des valeurs de l’énumération NumberStyles qui spécifie le style autorisé de la représentation textuelle d’un nombre. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet qui contient les informations de format de chaîne. |
| result | **uint8_t**\& | La référence à une variable entière non signée de 8 bits où le résultat de la conversion est placé. |

### Valeur de retour

Vrai si la conversion a réussi, sinon - faux.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) méthode




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) méthode




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) méthode




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## Voir aussi

* Énum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Byte](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)