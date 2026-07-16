---
title: TryParse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en la valeur Decimal équivalente.
type: docs
weight: 482
url: /fr/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en la valeur [Decimal](../) équivalente.

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| result | [Decimal](../)\& | La référence à une variable [Decimal](../) où le résultat de la conversion est placé |

### Valeur de retour

True si la conversion a réussi, sinon - false

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en la valeur [Decimal](../) équivalente en utilisant les informations de formatage fournies et le style de nombre.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison bit à bit des valeurs de l'énumération NumberStyles qui spécifie le style autorisé de la représentation sous forme de chaîne d’un nombre |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet contenant les informations de format de chaîne |
| result | [Decimal](../)\& | Un argument de sortie; contient le résultat de la conversion |

### Valeur de retour

True si la conversion a réussi, sinon - false

## Voir aussi

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Decimal](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)