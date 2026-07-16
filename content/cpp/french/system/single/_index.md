---
title: Single
second_title: Référence API Aspose.Slides pour C++
description: Contient des méthodes pour travailler avec le nombre à virgule flottante simple précision.
type: docs
weight: 1873
url: /fr/system/single/
---
## Structure simple


Contient des méthodes pour travailler avec le nombre à virgule flottante simple précision.

```cpp
class Single
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en la valeur équivalente à virgule flottante simple précision. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en la valeur équivalente à virgule flottante simple précision en utilisant les informations de formatage fournies. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en la valeur équivalente à virgule flottante simple précision en utilisant les informations de formatage fournies et le style de nombre. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en la valeur équivalente à virgule flottante simple précision. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en la valeur équivalente à virgule flottante simple précision en utilisant les informations de formatage fournies et le style de nombre. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |

## Champs

| Champ | Description |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Plus petite valeur positive supérieure à zéro. |
| static constexpr [MaxValue](./maxvalue/) | Valeur maximale possible. |
| static constexpr [MinValue](./minvalue/) | Plus petite valeur possible. |
| static constexpr [NaN](./nan/) | Valeur qui n'est pas un nombre. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Infini négatif. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Infini positif. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)