---
title: ICommentCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van opmerkingen van één auteur voor.
type: docs
url: /nl/com.aspose.slides/icommentcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

Stelt een collectie van opmerkingen van één auteur voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Voeg een nieuw commentaar toe aan het einde van een collectie. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Voeg een nieuw modern commentaar toe aan het einde van een collectie. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Voeg een nieuw commentaar in een collectie in op de opgegeven index. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Voeg een nieuw modern commentaar in een collectie in op de opgegeven index. |
| [toArray()](#toArray--) | Maakt en retourneert een array met alle opmerkingen. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Maakt en retourneert een array met alle opmerkingen van het opgegeven bereik. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index in een collectie. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Verwijdert de eerste vindplaats van de opgegeven opmerking in een collectie. |
| [clear()](#clear--) | Verwijdert alle opmerkingen uit een collectie. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```

Haalt het element op op de opgegeven index. Alleen-lezen [IComment](../../com.aspose.slides/icomment).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

Voeg een nieuw commentaar toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Platte tekst van een nieuw commentaar. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia in een presentatie waarin een nieuw commentaar moet worden toegevoegd. |
| position | android.graphics.PointF | Positie op een dia waar een nieuw commentaar moet worden toegevoegd. |
| creationTime | java.util.Date | Tijdstip van het aanmaken van het commentaar. |

**Retour:**
[IComment](../../com.aspose.slides/icomment) - Toegevoegd commentaar.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Voeg een nieuw modern commentaar toe aan het einde van een collectie.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Platte tekst van een nieuw modern commentaar. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia in een presentatie waarin een nieuw modern commentaar moet worden toegevoegd. |
| shape | [IShape](../../com.aspose.slides/ishape) | Vorm op een dia waaraan een nieuw modern commentaar is gekoppeld. |
| position | android.graphics.PointF | Positie op een dia waar een nieuw modern commentaar moet worden toegevoegd. |
| creationTime | java.util.Date | Tijdstip van het aanmaken van het moderne commentaar. |

**Retour:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Toegevoegd modern commentaar.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

Voeg een nieuw commentaar in een collectie in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het element in een collectie waarin het commentaar moet worden ingevoegd. |
| text | java.lang.String | Platte tekst van een nieuw commentaar. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia in een presentatie waarin een nieuw commentaar moet worden toegevoegd. |
| position | android.graphics.PointF | Positie op een dia waar een nieuw commentaar moet worden toegevoegd. |
| creationTime | java.util.Date | Tijdstip van het aanmaken van het commentaar. |

**Retour:**
[IComment](../../com.aspose.slides/icomment) - Ingevoerd commentaar.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Voeg een nieuw modern commentaar in een collectie in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het element in een collectie waarin het moderne commentaar moet worden ingevoegd. |
| text | java.lang.String | Platte tekst van een nieuw modern commentaar. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia in een presentatie waarin een nieuw modern commentaar moet worden toegevoegd. |
| shape | [IShape](../../com.aspose.slides/ishape) | Vorm op een dia waaraan een nieuw modern commentaar is gekoppeld. |
| position | android.graphics.PointF | Positie op een dia waar een nieuw modern commentaar moet worden toegevoegd. |
| creationTime | java.util.Date | Tijdstip van het aanmaken van het moderne commentaar. |

**Retour:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Ingevoerd modern commentaar.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```

Maakt en retourneert een array met alle opmerkingen.

**Retour:**
com.aspose.slides.IComment[] - Array van [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```

Maakt en retourneert een array met alle opmerkingen van het opgegeven bereik.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | int | Een index van de eerste opmerking die moet worden geretourneerd. |
| count | int | Het aantal opmerkingen dat moet worden geretourneerd. |

**Retour:**
com.aspose.slides.IComment[] - Array van [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert het element op de opgegeven index in een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het te verwijderen element. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

Verwijdert de eerste vindplaats van de opgegeven opmerking in een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | De opmerking die uit de collectie moet worden verwijderd. |

### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle opmerkingen uit een collectie.