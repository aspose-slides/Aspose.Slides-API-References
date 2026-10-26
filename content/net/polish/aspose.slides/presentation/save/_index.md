---
title: Save
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie.
type: docs
weight: 390
url: /pl/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | String | Ścieżka do tworzonego pliku. |
| format | SaveFormat | Format eksportowanych danych. |

### Zobacz także

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* klasa [Presentation](../../presentation)
* przestrzeń nazw [Aspose.Slides](../../presentation)
* zestaw [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | Stream | Strumień wyjściowy. |
| format | SaveFormat | Format eksportowanych danych. |

### Zobacz także

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* klasa [Presentation](../../presentation)
* przestrzeń nazw [Aspose.Slides](../../presentation)
* zestaw [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### Zobacz także

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfejs [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* klasa [Presentation](../../presentation)
* przestrzeń nazw [Aspose.Slides](../../presentation)
* zestaw [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie i z dodatkowymi opcjami.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | Stream | Strumień wyjściowy. |
| format | SaveFormat | Format eksportowanych danych. |
| options | ISaveOptions | Dodatkowe opcje formatu. |

### Wyjątki

| Wyjątek | Warunek |
| --- | --- |
| NotSupportedException | Jeśli spróbujesz zapisać zaszyfrowany plik w formacie innym niż Office 2007-2010 |

### Zobacz także

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfejs [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* klasa [Presentation](../../presentation)
* przestrzeń nazw [Aspose.Slides](../../presentation)
* zestaw [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Zapisuje wszystkie slajdy prezentacji do zestawu plików reprezentujących znacznik XAML.

```csharp
public void Save(IXamlOptions options)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | IXamlOptions | Opcje formatu XAML. |

### Przykłady

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Zobacz także

* interfejs [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* klasa [Presentation](../../presentation)
* przestrzeń nazw [Aspose.Slides](../../presentation)
* zestaw [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Zapisuje określone slajdy prezentacji do pliku w określonym formacie, zachowując numerację stron.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | String | Ścieżka do tworzonego pliku. |
| slides | Int32[] | Tablica pozycji slajdów, zaczynając od 1. |
| format | SaveFormat | Format eksportowanych danych. |

### Wyjątki

| Wyjątek | Warunek |
| --- | --- |
| ArgumentNullException | Gdy parametr stream lub slides jest równy null. |
| ArgumentOutOfRangeException | Gdy parametr slides zawiera nieprawidłowe numery slajdów. |
| InvalidOperationException | Gdy użyto nieobsługiwanego SaveFormat, np. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Zobacz także

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* klasa [Presentation](../../presentation)
* przestrzeń nazw [Aspose.Slides](../../presentation)
* zestaw [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Zapisuje określone slajdy prezentacji do pliku w określonym formacie, zachowując numerację stron.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | String | Ścieżka do tworzonego pliku. |
| slides | Int32[] | Tablica pozycji slajdów, zaczynając od 1. |
| format | SaveFormat | Format eksportowanych danych. |
| options | ISaveOptions | Dodatkowe opcje formatu. |

### Zobacz także

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfejs [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* klasa [Presentation](../../presentation)
* przestrzeń nazw [Aspose.Slides](../../presentation)
* zestaw [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Zapisuje określone slajdy prezentacji do strumienia w określonym formacie, zachowując numerację stron.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | Stream | Strumień wyjściowy. |
| slides | Int32[] | Tablica pozycji slajdów, zaczynając od 1. |
| format | SaveFormat | Format eksportowanych danych. |

### Zobacz także

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* klasa [Presentation](../../presentation)
* przestrzeń nazw [Aspose.Slides](../../presentation)
* zestaw [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Zapisuje określone slajdy prezentacji do strumienia w określonym formacie, zachowując numerację stron.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | Stream | Strumień wyjściowy. |
| slides | Int32[] | Tablica pozycji slajdów, zaczynając od 1. |
| format | SaveFormat | Format eksportowanych danych. |
| options | ISaveOptions | Dodatkowe opcje formatu. |

### Wyjątki

| Wyjątek | Warunek |
| --- | --- |
| ArgumentNullException | Gdy parametr stream lub slides jest równy null. |
| ArgumentOutOfRangeException | Gdy parametr slides zawiera nieprawidłowe numery slajdów. |
| InvalidOperationException | Gdy użyto nieobsługiwanego SaveFormat, np. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Przykłady

Poniższy przykład pokazuje, jak przekonwertować PowerPoint na PNG.

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

Poniższy przykład pokazuje, jak przekonwertować PowerPoint na PNG z niestandardowymi wymiarami.

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

Poniższy przykład pokazuje, jak przekonwertować PowerPoint na PNG z niestandardowym rozmiarem.

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

### Zobacz także

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfejs [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* klasa [Presentation](../../presentation)
* przestrzeń nazw [Aspose.Slides](../../presentation)
* zestaw [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->