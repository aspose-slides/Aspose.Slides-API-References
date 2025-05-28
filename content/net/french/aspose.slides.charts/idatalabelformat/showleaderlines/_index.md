---
title: ShowLeaderLines
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente le comportement d'affichage des lignes de leaders des étiquettes de données d'un graphique spécifié. True affiche les lignes de leaders. False pour cacher. Boolean en lecture/écriture.
type: docs
weight: 110
url: /fr/aspose.slides.charts/idatalabelformat/showleaderlines/
---

## Propriété IDataLabelFormat.ShowLeaderLines

Représente le comportement d'affichage des lignes de leaders des étiquettes de données d'un graphique spécifié. True affiche les lignes de leaders. False pour cacher. Boolean en lecture/écriture.

```csharp
public bool ShowLeaderLines { get; set; }
```

### Remarques

Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLeaderLines pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowLeaderLines de toutes les étiquettes de données dans la collection DataLabelCollection (c'est-à-dire "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" provoque que tous DataLabels[i].ShowLeaderLines soit égal à val).

### Voir aussi

* interface [IDataLabelFormat](../../idatalabelformat)
* namespace [Aspose.Slides.Charts](../../idatalabelformat)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->