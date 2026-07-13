---
title: ICommentCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una collezione di commenti di un autore.
type: docs
url: /it/com.aspose.slides/icommentcollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

Rappresenta una collezione di commenti di un autore.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Aggiunge un nuovo commento alla fine di una collezione. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Aggiunge un nuovo commento moderno alla fine di una collezione. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Inserisce un nuovo commento in una collezione all'indice specificato. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Inserisce un nuovo commento moderno in una collezione all'indice specificato. |
| [toArray()](#toArray--) | Crea e restituisce un array con tutti i commenti. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crea e restituisce un array con tutti i commenti dall'intervallo specificato. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato in una collezione. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Rimuove la prima occorrenza del commento specificato in una collezione. |
| [clear()](#clear--) | Rimuove tutti i commenti da una collezione. |
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
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

Aggiunge un nuovo commento alla fine di una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo semplice di un nuovo commento. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva in una presentazione in cui aggiungere un nuovo commento. |
| position | android.graphics.PointF | Posizione su una diapositiva in cui aggiungere un nuovo commento. |
| creationTime | java.util.Date | Ora di creazione del commento. |

**Restituisce:**
[IComment](../../com.aspose.slides/icomment) - Commento aggiunto.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Aggiunge un nuovo commento moderno alla fine di una collezione.

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
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva in una presentazione in cui aggiungere un nuovo commento moderno. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma su una diapositiva a cui è associato un nuovo commento moderno. |
| position | android.graphics.PointF | Posizione su una diapositiva in cui aggiungere un nuovo commento moderno. |
| creationTime | java.util.Date | Ora di creazione del commento moderno. |

**Restituisce:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Commento moderno aggiunto.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

Inserisce un nuovo commento in una collezione all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'elemento in una collezione in cui il commento dovrebbe essere inserito. |
| text | java.lang.String | Testo semplice di un nuovo commento. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva in una presentazione in cui aggiungere un nuovo commento. |
| position | android.graphics.PointF | Posizione su una diapositiva in cui aggiungere un nuovo commento. |
| creationTime | java.util.Date | Ora di creazione del commento. |

**Restituisce:**
[IComment](../../com.aspose.slides/icomment) - Commento inserito.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Inserisce un nuovo commento moderno in una collezione all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'elemento in una collezione in cui il commento moderno dovrebbe essere inserito. |
| text | java.lang.String | Testo semplice di un nuovo commento moderno. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva in una presentazione in cui aggiungere un nuovo commento moderno. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma su una diapositiva a cui è associato un nuovo commento moderno. |
| position | android.graphics.PointF | Posizione su una diapositiva in cui aggiungere un nuovo commento moderno. |
| creationTime | java.util.Date | Ora di creazione del commento moderno. |

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

Crea e restituisce un array con tutti i commenti dall'intervallo specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | int | Un indice del primo commento da restituire. |
| count | int | Un numero di commenti da restituire. |

**Restituisce:**
com.aspose.slides.IComment[] - Array di [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove l'elemento all'indice specificato in una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da rimuovere. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

Rimuove la prima occorrenza del commento specificato in una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Il commento da rimuovere da una collezione. |

### clear() {#clear--}
```
public abstract void clear()
```

Rimuove tutti i commenti da una collezione.