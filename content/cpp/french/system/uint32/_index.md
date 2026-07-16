---
title: UInt32
second_title: Référence de l'API Aspose.Slides for C++
description: Contient des méthodes pour travailler avec l'entier non signé sur 32 bits.
type: docs
weight: 1951
url: /fr/system/uint32/
---
## UInt32 structure

Contient des méthodes pour travailler avec l'entier non signé sur 32 bits.

```cpp
class UInt32
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en l'entier non signé 32 bits équivalent. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en l'entier non signé 32 bits équivalent en utilisant les informations de formatage fournies. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en l'entier non signé 32 bits équivalent en utilisant les informations de formatage et le style de nombre fournis. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint32_t**\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en l'entier non signé 32 bits équivalent. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint32_t**\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en l'entier non signé 32 bits équivalent en utilisant les informations de formatage et le style de nombre fournis. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint32_t**\&) |  |

## Champs

| Champ | Description |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Valeur maximale possible. |
| static constexpr [MinValue](./minvalue/) | Valeur minimale possible. |

## Voir aussi

* Namespace [System](../)
* Library [Aspose.Slides](../../)