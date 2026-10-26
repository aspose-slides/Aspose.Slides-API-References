---
title: SByte
second_title: Référence de l'API Aspose.Slides pour C++
description: Contient des méthodes pour travailler avec l'entier sur 8 bits.
type: docs
weight: 1847
url: /fr/system/sbyte/
---
## SByte struct

Contient des méthodes pour travailler avec l'entier sur 8 bits.

```cpp
class SByte
```

## Méthodes

| Method | Description |
| --- | --- |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&) | Convertit la chaîne spécifiée contenant la représentation texte d'un nombre en l'entier signé sur 8 bits équivalent. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne spécifiée contenant la représentation texte d'un nombre en l'entier signé sur 8 bits équivalent en utilisant les informations de formatage fournies. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne spécifiée contenant la représentation texte d'un nombre en l'entier signé sur 8 bits équivalent en utilisant les informations de formatage fournies et le style numérique. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int8_t**\&) | Convertit la chaîne spécifiée contenant la représentation texte d'un nombre en l'entier signé sur 8 bits équivalent. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int8_t**\&) | Convertit la chaîne spécifiée contenant la représentation texte d'un nombre en l'entier signé sur 8 bits équivalent en utilisant les informations de formatage fournies et le style numérique. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int8_t**\&) |  |

## Champs

| Field | Description |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Valeur maximale possible. |
| static constexpr [MinValue](./minvalue/) | Valeur minimale possible. |

## Voir aussi

* Namespace [System](../)
* Library [Aspose.Slides](../../)