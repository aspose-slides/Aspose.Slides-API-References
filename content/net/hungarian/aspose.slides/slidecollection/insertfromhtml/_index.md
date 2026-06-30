---
title: InsertFromHtml
second_title: Aspose.Sildes .NET API referencia
description: Diákat hoz létre HTML szövegből, és a megadott pozícióban beszúrja őket a gyűjteménybe.
type: docs
weight: 140
url: /hu/aspose.slides/slidecollection/insertfromhtml/
---
## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}}

Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti be a gyűjteménybe.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | Int32 | A beszúrás pozíciója. |
| htmlText | String | Hozzáadandó HTML. |
| resolver | IExternalResourceResolver | Egy visszahívási objektum, amely külső objektumok lekérésére szolgál. Ha ez a paraméter null, minden külső objektumot figyelmen kívül hagynak. |
| uri | String | A megadott HTML URI-ja. Relatív hivatkozások feloldására használják. |

### Visszatérési érték

Hozzáadott diák.

### Lásd még

* interfész [ISlide](../../islide)
* interfész [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* osztály [SlideCollection](../../slidecollection)
* névtér [Aspose.Slides](../../slidecollection)
* összeállítás [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti be a gyűjteménybe.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | Int32 | A beszúrás pozíciója. |
| htmlText | String | Hozzáadandó HTML. |
| resolver | IExternalResourceResolver | Egy visszahívási objektum, amely külső objektumok lekérésére szolgál. Ha ez a paraméter null, minden külső objektumot figyelmen kívül hagynak. |
| uri | String | A megadott HTML URI-ja. Relatív hivatkozások feloldására használják. |
| useSlideWithIndexAsStart | Boolean | Ez a jelző meghatározza, hogyan kezdődjön a beszúrás: egy új diától vagy a megadott indexű diától. Ha **true**, akkor az adatbeszúrás a megadott indexű dián egy üres helyről kezdődik. Ha **false**, akkor az adatok a létrehozott diákhoz lesznek hozzáadva. |

### Visszatérési érték

Hozzáadott diák.

### Lásd még

* interfész [ISlide](../../islide)
* interfész [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* osztály [SlideCollection](../../slidecollection)
* névtér [Aspose.Slides](../../slidecollection)
* összeállítás [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti be a gyűjteménybe.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | Int32 | A beszúrás pozíciója. |
| htmlText | String | Hozzáadandó HTML. |

### Visszatérési érték

Hozzáadott diák

### Lásd még

* interfész [ISlide](../../islide)
* osztály [SlideCollection](../../slidecollection)
* névtér [Aspose.Slides](../../slidecollection)
* összeállítás [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti be a gyűjteménybe.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | Int32 | A beszúrás pozíciója. |
| htmlText | String | Hozzáadandó HTML. |
| useSlideWithIndexAsStart | Boolean | Ez a jelző meghatározza, hogyan kezdődjön a beszúrás: egy új diától vagy a megadott indexű diától. Ha **true**, akkor az adatbeszúrás a megadott indexű dián egy üres helyről kezdődik. Ha **false**, akkor az adatok a létrehozott diákhoz lesznek hozzáadva. |

### Visszatérési érték

Hozzáadott diák

### Lásd még

* interfész [ISlide](../../islide)
* osztály [SlideCollection](../../slidecollection)
* névtér [Aspose.Slides](../../slidecollection)
* összeállítás [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti be a gyűjteménybe.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | Int32 | A beszúrás pozíciója. |
| htmlReader | TextReader | TextReader objektum, amely a HTML fájl forrásaként lesz használva. |
| resolver | IExternalResourceResolver | Egy visszahívási objektum, amely külső objektumok lekérésére szolgál. Ha ez a paraméter null, minden külső objektumot figyelmen kívül hagynak. |
| uri | String | A megadott HTML URI-ja. Relatív hivatkozások feloldására használják. |

### Visszatérési érték

Hozzáadott diák.

### Lásd még

* interfész [ISlide](../../islide)
* interfész [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* osztály [SlideCollection](../../slidecollection)
* névtér [Aspose.Slides](../../slidecollection)
* összeállítás [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti be a gyűjteménybe.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | Int32 | A beszúrás pozíciója. |
| htmlReader | TextReader | TextReader objektum, amely a HTML fájl forrásaként lesz használva. |

### Visszatérési érték

Hozzáadott diák

### Lásd még

* interfész [ISlide](../../islide)
* osztály [SlideCollection](../../slidecollection)
* névtér [Aspose.Slides](../../slidecollection)
* összeállítás [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti be a gyűjteménybe.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | Int32 | A beszúrás pozíciója. |
| htmlStream | Stream | Stream objektum, amely a HTML fájl forrásaként lesz használva. |
| resolver | IExternalResourceResolver | Egy visszahívási objektum, amely külső objektumok lekérésére szolgál. Ha ez a paraméter null, minden külső objektumot figyelmen kívül hagynak. |
| uri | String | A megadott HTML URI-ja. Relatív hivatkozások feloldására használják. |

### Visszatérési érték

Hozzáadott diák.

### Lásd még

* interfész [ISlide](../../islide)
* interfész [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* osztály [SlideCollection](../../slidecollection)
* névtér [Aspose.Slides](../../slidecollection)
* összeállítás [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti be a gyűjteménybe.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | Int32 | A beszúrás pozíciója. |
| htmlStream | Stream | Stream objektum, amely a HTML fájl forrásaként lesz használva. |
| resolver | IExternalResourceResolver | Egy visszahívási objektum, amely külső objektumok lekérésére szolgál. Ha ez a paraméter null, minden külső objektumot figyelmen kívül hagynak. |
| uri | String | A megadott HTML URI-ja. Relatív hivatkozások feloldására használják. |
| useSlideWithIndexAsStart | Boolean | Ez a jelző meghatározza, hogyan kezdődjön a beszúrás: egy új diától vagy a megadott indexű diától. Ha **true**, akkor az adatbeszúrás a megadott indexű dián egy üres helyről kezdődik. Ha **false**, akkor az adatok a létrehozott diákhoz lesznek hozzáadva. |

### Visszatérési érték

Hozzáadott diák.

### Lásd még

* interfész [ISlide](../../islide)
* interfész [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* osztály [SlideCollection](../../slidecollection)
* névtér [Aspose.Slides](../../slidecollection)
* összeállítás [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti be a gyűjteménybe.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | Int32 | A beszúrás pozíciója. |
| htmlStream | Stream | Stream objektum, amely a HTML fájl forrásaként lesz használva. |

### Visszatérési érték

Hozzáadott diák

### Lásd még

* interfész [ISlide](../../islide)
* osztály [SlideCollection](../../slidecollection)
* névtér [Aspose.Slides](../../slidecollection)
* összeállítás [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti be a gyűjteménybe.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | Int32 | A beszúrás pozíciója. |
| htmlStream | Stream | Stream objektum, amely a HTML fájl forrásaként lesz használva. |
| useSlideWithIndexAsStart | Boolean | Ez a jelző meghatározza, hogyan kezdődjön a beszúrás: egy új diától vagy a megadott indexű diától. Ha **true**, akkor az adatbeszúrás a megadott indexű dián egy üres helyről kezdődik. Ha **false**, akkor az adatok a létrehozott diákhoz lesznek hozzáadva. |

### Visszatérési érték

Hozzáadott diák

### Lásd még

* interfész [ISlide](../../islide)
* osztály [SlideCollection](../../slidecollection)
* névtér [Aspose.Slides](../../slidecollection)
* összeállítás [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->