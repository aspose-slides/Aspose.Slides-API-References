---
title: Double
second_title: Référence de l'API Aspose.Slides pour C++
description: Contient des méthodes pour travailler avec le nombre à virgule flottante double précision.
type: docs
weight: 1548
url: /fr/system/double/
---
## Double struct

Contient des méthodes pour travailler avec le nombre à virgule flottante double précision.

```cpp
class Double
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en la valeur équivalente à virgule flottante double précision. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en la valeur équivalente à virgule flottante double précision en utilisant les informations de formatage fournies. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en la valeur équivalente à virgule flottante double précision en utilisant les informations de formatage fournies et le style numérique. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en la valeur équivalente à virgule flottante double précision. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en la valeur équivalente à virgule flottante double précision en utilisant les informations de formatage fournies et le style numérique. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

## Champs

| Champ | Description |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Plus petite valeur positive supérieure à zéro. |
| static constexpr [MaxValue](./maxvalue/) | Plus grande valeur possible. |
| static constexpr [MinValue](./minvalue/) | Plus petite valeur possible. |
| static constexpr [NaN](./nan/) | Valeur qui n'est pas un nombre. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Infini négatif. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Infini positif. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)