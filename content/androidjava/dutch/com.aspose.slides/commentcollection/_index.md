---
title: CommentCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling opmerkingen van één auteur voor.
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

Stelt een verzameling opmerkingen van één auteur voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Voegt een nieuwe opmerking toe aan het einde van een collectie. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Voegt een nieuwe moderne opmerking toe aan het einde van een collectie. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Voegt een nieuwe opmerking in een collectie in op de opgegeven index. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Voegt een nieuwe moderne opmerking in een collectie in op de opgegeven index. |
| [toArray()](#toArray--) | Maakt een array met alle opmerkingen aan en retourneert deze. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Maakt een array met alle opmerkingen uit het opgegeven bereik aan en retourneert deze. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index in een collectie. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Verwijdert de eerste instantie van de opgegeven opmerking in een collectie. |
| [clear()](#clear--) | Verwijdert alle opmerkingen uit een collectie. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een Java-iterator voor de volledige collectie. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Zoekt een opmerking in de collectie op basis van index. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen van de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
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
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```


Voegt een nieuwe opmerking toe aan het einde van een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Platte tekst van een nieuwe opmerking. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia in een presentatie waarin de nieuwe opmerking moet worden toegevoegd. |
| position | android.graphics.PointF | Positie op een dia waar de nieuwe opmerking moet worden toegevoegd. |
| creationTime | java.util.Date | Tijd van aanmaak van de opmerking. |

**Retour:**
[IComment](../../com.aspose.slides/icomment) - Toegevoegde opmerking.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


Voegt een nieuwe moderne opmerking toe aan het einde van een collectie.

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
| text | java.lang.String | Platte tekst van een nieuwe moderne opmerking. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia in een presentatie waarin de nieuwe moderne opmerking moet worden toegevoegd. |
| shape | [IShape](../../com.aspose.slides/ishape) | Vorm op een dia waaraan een nieuwe moderne opmerking is gekoppeld. |
| position | android.graphics.PointF | Positie op een dia waar de nieuwe moderne opmerking moet worden toegevoegd. |
| creationTime | java.util.Date | Tijd van aanmaak van de moderne opmerking. |

**Retour:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Toegevoegde moderne opmerking.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```


Voegt een nieuwe opmerking in een collectie in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het element in een collectie waarin de opmerking moet worden ingevoegd. |
| text | java.lang.String | Platte tekst van een nieuwe opmerking. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia in een presentatie waarin de nieuwe opmerking moet worden toegevoegd. |
| position | android.graphics.PointF | Positie op een dia waar de nieuwe opmerking moet worden toegevoegd. |
| creationTime | java.util.Date | Tijd van aanmaak van de opmerking. |

**Retour:**
[IComment](../../com.aspose.slides/icomment) - Ingevoegde opmerking.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


Voegt een nieuwe moderne opmerking in een collectie in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het element in een collectie waarin de moderne opmerking moet worden ingevoegd. |
| text | java.lang.String | Platte tekst van een nieuwe moderne opmerking. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia in een presentatie waarin de nieuwe moderne opmerking moet worden toegevoegd. |
| shape | [IShape](../../com.aspose.slides/ishape) | Vorm op een dia waaraan een nieuwe moderne opmerking is gekoppeld. |
| position | android.graphics.PointF | Positie op een dia waar de nieuwe moderne opmerking moet worden toegevoegd. |
| creationTime | java.util.Date | Tijd van aanmaak van de moderne opmerking. |

**Retour:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Ingevoegde moderne opmerking.
### toArray() {#toArray--}
```
public final IComment[] toArray()
```


Maakt een array met alle opmerkingen aan en retourneert deze.

**Retour:**
com.aspose.slides.IComment[] - Array van [Comment](../../com.aspose.slides/comment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```


Maakt een array met alle opmerkingen uit het opgegeven bereik aan en retourneert deze.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | int | Een index van de eerste opmerking die moet worden geretourneerd. |
| count | int | Een aantal opmerkingen om te retourneren. |

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
| index | int | De nulgebaseerde index van het te verwijderen element. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```


Verwijdert de eerste instantie van de opgegeven opmerking in een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | De opmerking die uit een collectie moet worden verwijderd. |

### clear() {#clear--}
```
public final void clear()
```


Verwijdert alle opmerkingen uit een collectie.

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


Retourneert een Java-iterator voor de volledige collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Een java.util.Iterator voor de volledige collectie.
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```


Zoekt een opmerking in de collectie op basis van index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| idx | int | Unieke index van een opmerking om te vinden  int . |

**Retour:**
[IComment](../../com.aspose.slides/icomment) - Gevonden opmerking of null [IComment](../../com.aspose.slides/icomment).
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


Retourneert een synchronatiewortel. Alleen-lezen  Object .

**Retour:**
java.lang.Object