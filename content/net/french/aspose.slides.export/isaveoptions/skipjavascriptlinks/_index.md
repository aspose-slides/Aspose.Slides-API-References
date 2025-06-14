---
title: SkipJavaScriptLinks
second_title: Référence API Aspose.Slides pour .NET
description: Spécifie s'il faut ignorer les hyperliens contenant des appels JavaScript lors de l'enregistrement de la présentation. Booléen en lecture/écriture. La valeur par défaut est false.
type: docs
weight: 40
url: /fr/aspose.slides.export/isaveoptions/skipjavascriptlinks/
---

## Propriété ISaveOptions.SkipJavaScriptLinks

Spécifie s'il faut ignorer les hyperliens contenant des appels JavaScript lors de l'enregistrement de la présentation. Booléen en lecture/écriture. La valeur par défaut est **false**.

```csharp
public bool SkipJavaScriptLinks { get; set; }
```

### Remarques

Lorsque cette propriété est définie sur **true**, les hyperliens contenant des appels JavaScript seront ignorés lors de l'enregistrement.

Lorsque cette propriété est définie sur **false**, tous les hyperliens seront enregistrés.

### Exemples

Exemple:

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
    pres.Save("result_without_JavaScript_links.html", SaveFormat.Html, new HtmlOptions()
    {
        SkipJavaScriptLinks = true
    });
}
```

### Voir aussi

* interface [ISaveOptions](../../isaveoptions)
* namespace [Aspose.Slides.Export](../../isaveoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->