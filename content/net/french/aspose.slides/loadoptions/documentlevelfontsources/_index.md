---
title: DocumentLevelFontSources
second_title: Aspose.Sildes pour .NET API Référence
description: Spécifie les sources pour les polices externes à utiliser par la présentation. Ces polices sont disponibles pour la présentation tout au long de sa durée de vie et ne sont pas partagées avec d'autres présentations
type: docs
weight: 80
url: /fr/aspose.slides/loadoptions/documentlevelfontsources/
---

## LoadOptions.DocumentLevelFontSources property

Spécifie les sources pour les polices externes à utiliser par la présentation. Ces polices sont disponibles pour la présentation tout au long de sa durée de vie et ne sont pas partagées avec d'autres présentations

```csharp
public IFontSources DocumentLevelFontSources { get; set; }
```

### Exemples

L'exemple suivant montre comment spécifier des polices personnalisées utilisées avec PowerPoint Presentation.

```csharp
[C#]
byte[] memoryFont1 = File.ReadAllBytes("customfonts\\CustomFont1.ttf");
byte[] memoryFont2 = File.ReadAllBytes("customfonts\\CustomFont2.ttf");
LoadOptions loadOptions = new LoadOptions();
loadOptions.DocumentLevelFontSources.FontFolders = new string[] { "assets\\fonts", "global\\fonts" };
loadOptions.DocumentLevelFontSources.MemoryFonts = new byte[][] { memoryFont1, memoryFont2 };
using (IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions))
{
    //travailler avec la présentation
    //CustomFont1, CustomFont2 ainsi que les polices des dossiers assets\fonts & global\fonts et de leurs sous-dossiers sont disponibles pour la présentation
}
```

### Voir aussi

* interface [IFontSources](../../ifontsources)
* classe [LoadOptions](../../loadoptions)
* namespace [Aspose.Slides](../../loadoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->