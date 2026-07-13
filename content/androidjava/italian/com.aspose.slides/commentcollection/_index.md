---
title: CommentCollection
second_title: Aspose.Slides per Android via Riferimento API Java
description: Rappresenta una collezione di commenti di un autore.
type: docs
url: /it/com.aspose.slides/commentcollection/
---
**Eredità:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

Rappresenta una collezione di commenti di un singolo autore.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Restituisce il numero di elementi effettivamente contenuti nella collezione. |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Aggiunge un nuovo commento alla fine della collezione. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Aggiunge un nuovo commento moderno alla fine della collezione. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Inserisce un nuovo commento in una collezione all'indice specificato. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Inserisce un nuovo commento moderno in una collezione all'indice specificato. |
| [toArray()](#toArray--) | Crea e restituisce un array con tutti i commenti. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crea e restituisce un array con tutti i commenti dell'intervallo specificato. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato in una collezione. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Rimuove la prima occorrenza del commento specificato in una collezione. |
| [clear()](#clear--) | Rimuove tutti i commenti da una collezione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Trova un commento nella collezione per indice. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi dalla collezione nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
### size() {#size--}
```
public final int size()
```

Restituisce il numero di elementi effettivamente contenuti nella collezione. Sola lettura  int .

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

Restituisce l'elemento all'indice specificato. Sola lettura [Comment](../../com.aspose.slides/comment).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

Aggiunge un nuovo commento alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo semplice di un nuovo commento. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva in una presentazione dove aggiungere un nuovo commento. |
| position | android.graphics.PointF | Posizione su una diapositiva dove aggiungere un nuovo commento. |
| creationTime | java.util.Date | Tempo di creazione di un commento. |

**Restituisce:**
[IComment](../../com.aspose.slides/icomment) - Commento aggiunto.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Aggiunge un nuovo commento moderno alla fine della collezione.

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


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo semplice di un nuovo commento moderno. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva in una presentazione dove aggiungere un nuovo commento moderno. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma su una diapositiva a cui è associato un nuovo commento moderno. |
| position | android.graphics.PointF | Posizione su una diapositiva dove aggiungere un nuovo commento moderno. |
| creationTime | java.util.Date | Tempo di creazione di un commento moderno. |

**Restituisce:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Commento moderno aggiunto.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

Inserisce un nuovo commento in una collezione all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'elemento in una collezione al quale il commento deve essere inserito. |
| text | java.lang.String | Testo semplice di un nuovo commento. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva in una presentazione dove aggiungere un nuovo commento. |
| position | android.graphics.PointF | Posizione su una diapositiva dove aggiungere un nuovo commento. |
| creationTime | java.util.Date | Tempo di creazione di un commento. |

**Restituisce:**
[IComment](../../com.aspose.slides/icomment) - Commento inserito.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Inserisce un nuovo commento moderno in una collezione all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'elemento in una collezione al quale il commento moderno deve essere inserito. |
| text | java.lang.String | Testo semplice di un nuovo commento moderno. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva in una presentazione dove aggiungere un nuovo commento moderno. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma su una diapositiva a cui è associato un nuovo commento moderno. |
| position | android.graphics.PointF | Posizione su una diapositiva dove aggiungere un nuovo commento moderno. |
| creationTime | java.util.Date | Tempo di creazione di un commento moderno. |

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

Rimuove l'elemento all'indice specificato in una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice basato su zero dell'elemento da rimuovere. |
### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

Rimuove la prima occorrenza del commento specificato in una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Il commento da rimuovere dalla collezione. |
### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti i commenti da una collezione.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - un java.util.Iterator per l'intera collezione.
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

Trova un commento nella collezione per indice.

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

Copia tutti gli elementi dalla collezione nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| index | int | Indice di partenza nell'array di destinazione. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). Sola lettura  boolean .

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Restituisce una radice di sincronizzazione. Sola lettura  Object .

**Restituisce:**
java.lang.Object