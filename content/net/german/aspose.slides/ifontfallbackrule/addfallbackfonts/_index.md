---
title: AddFallBackFonts
second_title: Aspose.Slides für .NET-API-Referenz
description: Fügt der Liste der FallBackSchriftarten eine oder mehrere neue Schriftarten hinzu.
type: docs
weight: 50
url: /de/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## AddFallBackFonts(string) {#addfallbackfonts}

Fügt der Liste der FallBack-Schriftarten eine oder mehrere neue Schriftarten hinzu.

```csharp
public void AddFallBackFonts(string fontName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Name oder Namen der Schriftart (durch Komma getrennt) für FallBack |

### Beispiele

```csharp
[C#]
//Neue Instanz von FantFallBackRule erstellen
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");

//Fügt der Regel eine zweite Schriftart hinzu 
newRule.AddFallBackFonts("MS Gothic");
//Dritte und vierte Schriftart zur Regel hinzufügen 
newRule.AddFallBackFonts("Tahoma, Times New Roman");
```

### Siehe auch

* interface [IFontFallBackRule](../../ifontfallbackrule)
* namensraum [Aspose.Slides](../../ifontfallbackrule)
* Montage [Aspose.Slides](../../../)

---

## AddFallBackFonts(string[]) {#addfallbackfonts_1}

Fügt eine neue Schriftart zur Liste der FallBack-Schriftarten hinzu.

```csharp
public void AddFallBackFonts(string[] fontNames)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontNames | String[] | Name oder Namen der Schriftart (durch Komma getrennt) für FallBack |

### Beispiele

```csharp
[C#]
//Neue Instanz von FontFallBackRule erstellen
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");

//Hinzufügen von drei weiteren Schriftarten zur Regel 
newRule.AddFallBackFonts(new string [] {"MS Gothic","Tahoma, Times New Roman"});
```

### Siehe auch

* interface [IFontFallBackRule](../../ifontfallbackrule)
* namensraum [Aspose.Slides](../../ifontfallbackrule)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
