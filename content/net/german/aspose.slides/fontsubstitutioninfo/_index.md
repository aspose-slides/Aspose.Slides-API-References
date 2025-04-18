---
title: FontSubstitutionInfo
second_title: Aspose.Slides für .NET-API-Referenz
description: Diese Struktur stellt die Informationen über die Schriftersetzung dar wenn sie gerendert wird.
type: docs
weight: 4480
url: /de/aspose.slides/fontsubstitutioninfo/
---
## FontSubstitutionInfo class

Diese Struktur stellt die Informationen über die Schriftersetzung dar, wenn sie gerendert wird.

```csharp
public class FontSubstitutionInfo
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [FontSubstitutionInfo](fontsubstitutioninfo)(string, string) | Erstellt eine Instanz von[`FontSubstitutionInfo`](../fontsubstitutioninfo) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [OriginalFontName](../../aspose.slides/fontsubstitutioninfo/originalfontname) { get; } | Gibt den Quellschriftnamen in der Präsentation an. SchreibgeschütztString |
| [SubstitutedFontName](../../aspose.slides/fontsubstitutioninfo/substitutedfontname) { get; } | Gibt den Namen der Ersatzschriftart für die Originalschriftart an. SchreibgeschütztString |

### Beispiele

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    foreach (FontSubstitutionInfo fontSubstitution in pres.FontsManager.GetSubstitutions())
    {
        Console.WriteLine("{0} -> {1}", fontSubstitution.OriginalFontName, fontSubstitution.SubstitutedFontName);
    }
}        
```

### Siehe auch

* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
