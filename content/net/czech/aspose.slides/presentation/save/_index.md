---
title: Save
second_title: Aspose.Sildes pro .NET API Reference
description: Uloží všechny snímky prezentace do souboru ve zvoleném formátu.
type: docs
weight: 400
url: /cs/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

Uloží všechny snímky prezentace do souboru ve zvoleném formátu.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | String | Cesta k vytvořenému souboru. |
| format | SaveFormat | Formát exportovaných dat. |

### Viz také

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* třída [Presentation](../../presentation)
* jmenný prostor [Aspose.Slides](../../presentation)
* sestavení [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Uloží všechny snímky prezentace do proudu ve zvoleném formátu.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | Stream | Výstupní proud. |
| format | SaveFormat | Formát exportovaných dat. |

### Viz také

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* třída [Presentation](../../presentation)
* jmenný prostor [Aspose.Slides](../../presentation)
* sestavení [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### Viz také

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* rozhraní [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* třída [Presentation](../../presentation)
* jmenný prostor [Aspose.Slides](../../presentation)
* sestavení [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Uloží všechny snímky prezentace do proudu ve zvoleném formátu a s dodatečnými možnostmi.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | Stream | Výstupní proud. |
| format | SaveFormat | Formát exportovaných dat. |
| options | ISaveOptions | Dodatečné možnosti formátu. |

### Výjimky

| výjimka | podmínka |
| --- | --- |
| NotSupportedException | Pokud se pokusíte uložit šifrovaný soubor v žádném formátu Office 2007-2010 |

### Viz také

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* rozhraní [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* třída [Presentation](../../presentation)
* jmenný prostor [Aspose.Slides](../../presentation)
* sestavení [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Uloží všechny snímky prezentace do sady souborů představujících XAML značkování.

```csharp
public void Save(IXamlOptions options)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | IXamlOptions | Možnosti formátu XAML. |

### Příklady

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Viz také

* rozhraní [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* třída [Presentation](../../presentation)
* jmenný prostor [Aspose.Slides](../../presentation)
* sestavení [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Uloží zadané snímky prezentace do souboru ve zvoleném formátu a zachová čísla stránek.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | String | Cesta k vytvořenému souboru. |
| slides | Int32[] | Pole s pozicemi snímků, počínaje 1. |
| format | SaveFormat | Formát exportovaných dat. |

### Výjimky

| výjimka | podmínka |
| --- | --- |
| ArgumentNullException | Když je parametr stream nebo slides null. |
| ArgumentOutOfRangeException | Když parametr slides obsahuje nesprávná čísla stránek. |
| InvalidOperationException | Když je použit nepodporovaný SaveFormat, např. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Viz také

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* třída [Presentation](../../presentation)
* jmenný prostor [Aspose.Slides](../../presentation)
* sestavení [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Uloží zadané snímky prezentace do souboru ve zvoleném formátu a zachová čísla stránek.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | String | Cesta k vytvořenému souboru. |
| slides | Int32[] | Pole s pozicemi snímků, počínaje 1. |
| format | SaveFormat | Formát exportovaných dat. |
| options | ISaveOptions | Dodatečné možnosti formátu. |

### Viz také

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* rozhraní [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* třída [Presentation](../../presentation)
* jmenný prostor [Aspose.Slides](../../presentation)
* sestavení [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Uloží zadané snímky prezentace do proudu ve zvoleném formátu a zachová čísla stránek.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | Stream | Výstupní proud. |
| slides | Int32[] | Pole s pozicemi snímků, počínaje 1. |
| format | SaveFormat | Formát exportovaných dat. |

### Viz také

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* třída [Presentation](../../presentation)
* jmenný prostor [Aspose.Slides](../../presentation)
* sestavení [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Uloží zadané snímky prezentace do proudu ve zvoleném formátu a zachová čísla stránek.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | Stream | Výstupní proud. |
| slides | Int32[] | Pole s pozicemi snímků, počínaje 1. |
| format | SaveFormat | Formát exportovaných dat. |
| options | ISaveOptions | Dodatečné možnosti formátu. |

### Výjimky

| výjimka | podmínka |
| --- | --- |
| ArgumentNullException | Když je parametr stream nebo slides null. |
| ArgumentOutOfRangeException | Když parametr slides obsahuje nesprávná čísla stránek. |
| InvalidOperationException | Když je použit nepodporovaný SaveFormat, např. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Příklady

Následující příklad ukazuje, jak převést PowerPoint do formátu PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail().Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

Následující příklad ukazuje, jak převést PowerPoint do formátu PNG s vlastními rozměry.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    float scaleX = 2f;
    float scaleY = 2f;
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail(scaleX, scaleY).Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

Následující příklad ukazuje, jak převést PowerPoint do formátu PNG s vlastní velikostí.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    Size size = new Size(960, 720);
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail(size).Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

### Viz také

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* rozhraní [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* třída [Presentation](../../presentation)
* jmenný prostor [Aspose.Slides](../../presentation)
* sestavení [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->