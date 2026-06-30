---
title: AddFromHtml
second_title: Aspose.Sildes dla .NET - referencja API
description: Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.
type: docs
weight: 70
url: /pl/aspose.slides/slidecollection/addfromhtml/
---
## AddFromHtml(string, IExternalResourceResolver, string) {#addfromhtml_5}

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

```csharp
public ISlide[] AddFromHtml(string htmlText, IExternalResourceResolver resolver, string uri)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlText | String | Html do dodania. |
| resolver | IExternalResourceResolver | Obiekt wywołania zwrotnego używany do pobierania obiektów zewnętrznych. Jeśli ten parametr jest null, wszystkie obiekty zewnętrzne zostaną zignorowane. |
| uri | String | URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

### Wartość zwracana

Dodane slajdy.

### Zobacz także

* interfejs [ISlide](../../islide)
* interfejs [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* klasa [SlideCollection](../../slidecollection)
* przestrzeń nazw [Aspose.Slides](../../slidecollection)
* biblioteka [Aspose.Slides](../../../)

---

## AddFromHtml(string) {#addfromhtml_4}

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

```csharp
public ISlide[] AddFromHtml(string htmlText)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlText | String | Html do dodania. |

### Wartość zwracana

Dodane slajdy

### Zobacz także

* interfejs [ISlide](../../islide)
* klasa [SlideCollection](../../slidecollection)
* przestrzeń nazw [Aspose.Slides](../../slidecollection)
* biblioteka [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader, IExternalResourceResolver, string) {#addfromhtml_3}

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader, IExternalResourceResolver resolver, string uri)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlReader | TextReader | Obiekt TextReader, który będzie używany jako źródło pliku HTML. |
| resolver | IExternalResourceResolver | Obiekt wywołania zwrotnego używany do pobierania obiektów zewnętrznych. Jeśli ten parametr jest null, wszystkie obiekty zewnętrzne zostaną zignorowane. |
| uri | String | URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

### Wartość zwracana

Dodane slajdy.

### Zobacz także

* interfejs [ISlide](../../islide)
* interfejs [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* klasa [SlideCollection](../../slidecollection)
* przestrzeń nazw [Aspose.Slides](../../slidecollection)
* biblioteka [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader) {#addfromhtml_2}

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlReader | TextReader | Obiekt TextReader, który będzie używany jako źródło pliku HTML. |

### Wartość zwracana

Dodane slajdy

### Zobacz także

* interfejs [ISlide](../../islide)
* klasa [SlideCollection](../../slidecollection)
* przestrzeń nazw [Aspose.Slides](../../slidecollection)
* biblioteka [Aspose.Slides](../../../)

---

## AddFromHtml(Stream, IExternalResourceResolver, string) {#addfromhtml_1}

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream, IExternalResourceResolver resolver, string uri)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlStream | Stream | Obiekt Stream, który będzie używany jako źródło pliku HTML. |
| resolver | IExternalResourceResolver | Obiekt wywołania zwrotnego używany do pobierania obiektów zewnętrznych. Jeśli ten parametr jest null, wszystkie obiekty zewnętrzne zostaną zignorowane. |
| uri | String | URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

### Wartość zwracana

Dodane slajdy.

### Zobacz także

* interfejs [ISlide](../../islide)
* interfejs [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* klasa [SlideCollection](../../slidecollection)
* przestrzeń nazw [Aspose.Slides](../../slidecollection)
* biblioteka [Aspose.Slides](../../../)

---

## AddFromHtml(Stream) {#addfromhtml}

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlStream | Stream | Obiekt Stream, który będzie używany jako źródło pliku HTML. |

### Wartość zwracana

Dodane slajdy

### Przykłady

```csharp
[C#]
// Utwórz instancję klasy Presentation.
using (var presentation = new Presentation())
{
    using (var htmlStream = File.OpenRead("page.html"))
    {
		// Wywołaj metodę AddFromHtml i przekaż plik HTML.
        presentation.Slides.AddFromHtml(htmlStream);
    }
	// Użyj metody Save, aby zapisać plik jako dokument PowerPoint.
    presentation.Save("MyPresentation.pptx", SaveFormat.Pptx);
}
```

### Zobacz także

* interfejs [ISlide](../../islide)
* klasa [SlideCollection](../../slidecollection)
* przestrzeń nazw [Aspose.Slides](../../slidecollection)
* biblioteka [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->