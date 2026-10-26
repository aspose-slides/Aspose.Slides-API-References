---
title: ICommentCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een verzameling opmerkingen van één auteur voor.
type: docs
url: /nl/com.aspose.slides/icommentcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

Stelt een verzameling opmerkingen van één auteur voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op de opgegeven index op. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Voegt een nieuwe opmerking toe aan het einde van een verzameling. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Voegt een nieuwe moderne opmerking toe aan het einde van een verzameling. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Voegt een nieuwe opmerking in een verzameling in op de opgegeven index. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Voegt een nieuwe moderne opmerking in een verzameling in op de opgegeven index. |
| [toArray()](#toArray--) | Maakt een array met alle opmerkingen en retourneert deze. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Maakt een array met alle opmerkingen uit het opgegeven bereik en retourneert deze. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index in een verzameling. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Verwijdert de eerste instantie van de opgegeven opmerking in een verzameling. |
| [clear()](#clear--) | Verwijdert alle opmerkingen uit een verzameling. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```


Haalt het element op de opgegeven index op. Alleen-lezen [IComment](../../com.aspose.slides/icomment).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```


Voegt een nieuwe opmerking toe aan het einde van een verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Platte tekst van een nieuwe opmerking. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia in een presentatie waarin een nieuwe opmerking moet worden toegevoegd. |
| position | java.awt.geom.Point2D.Float | Positie op een dia waar een nieuwe opmerking moet worden toegevoegd. |
| creationTime | java.util.Date | Tijdstip van het aanmaken van de opmerking. |

**Retour:**
[IComment](../../com.aspose.slides/icomment) - Toegevoegde opmerking.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```


Voegt een nieuwe moderne opmerking toe aan het einde van een verzameling.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Platte tekst van een nieuwe moderne opmerking. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia in een presentatie waarin een nieuwe moderne opmerking moet worden toegevoegd. |
| shape | [IShape](../../com.aspose.slides/ishape) | Vorm op een dia waaraan een nieuwe moderne opmerking is gekoppeld. |
| position | java.awt.geom.Point2D.Float | Positie op een dia waar een nieuwe moderne opmerking moet worden toegevoegd. |
| creationTime | java.util.Date | Tijdstip van het aanmaken van de moderne opmerking. |

**Retour:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Toegevoegde moderne opmerking.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```


Voegt een nieuwe opmerking in een verzameling in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het element in een verzameling waarin de opmerking moet worden ingevoegd. |
| text | java.lang.String | Platte tekst van een nieuwe opmerking. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia in een presentatie waarin een nieuwe opmerking moet worden toegevoegd. |
| position | java.awt.geom.Point2D.Float | Positie op een dia waar een nieuwe opmerking moet worden toegevoegd. |
| creationTime | java.util.Date | Tijdstip van het aanmaken van de opmerking. |

**Retour:**
[IComment](../../com.aspose.slides/icomment) - Ingevoegde opmerking.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```


Voegt een nieuwe moderne opmerking in een verzameling in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het element in een verzameling waarin de moderne opmerking moet worden ingevoegd. |
| text | java.lang.String | Platte tekst van een nieuwe moderne opmerking. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia in een presentatie waarin een nieuwe moderne opmerking moet worden toegevoegd. |
| shape | [IShape](../../com.aspose.slides/ishape) | Vorm op een dia waaraan een nieuwe moderne opmerking is gekoppeld. |
| position | java.awt.geom.Point2D.Float | Positie op een dia waar een nieuwe moderne opmerking moet worden toegevoegd. |
| creationTime | java.util.Date | Tijdstip van het aanmaken van de moderne opmerking. |

**Retour:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Ingevoegde moderne opmerking.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```


Maakt een array met alle opmerkingen en retourneert deze.

**Retour:**
com.aspose.slides.IComment[] - Array van [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```


Maakt een array met alle opmerkingen uit het opgegeven bereik en retourneert deze.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | int | Een index van de eerste opmerking die moet worden geretourneerd. |
| count | int | Een aantal opmerkingen om te retourneren. |

**Retour:**
com.aspose.slides.IComment[] - Array van [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Verwijdert het element op de opgegeven index in een verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index van het te verwijderen element. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```


Verwijdert de eerste instantie van de opgegeven opmerking in een verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | De opmerking die uit een verzameling moet worden verwijderd. |

### clear() {#clear--}
```
public abstract void clear()
```


Verwijdert alle opmerkingen uit een verzameling.