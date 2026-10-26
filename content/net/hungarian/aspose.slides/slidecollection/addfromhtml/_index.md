---
title: AddFromHtml
second_title: Aspose.Sildes .NET API hivatkozás
description: Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket.
type: docs
weight: 70
url: /hu/aspose.slides/slidecollection/addfromhtml/
---
## AddFromHtml(string, IExternalResourceResolver, string) {#addfromhtml_5}

Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket.

```csharp
public ISlide[] AddFromHtml(string htmlText, IExternalResourceResolver resolver, string uri)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlText | String | Hozzáadandó HTML. |
| resolver | IExternalResourceResolver | Egy visszahívási objektum a külső objektumok lekéréséhez. Ha ez a paraméter null, akkor az összes külső objektum figyelmen kívül marad. |
| uri | String | A megadott HTML URI-ja. Relatív hivatkozások feloldásához használható. |

### Visszatérési érték

Hozzáadott diákok.

### Lásd még

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(string) {#addfromhtml_4}

Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket.

```csharp
public ISlide[] AddFromHtml(string htmlText)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlText | String | Hozzáadandó HTML. |

### Visszatérési érték

Hozzáadott diákok

### Lásd még

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader, IExternalResourceResolver, string) {#addfromhtml_3}

Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader, IExternalResourceResolver resolver, string uri)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlReader | TextReader | TextReader objektum, amely a HTML fájl forrásaként szolgál. |
| resolver | IExternalResourceResolver | Egy visszahívási objektum a külső objektumok lekéréséhez. Ha ez a paraméter null, akkor az összes külső objektum figyelmen kívül marad. |
| uri | String | A megadott HTML URI-ja. Relatív hivatkozások feloldásához használható. |

### Visszatérési érték

Hozzáadott diákok.

### Lásd még

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader) {#addfromhtml_2}

Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlReader | TextReader | TextReader objektum, amely a HTML fájl forrásaként szolgál. |

### Visszatérési érték

Hozzáadott diákok

### Lásd még

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream, IExternalResourceResolver, string) {#addfromhtml_1}

Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream, IExternalResourceResolver resolver, string uri)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlStream | Stream | Stream objektum, amely a HTML fájl forrásaként szolgál. |
| resolver | IExternalResourceResolver | Egy visszahívási objektum a külső objektumok lekéréséhez. Ha ez a paraméter null, akkor az összes külső objektum figyelmen kívül marad. |
| uri | String | A megadott HTML URI-ja. Relatív hivatkozások feloldásához használható. |

### Visszatérési érték

Hozzáadott diákok.

### Lásd még

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream) {#addfromhtml}

Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| htmlStream | Stream | Stream objektum, amely a HTML fájl forrásaként szolgál. |

### Visszatérési érték

Hozzáadott diákok

### Példák

```csharp
[C#]
// Hozzon létre egy példányt a Presentation osztályból.
using (var presentation = new Presentation())
{
    using (var htmlStream = File.OpenRead("page.html"))
    {
        // Hívja meg az AddFromHtml metódust, és adja át a HTML fájlt.
        presentation.Slides.AddFromHtml(htmlStream);
    }
    // Használja a Save metódust a fájl PowerPoint dokumentumként való mentéséhez.
    presentation.Save("MyPresentation.pptx", SaveFormat.Pptx);
}
```

### Lásd még

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->