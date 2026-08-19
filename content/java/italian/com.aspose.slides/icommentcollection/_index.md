---
title: ICommentCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una raccolta di commenti di un singolo autore.
type: docs
url: /it/com.aspose.slides/icommentcollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

Rappresenta una raccolta di commenti di un singolo autore.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Aggiunge un nuovo commento alla fine di una raccolta. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Aggiunge un nuovo commento moderno alla fine di una raccolta. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Inserisce un nuovo commento in una raccolta all'indice specificato. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Inserisce un nuovo commento moderno in una raccolta all'indice specificato. |
| [toArray()](#toArray--) | Crea e restituisce un array con tutti i commenti. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crea e restituisce un array con tutti i commenti dell'intervallo specificato. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato in una raccolta. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Rimuove la prima occorrenza del commento specificato in una raccolta. |
| [clear()](#clear--) | Rimuove tutti i commenti da una raccolta. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```

Ottiene l'elemento all'indice specificato. Sola lettura [IComment](../../com.aspose.slides/icomment).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Aggiunge un nuovo commento alla fine di una raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo semplice di un nuovo commento. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva in una presentazione dove aggiungere un nuovo commento. |
| position | java.awt.geom.Point2D.Float | Posizione su una diapositiva dove aggiungere un nuovo commento. |
| creationTime | java.util.Date | Tempo di creazione del commento. |

**Restituisce:**
[IComment](../../com.aspose.slides/icomment) - Commento aggiunto.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Aggiunge un nuovo commento moderno alla fine di una raccolta.

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
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva in una presentazione dove aggiungere un nuovo commento moderno. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma su una diapositiva a cui è associato un nuovo commento moderno. |
| position | java.awt.geom.Point2D.Float | Posizione su una diapositiva dove aggiungere un nuovo commento moderno. |
| creationTime | java.util.Date | Tempo di creazione di un commento moderno. |

**Restituisce:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Commento moderno aggiunto.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Inserisce un nuovo commento in una raccolta all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'elemento in una raccolta a cui il commento deve essere inserito. |
| text | java.lang.String | Testo semplice di un nuovo commento. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva in una presentazione dove aggiungere un nuovo commento. |
| position | java.awt.geom.Point2D.Float | Posizione su una diapositiva dove aggiungere un nuovo commento. |
| creationTime | java.util.Date | Tempo di creazione del commento. |

**Restituisce:**
[IComment](../../com.aspose.slides/icomment) - Commento inserito.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Inserisce un nuovo commento moderno in una raccolta all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'elemento in una raccolta a cui il commento moderno deve essere inserito. |
| text | java.lang.String | Testo semplice di un nuovo commento moderno. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva in una presentazione dove aggiungere un nuovo commento moderno. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma su una diapositiva a cui è associato un nuovo commento moderno. |
| position | java.awt.geom.Point2D.Float | Posizione su una diapositiva dove aggiungere un nuovo commento moderno. |
| creationTime | java.util.Date | Tempo di creazione di un commento moderno. |

**Restituisce:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Commento moderno inserito.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```

Crea e restituisce un array con tutti i commenti.

**Restituisce:**
com.aspose.slides.IComment[] - Array di [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```

Crea e restituisce un array con tutti i commenti dell'intervallo specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | int | Indice del primo commento da restituire. |
| count | int | Numero di commenti da restituire. |

**Restituisce:**
com.aspose.slides.IComment[] - Array di [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove l'elemento all'indice specificato in una raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da rimuovere. |
### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

Rimuove la prima occorrenza del commento specificato in una raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Il commento da rimuovere da una raccolta. |
### clear() {#clear--}
```
public abstract void clear()
```

Rimuove tutti i commenti da una raccolta.