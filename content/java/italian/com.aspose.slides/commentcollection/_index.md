---
title: CommentCollection
second_title: Aspose.Slides per Java API Reference
description: Rappresenta una raccolta di commenti di un autore.
type: docs
url: /it/com.aspose.slides/commentcollection/
---
**Ereditarietà:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

Rappresenta una raccolta di commenti di un autore.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Restituisce il numero di elementi effettivamente contenuti nella raccolta. |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Aggiunge un nuovo commento alla fine della raccolta. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Aggiunge un nuovo commento moderno alla fine della raccolta. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Inserisce un nuovo commento in una raccolta all'indice specificato. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Inserisce un nuovo commento moderno in una raccolta all'indice specificato. |
| [toArray()](#toArray--) | Crea e restituisce un array con tutti i commenti. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crea e restituisce un array con tutti i commenti dell'intervallo specificato. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato in una raccolta. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Rimuove la prima occorrenza del commento specificato in una raccolta. |
| [clear()](#clear--) | Rimuove tutti i commenti da una raccolta. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iterator java per l'intera raccolta. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Trova un commento nella raccolta per indice. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi dalla raccolta nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
### size() {#size--}
```
public final int size()
```

Restituisce il numero di elementi effettivamente contenuti nella raccolta. Solo lettura  int .

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

Restituisce l'elemento all'indice specificato. Solo lettura [Comment](../../com.aspose.slides/comment).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Aggiunge un nuovo commento alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo semplice di un nuovo commento. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva nella presentazione in cui aggiungere un nuovo commento. |
| position | java.awt.geom.Point2D.Float | Posizione sulla diapositiva in cui aggiungere un nuovo commento. |
| creationTime | java.util.Date | Ora di creazione del commento. |

**Restituisce:**
[IComment](../../com.aspose.slides/icomment) - Commento aggiunto.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Aggiunge un nuovo commento moderno alla fine della raccolta.

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


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo semplice di un nuovo commento moderno. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva nella presentazione in cui aggiungere un nuovo commento moderno. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma sulla diapositiva a cui è associato un nuovo commento moderno. |
| position | java.awt.geom.Point2D.Float | Posizione sulla diapositiva in cui aggiungere un nuovo commento moderno. |
| creationTime | java.util.Date | Ora di creazione del commento moderno. |

**Restituisce:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Commento moderno aggiunto.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Inserisce un nuovo commento in una raccolta all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'elemento nella raccolta in cui inserire il commento. |
| text | java.lang.String | Testo semplice di un nuovo commento. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva nella presentazione in cui aggiungere un nuovo commento. |
| position | java.awt.geom.Point2D.Float | Posizione sulla diapositiva in cui aggiungere un nuovo commento. |
| creationTime | java.util.Date | Ora di creazione del commento. |

**Restituisce:**
[IComment](../../com.aspose.slides/icomment) - Commento inserito.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Inserisce un nuovo commento moderno in una raccolta all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'elemento nella raccolta in cui inserire il commento moderno. |
| text | java.lang.String | Testo semplice di un nuovo commento moderno. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva nella presentazione in cui aggiungere un nuovo commento moderno. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma sulla diapositiva a cui è associato un nuovo commento moderno. |
| position | java.awt.geom.Point2D.Float | Posizione sulla diapositiva in cui aggiungere un nuovo commento moderno. |
| creationTime | java.util.Date | Ora di creazione del commento moderno. |

**Restituisce:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Commento moderno inserito.
### toArray() {#toArray--}
```
public final IComment[] toArray()
```

Crea e restituisce un array con tutti i commenti.

**Restituisce:**
com.aspose.slides.IComment[] - Array di [Comment](../../com.aspose.slides/comment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

Crea e restituisce un array con tutti i commenti dell'intervallo specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | int | Indice del primo commento da restituire. |
| count | int | Numero di commenti da restituire. |

**Restituisce:**
com.aspose.slides.IComment[] - Array di [Comment](../../com.aspose.slides/comment).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove l'elemento all'indice specificato in una raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero dell'elemento da rimuovere. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

Rimuove la prima occorrenza del commento specificato in una raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Il commento da rimuovere dalla raccolta. |

### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti i commenti da una raccolta.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

Restituisce un enumeratore che itera attraverso la raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Un IGenericEnumerator che può essere usato per iterare attraverso la raccolta.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

Restituisce un iterator java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Un java.util.Iterator per l'intera raccolta.
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

Trova un commento nella raccolta per indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| idx | int | Indice unico di un commento da trovare  int . |

**Restituisce:**
[IComment](../../com.aspose.slides/icomment) - Commento trovato o null [IComment](../../com.aspose.slides/icomment).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia tutti gli elementi dalla raccolta nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| index | int | Indice di partenza nell'array di destinazione. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). Solo lettura  boolean .

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Restituisce una radice di sincronizzazione. Solo lettura  Object .

**Restituisce:**
java.lang.Object