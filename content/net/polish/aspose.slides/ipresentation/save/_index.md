---
title: Save
second_title: Aspose.Sildes dla .NET referencja API
description: Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie.
type: docs
weight: 380
url: /pl/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | String | Ścieżka do utworzonego pliku. |
| format | SaveFormat | Format wyeksportowanych danych. |

### Zobacz także

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfejs [IPresentation](../../ipresentation)
* przestrzeń nazw [Aspose.Slides](../../ipresentation)
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
| format | SaveFormat | Format wyeksportowanych danych. |

### Zobacz także

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfejs [IPresentation](../../ipresentation)
* przestrzeń nazw [Aspose.Slides](../../ipresentation)
* zestaw [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie oraz z dodatkowymi opcjami.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | String | Ścieżka do utworzonego pliku. |
| format | SaveFormat | Format wyeksportowanych danych. |
| options | ISaveOptions | Dodatkowe opcje formatu. |

### Zobacz także

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfejs [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interfejs [IPresentation](../../ipresentation)
* przestrzeń nazw [Aspose.Slides](../../ipresentation)
* zestaw [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie oraz z dodatkowymi opcjami.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | Stream | Strumień wyjściowy. |
| format | SaveFormat | Format wyeksportowanych danych. |
| options | ISaveOptions | Dodatkowe opcje formatu. |

### Wyjątki

| wyjątek | warunek |
| --- | --- |
| NotSupportedException | Jeśli spróbujesz zapisać zaszyfrowany plik w formacie innym niż Office 2007-2010 |

### Zobacz także

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfejs [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interfejs [IPresentation](../../ipresentation)
* przestrzeń nazw [Aspose.Slides](../../ipresentation)
* zestaw [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Zapisuje określone slajdy prezentacji do pliku w określonym formacie.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | String | Ścieżka do utworzonego pliku. |
| slides | Int32[] | Tablica z pozycjami slajdów, zaczynając od 1. |
| format | SaveFormat | Format wyeksportowanych danych. |

### Wyjątki

| wyjątek | warunek |
| --- | --- |
| ArgumentNullException | Gdy parametr stream lub slides jest równy null. |
| ArgumentOutOfRangeException | Gdy parametr slides zawiera nieprawidłowe numery stron. |
| InvalidOperationException | Gdy używany jest nieobsługiwany SaveFormat, np. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Zobacz także

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfejs [IPresentation](../../ipresentation)
* przestrzeń nazw [Aspose.Slides](../../ipresentation)
* zestaw [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Zapisuje określone slajdy prezentacji do pliku w określonym formacie.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | String | Ścieżka do utworzonego pliku. |
| slides | Int32[] | Tablica z pozycjami slajdów, zaczynając od 1. |
| format | SaveFormat | Format wyeksportowanych danych. |
| options | ISaveOptions | Dodatkowe opcje formatu. |

### Wyjątki

| wyjątek | warunek |
| --- | --- |
| ArgumentNullException | Gdy parametr stream lub slides jest równy null. |
| ArgumentOutOfRangeException | Gdy parametr slides zawiera nieprawidłowe numery stron. |
| InvalidOperationException | Gdy używany jest nieobsługiwany SaveFormat, np. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Zobacz także

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfejs [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interfejs [IPresentation](../../ipresentation)
* przestrzeń nazw [Aspose.Slides](../../ipresentation)
* zestaw [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Zapisuje określone slajdy prezentacji do strumienia w określonym formacie.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | Stream | Strumień wyjściowy. |
| slides | Int32[] | Tablica z pozycjami slajdów, zaczynając od 1. |
| format | SaveFormat | Format wyeksportowanych danych. |

### Wyjątki

| wyjątek | warunek |
| --- | --- |
| ArgumentNullException | Gdy parametr stream lub slides jest równy null. |
| ArgumentOutOfRangeException | Gdy parametr slides zawiera nieprawidłowe numery stron. |
| InvalidOperationException | Gdy używany jest nieobsługiwany SaveFormat, np. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Zobacz także

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfejs [IPresentation](../../ipresentation)
* przestrzeń nazw [Aspose.Slides](../../ipresentation)
* zestaw [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Zapisuje określone slajdy prezentacji do strumienia w określonym formacie.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | Stream | Strumień wyjściowy. |
| slides | Int32[] | Tablica z pozycjami slajdów, zaczynając od 1. |
| format | SaveFormat | Format wyeksportowanych danych. |
| options | ISaveOptions | Dodatkowe opcje formatu. |

### Wyjątki

| wyjątek | warunek |
| --- | --- |
| ArgumentNullException | Gdy parametr stream lub slides jest równy null. |
| ArgumentOutOfRangeException | Gdy parametr slides zawiera nieprawidłowe numery stron. |
| InvalidOperationException | Gdy używany jest nieobsługiwany SaveFormat, np. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Zobacz także

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interfejs [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interfejs [IPresentation](../../ipresentation)
* przestrzeń nazw [Aspose.Slides](../../ipresentation)
* zestaw [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Zapisuje wszystkie slajdy prezentacji do zestawu plików reprezentujących znaczniki XAML.

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
* interfejs [IPresentation](../../ipresentation)
* przestrzeń nazw [Aspose.Slides](../../ipresentation)
* zestaw [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->