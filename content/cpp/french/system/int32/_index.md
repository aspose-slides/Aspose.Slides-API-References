---
title: Int32
second_title: Référence de l'API Aspose.Slides pour C++
description: Contient des méthodes pour travailler avec l'entier 32 bits.
type: docs
weight: 1028
url: /fr/system/int32/
---
## Int32 classe

Contient des méthodes pour travailler avec l'entier sur 32 bits.

```cpp
class Int32
```

## Méthodes

| Method | Description |
| --- | --- |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d’un nombre en l’entier signé 32 bits équivalent. |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d’un nombre en l’entier signé 32 bits équivalent en utilisant les informations de formatage fournies. |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d’un nombre en l’entier signé 32 bits équivalent en utilisant les informations de formatage et le style de nombre fournis. |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [Parse](./parse/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&, std::nullptr_t) |  |
| static **int32_t** [Parse](./parse/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int32_t**\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d’un nombre en l’entier signé 32 bits équivalent. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int32_t**\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d’un nombre en l’entier signé 32 bits équivalent en utilisant les informations de formatage et le style de nombre fournis. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int32_t**\&) |  |

## Champs

| Field | Description |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Valeur maximale possible. |
| static constexpr [MinValue](./minvalue/) | Valeur minimale possible. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)