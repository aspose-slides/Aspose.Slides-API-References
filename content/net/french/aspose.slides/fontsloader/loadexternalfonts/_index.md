---
title: LoadExternalFonts
second_title: Aspose.Slides for .NET API Reference
description: Ajoute des dossiers supplémentaires pour rechercher des polices.
type: docs
weight: 40
url: /fr/aspose.slides/fontsloader/loadexternalfonts/
---

## FontsLoader.LoadExternalFonts method

Ajoute des dossiers supplémentaires pour rechercher des polices.

```csharp
public static void LoadExternalFonts(string[] directories)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| directories | String[] | Dossiers pour lire des polices supplémentaires. |

### Exemples

Les exemples suivants montrent comment charger des polices personnalisées à partir de .TTF

```csharp
[C#]
// Le chemin vers le répertoire des documents.
string dataDir = "C:\\";
// dossiers pour rechercher des polices
String[] folders = new String[] { dataDir };
// Charger les polices du répertoire de polices personnalisées
FontsLoader.LoadExternalFonts(folders);
// Faire du travail et effectuer le rendu de présentation/slides
using (Presentation presentation = new Presentation(dataDir + "DefaultFonts.pptx"))
{
    presentation.Save(dataDir + "NewFonts_out.pptx", SaveFormat.Pptx);
	// Effacer le cache de police
	FontsLoader.ClearCache();
}
```

### Voir aussi

* class [FontsLoader](../../fontsloader)
* namespace [Aspose.Slides](../../fontsloader)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->