---
title: CommentCollection
second_title: Aspose.Slides voor Java API Referentie
description: Stelt een collectie van commentaren van één auteur voor.
type: docs
url: /nl/com.aspose.slides/commentcollection/
---
**Erfenis:**  
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**  
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

Stelt een collectie van commentaren van één auteur voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Voegt een nieuw commentaar toe aan het einde van een collectie. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Voegt een nieuw modern commentaar toe aan het einde van een collectie. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Voegt een nieuw commentaar in een collectie in op de opgegeven index. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Voegt een nieuw modern commentaar in een collectie in op de opgegeven index. |
| [toArray()](#toArray--) | Maakt een array met alle commentaren aan en retourneert deze. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Maakt een array met alle commentaren uit het opgegeven bereik aan en retourneert deze. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index in een collectie. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Verwijdert de eerste verschijning van het opgegeven commentaar in een collectie. |
| [clear()](#clear--) | Verwijdert alle commentaren uit een collectie. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java iterator voor de volledige collectie. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Zoekt een commentaar in de collectie op index. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen van de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen  boolean . |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatie-root. Alleen-lezen  Object . |
### size() {#size--}
```
public final int size()
```

Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. Alleen-lezen  int .

**Retour:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

Haalt het element op op de opgegeven index. Alleen-lezen [Comment](../../com.aspose.slides/comment).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Voegt een nieuw commentaar toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Platte tekst van een nieuw commentaar. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia in een presentatie waarin een nieuw commentaar moet worden toegevoegd. |
| position | java.awt.geom.Point2D.Float | Positie op een dia waar een nieuw commentaar moet worden toegevoegd. |
| creationTime | java.util.Date | Tijdstip van het aanmaken van het commentaar. |

**Retour:**
[IComment](../../com.aspose.slides/icomment) - Toegevoegd commentaar.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Voegt een nieuw modern commentaar toe aan het einde van een collectie.

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
| text | java.lang.String | Platte tekst van een nieuw modern commentaar. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia in een presentatie waarin een nieuw modern commentaar moet worden toegevoegd. |
| shape | [IShape](../../com.aspose.slides/ishape) | Vorm op een dia waaraan een nieuw modern commentaar is gekoppeld. |
| position | java.awt.geom.Point2D.Float | Positie op een dia waar een nieuw modern commentaar moet worden toegevoegd. |
| creationTime | java.util.Date | Tijdstip van het aanmaken van een modern commentaar. |

**Retour:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Toegevoegd modern commentaar.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Voegt een nieuw commentaar in een collectie in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het element in een collectie waarop het commentaar moet worden ingevoegd. |
| text | java.lang.String | Platte tekst van een nieuw commentaar. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia in een presentatie waarin een nieuw commentaar moet worden toegevoegd. |
| position | java.awt.geom.Point2D.Float | Positie op een dia waar een nieuw commentaar moet worden toegevoegd. |
| creationTime | java.util.Date | Tijdstip van het aanmaken van het commentaar. |

**Retour:**
[IComment](../../com.aspose.slides/icomment) - Ingevoegd commentaar.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Voegt een nieuw modern commentaar in een collectie in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het element in een collectie waarop het moderne commentaar moet worden ingevoegd. |
| text | java.lang.String | Platte tekst van een nieuw modern commentaar. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia in een presentatie waarin een nieuw modern commentaar moet worden toegevoegd. |
| shape | [IShape](../../com.aspose.slides/ishape) | Vorm op een dia waaraan een nieuw modern commentaar is gekoppeld. |
| position | java.awt.geom.Point2D.Float | Positie op een dia waar een nieuw modern commentaar moet worden toegevoegd. |
| creationTime | java.util.Date | Tijdstip van het aanmaken van een modern commentaar. |

**Retour:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Ingevoegd modern commentaar.
### toArray() {#toArray--}
```
public final IComment[] toArray()
```

Maakt een array met alle commentaren aan en retourneert deze.

**Retour:**
com.aspose.slides.IComment[] - Array van [Comment](../../com.aspose.slides/comment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

Maakt een array met alle commentaren uit het opgegeven bereik aan en retourneert deze.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | int | Een index van het eerste commentaar om te retourneren. |
| count | int | Een aantal commentaren om te retourneren. |

**Retour:**
com.aspose.slides.IComment[] - Array van [Comment](../../com.aspose.slides/comment).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert het element op de opgegeven index in een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index van het te verwijderen element. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

Verwijdert de eerste verschijning van het opgegeven commentaar in een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Het commentaar dat uit de collectie moet worden verwijderd. |

### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle commentaren uit een collectie.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

Retourneert een enumerator die door de collectie iterereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

Retourneert een java iterator voor de volledige collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Een java.util.Iterator voor de volledige collectie.
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

Zoekt een commentaar in de collectie op index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| idx | int | Unieke index van een commentaar om te vinden  int . |

**Retour:**
[IComment](../../com.aspose.slides/icomment) - Gevonden commentaar of null [IComment](../../com.aspose.slides/icomment).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopieert alle elementen van de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doelarray. |
| index | int | Startindex in de doelarray. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen  boolean .

**Retour:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een synchronisatie-root. Alleen-lezen  Object .

**Retour:**
java.lang.Object