---
title: Metered
second_title: Aspose.Sildes pour la référence API .NET
description: Fournit des méthodes pour définir une clé mesurée.
type: docs
weight: 8810
url: /fr/aspose.slides/metered/
---

## Classe Metered

Fournit des méthodes pour définir une clé mesurée.

```csharp
public class Metered
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Metered](metered)() | Initialise une nouvelle instance de cette classe. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SetMeteredKey](../../aspose.slides/metered/setmeteredkey)(string, string) | Définit la clé publique et la clé privée mesurées |
| static [GetConsumptionCredit](../../aspose.slides/metered/getconsumptioncredit)() | Obtient le crédit de consommation |
| static [GetConsumptionQuantity](../../aspose.slides/metered/getconsumptionquantity)() | Obtient la taille du fichier de consommation |
| static [IsMeteredLicensed](../../aspose.slides/metered/ismeteredlicensed)() | Vérifie si la mesure est sous licence |

### Exemples

Dans cet exemple, une tentative sera faite pour définir la clé publique et la clé privée mesurées

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Voir Aussi

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->