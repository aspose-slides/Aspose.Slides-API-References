---
title: Parse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la représentation sous forme de chaîne d'un nombre décimal en une instance équivalente de la classe Decimal.
type: docs
weight: 469
url: /fr/system/decimal/parse/
---
## Decimal::Parse(const String\&) method

Convertit la représentation sous forme de chaîne d’un nombre décimal en une instance équivalente de la classe [Decimal](../).

```cpp
static Decimal System::Decimal::Parse(const String &s)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | La représentation sous forme de chaîne d’un nombre |

### Valeur de retour

Une nouvelle instance de la classe [Decimal](../) représentant une valeur équivalente à celle décrite par la chaîne spécifiée.

## Decimal::Parse(const String\&, Globalization::NumberStyles) method

Convertit la représentation sous forme de chaîne d’un nombre décimal en une instance équivalente de la classe [Decimal](../) en utilisant le style spécifié.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | La représentation sous forme de chaîne d’une valeur décimale à convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison binaire des valeurs d’énumération qui fournit des informations supplémentaires sur **s**, sur les éléments de style pouvant être présents dans **s**, ou sur la conversion de **s** vers un objet [Decimal](../) |

### Valeur de retour

Une nouvelle instance de la classe [Decimal](../) représentant une valeur équivalente à celle décrite par la chaîne spécifiée.

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) method

Convertit la représentation sous forme de chaîne d’un nombre décimal en une instance équivalente de la classe [Decimal](../) en utilisant le fournisseur de format spécifié.

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | La représentation sous forme de chaîne d’une valeur décimale à convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Fournisseur de format |

### Valeur de retour

Une nouvelle instance de la classe [Decimal](../) représentant une valeur équivalente à celle décrite par la chaîne spécifiée.

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method

Convertit la représentation sous forme de chaîne d’un nombre décimal en une instance équivalente de la classe [Decimal](../) en utilisant le style et le fournisseur de format spécifiés.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | La représentation sous forme de chaîne d’une valeur décimale à convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison binaire des valeurs d’énumération qui fournit des informations supplémentaires sur **s**, sur les éléments de style pouvant être présents dans **s**, ou sur la conversion de **s** vers un objet [Decimal](../) |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Fournisseur de format |

### Valeur de retour

Une nouvelle instance de la classe [Decimal](../) représentant une valeur équivalente à celle décrite par la chaîne spécifiée.

## Voir aussi

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)