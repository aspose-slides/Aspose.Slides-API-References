---
title: UInt64
second_title: Référence de l'API Aspose.Slides pour C++
description: Contient des méthodes pour travailler avec l'entier non signé de 64 bits.
type: docs
weight: 1964
url: /fr/system/uint64/
---
## UInt64 struct

Contient des méthodes pour travailler avec l'entier non signé de 64 bits.

```cpp
class UInt64
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&) | Convertit la string spécifiée contenant la représentation sous forme de string d'un nombre en l'entier non signé 64 bits équivalent. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la string spécifiée contenant la représentation sous forme de string d'un nombre en l'entier non signé 64 bits équivalent en utilisant les informations de formatage fournies. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la string spécifiée contenant la représentation sous forme de string d'un nombre en l'entier non signé 64 bits équivalent en utilisant les informations de formatage fournies et le style de nombre. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint64_t**\&) | Convertit la string spécifiée contenant la représentation sous forme de string d'un nombre en l'entier non signé 64 bits équivalent. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint64_t**\&) | Convertit la string spécifiée contenant la représentation sous forme de string d'un nombre en l'entier non signé 64 bits équivalent en utilisant les informations de formatage fournies et le style de nombre. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint64_t**\&) |  |

## Champs

| Champ | Description |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Valeur maximale possible. |
| static constexpr [MinValue](./minvalue/) | Valeur minimale possible. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)