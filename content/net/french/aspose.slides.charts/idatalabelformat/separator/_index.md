---
title: Separator
second_title: Référence de l'API Aspose.Slides pour .NET
description: Définit ou renvoie un Variant représentant le séparateur utilisé pour les étiquettes de données sur un graphique. Chaîne lisible/écrivable.
type: docs
weight: 60
url: /fr/aspose.slides.charts/idatalabelformat/separator/
---

## Propriété IDataLabelFormat.Separator

Définit ou renvoie un Variant représentant le séparateur utilisé pour les étiquettes de données sur un graphique. Chaîne lisible/écrivable.

```csharp
public string Separator { get; set; }
```

### Remarques

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété Separator pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur pour la propriété Separator de toutes les étiquettes de données dans la collection DataLabelCollection (c'est-à-dire que "DataLabels.DefaultDataLabelFormat.Separator = val;" entraîne que toutes les DataLabels[i].Separator sont égales à val).

### Voir aussi

* interface [IDataLabelFormat](../../idatalabelformat)
* namespace [Aspose.Slides.Charts](../../idatalabelformat)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour Aspose.Slides.dll -->