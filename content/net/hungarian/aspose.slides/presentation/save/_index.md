---
title: Save
second_title: Aspose.Sildes .NET API-referencia
description: Ment minden diát egy prezentációból a megadott formátumú fájlba.
type: docs
weight: 390
url: /hu/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

Ment minden diát egy prezentációból a megadott formátumú fájlba.

```csharp
public void Save(string fname, SaveFormat format)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | String | Az elkészített fájl elérési útja. |
| format | SaveFormat | Az exportált adatok formátuma. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Ment minden diát egy prezentációból egy adatfolyamba a megadott formátumban.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | Stream | Kimeneti adatfolyam. |
| format | SaveFormat | Az exportált adatok formátuma. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Ment minden diát egy prezentációból egy adatfolyamba a megadott formátumban, plusz további beállításokkal.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | Stream | Kimeneti adatfolyam. |
| format | SaveFormat | Az exportált adatok formátuma. |
| options | ISaveOptions | További formátumbeállítások. |

### Kivétel

| kivétel | feltétel |
| --- | --- |
| NotSupportedException | Ha titkosított fájlt próbál menteni a nem Office 2007-2010 formátumokban |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Ment minden diát egy prezentációból egy sor fájlba, amely XAML jelölést reprezentál.

```csharp
public void Save(IXamlOptions options)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | IXamlOptions | A XAML formátum beállításai. |

### Példák

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Lásd még

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Ment egy prezentáció kiválasztott diáit egy fájlba a megadott formátummal, az oldalszámok megtartásával.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | String | Az elkészített fájl elérési útja. |
| slides | Int32[] | Diapozíciók tömbje, 1-től kezdve. |
| format | SaveFormat | Az exportált adatok formátuma. |

### Kivétel

| kivétel | feltétel |
| --- | --- |
| ArgumentNullException | Ha a stream vagy a slides paraméter null. |
| ArgumentOutOfRangeException | Ha a slides paraméter hibás oldalszámokat tartalmaz. |
| InvalidOperationException | Ha egy nem támogatott SaveFormat-ot használnak, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Ment egy prezentáció kiválasztott diáit egy fájlba a megadott formátummal, az oldalszámok megtartásával.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | String | Az elkészített fájl elérési útja. |
| slides | Int32[] | Diapozíciók tömbje, 1-től kezdve. |
| format | SaveFormat | Az exportált adatok formátuma. |
| options | ISaveOptions | További formátumbeállítások. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Ment egy prezentáció kiválasztott diáit egy adatfolyamba a megadott formátumban, az oldalszámok megtartásával.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | Stream | Kimeneti adatfolyam. |
| slides | Int32[] | Diapozíciók tömbje, 1-től kezdve. |
| format | SaveFormat | Az exportált adatok formátuma. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Ment egy prezentáció kiválasztott diáit egy adatfolyamba a megadott formátumban, az oldalszámok megtartásával.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | Stream | Kimeneti adatfolyam. |
| slides | Int32[] | Diapozíciók tömbje, 1-től kezdve. |
| format | SaveFormat | Az exportált adatok formátuma. |
| options | ISaveOptions | További formátumbeállítások. |

### Kivétel

| kivétel | feltétel |
| --- | --- |
| ArgumentNullException | Ha a stream vagy a slides paraméter null. |
| ArgumentOutOfRangeException | Ha a slides paraméter hibás oldalszámokat tartalmaz. |
| InvalidOperationException | Ha egy nem támogatott SaveFormat-ot használnak, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Példák

A következő példa bemutatja, hogyan lehet a PowerPoint-ot PNG-re konvertálni.

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

A következő példa bemutatja, hogyan lehet a PowerPoint-ot egyedi méretekkel PNG-re konvertálni.

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

A következő példa bemutatja, hogyan lehet a PowerPoint-ot egyedi mérettel PNG-re konvertálni.

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

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->