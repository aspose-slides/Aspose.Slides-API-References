---
title: Save
second_title: Aspose.Sildes .NET API hivatkozás
description: Ment minden diát egy bemutatóból egy fájlba a megadott formátummal.
type: docs
weight: 400
url: /hu/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

Ment minden diát egy bemutatóból egy fájlba a megadott formátummal.

```csharp
public void Save(string fname, SaveFormat format)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | String | Az létrehozott fájl elérési útja. |
| format | SaveFormat | Az exportált adatok formátuma. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* osztály [Presentation](../../presentation)
* névtér [Aspose.Slides](../../presentation)
* összeállítás [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Ment minden diát egy bemutatóból egy adatfolyamba a megadott formátummal.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | Stream | Kimeneti adatfolyam. |
| format | SaveFormat | Az exportált adatok formátuma. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* osztály [Presentation](../../presentation)
* névtér [Aspose.Slides](../../presentation)
* összeállítás [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfész [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* osztály [Presentation](../../presentation)
* névtér [Aspose.Slides](../../presentation)
* összeállítás [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Ment minden diát egy bemutatóból egy adatfolyamba a megadott formátummal és további beállításokkal.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | Stream | Kimeneti adatfolyam. |
| format | SaveFormat | Az exportált adatok formátuma. |
| options | ISaveOptions | További formátumbeállítások. |

### Kivételek

| kivétel | feltétel |
| --- | --- |
| NotSupportedException | Ha titkosított fájlt próbál menteni olyan formátumban, amely nem Office 2007-2010 |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfész [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* osztály [Presentation](../../presentation)
* névtér [Aspose.Slides](../../presentation)
* összeállítás [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Ment minden diát egy bemutatóból egy XAML jelöléskészletet képviselő fájlok halmazába.

```csharp
public void Save(IXamlOptions options)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | IXamlOptions | A XAML formátumbeállítások. |

### Példák

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Lásd még

* interfész [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* osztály [Presentation](../../presentation)
* névtér [Aspose.Slides](../../presentation)
* összeállítás [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Ment megadott diákat egy bemutatóból egy fájlba a megadott formátummal, az oldalszámok megtartásával.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | String | Az létrehozott fájl elérési útja. |
| slides | Int32[] | A diákat tartalmazó tömb, 1-től kezdődően. |
| format | SaveFormat | Az exportált adatok formátuma. |

### Kivételek

| kivétel | feltétel |
| --- | --- |
| ArgumentNullException | Ha a stream vagy a slides paraméter null értékű. |
| ArgumentOutOfRangeException | Ha a slides paraméter hibás oldalszámokat tartalmaz. |
| InvalidOperationException | Ha nem támogatott SaveFormat van használva, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* osztály [Presentation](../../presentation)
* névtér [Aspose.Slides](../../presentation)
* összeállítás [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Ment megadott diákat egy bemutatóból egy fájlba a megadott formátummal, az oldalszámok megtartásával.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | String | Az létrehozott fájl elérési útja. |
| slides | Int32[] | A diákat tartalmazó tömb, 1-től kezdődően. |
| format | SaveFormat | Az exportált adatok formátuma. |
| options | ISaveOptions | További formátumbeállítások. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfész [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* osztály [Presentation](../../presentation)
* névtér [Aspose.Slides](../../presentation)
* összeállítás [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Ment megadott diákat egy bemutatóból egy adatfolyamba a megadott formátummal, az oldalszámok megtartásával.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | Stream | Kimeneti adatfolyam. |
| slides | Int32[] | A diákat tartalmazó tömb, 1-től kezdődően. |
| format | SaveFormat | Az exportált adatok formátuma. |

### Lásd még

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* osztály [Presentation](../../presentation)
* névtér [Aspose.Slides](../../presentation)
* összeállítás [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Ment megadott diákat egy bemutatóból egy adatfolyamba a megadott formátummal, az oldalszámok megtartásával.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | Stream | Kimeneti adatfolyam. |
| slides | Int32[] | A diákat tartalmazó tömb, 1-től kezdődően. |
| format | SaveFormat | Az exportált adatok formátuma. |
| options | ISaveOptions | További formátumbeállítások. |

### Kivételek

| kivétel | feltétel |
| --- | --- |
| ArgumentNullException | Ha a stream vagy a slides paraméter null értékű. |
| ArgumentOutOfRangeException | Ha a slides paraméter hibás oldalszámokat tartalmaz. |
| InvalidOperationException | Ha nem támogatott SaveFormat van használva, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Példák

Az alábbi példa bemutatja, hogyan konvertálhatunk PowerPointot PNG formátumba.

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

Az alábbi példa bemutatja, hogyan konvertálhatunk PowerPointot PNG formátumba egyéni méretekkel.

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

Az alábbi példa bemutatja, hogyan konvertálhatunk PowerPointot PNG formátumba egyéni mérettel.

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
* interfész [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* osztály [Presentation](../../presentation)
* névtér [Aspose.Slides](../../presentation)
* összeállítás [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->