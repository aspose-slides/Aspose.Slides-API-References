---
title: ICommentCollection
second_title: Aspose.Slides pro Java API Reference
description: Representuje kolekci komentářů jednoho autora.
type: docs
url: /cs/com.aspose.slides/icommentcollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

Representuje kolekci komentářů jednoho autora.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Přidá nový komentář na konec kolekce. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Přidá nový moderní komentář na konec kolekce. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Vloží nový komentář do kolekce na zadaném indexu. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Vloží nový moderní komentář do kolekce na zadaném indexu. |
| [toArray()](#toArray--) | Vytvoří a vrátí pole se všemi komentáři. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Vytvoří a vrátí pole se všemi komentáři ze zadaného rozsahu. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu v kolekci. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Odstraní první výskyt zadaného komentáře v kolekci. |
| [clear()](#clear--) | Odstraní všechny komentáře z kolekce. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```

Získá prvek na zadaném indexu. Pouze pro čtení [IComment](../../com.aspose.slides/icomment).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Přidá nový komentář na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Plain text of a new comment. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide in a presentation where to add a new comment. |
| position | java.awt.geom.Point2D.Float | Position on a slide where to add a new comment. |
| creationTime | java.util.Date | Time of a comment creation. |

**Vrací:**
[IComment](../../com.aspose.slides/icomment) - Přidaný komentář.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Přidá nový moderní komentář na konec kolekce.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Plain text of a new modern comment. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide in a presentation where to add a new modern comment. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape on a slide to which a new modern comment is associated. |
| position | java.awt.geom.Point2D.Float | Position on a slide where to add a new modern comment. |
| creationTime | java.util.Date | Time of a modern comment creation. |

**Vrací:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Přidaný moderní komentář.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Vloží nový komentář do kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index of the element in a collection at which comment should be inserted. |
| text | java.lang.String | Plain text of a new comment. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide in a presentation where to add a new comment. |
| position | java.awt.geom.Point2D.Float | Position on a slide where to add a new comment. |
| creationTime | java.util.Date | Time of a comment creation. |

**Vrací:**
[IComment](../../com.aspose.slides/icomment) - Vložený komentář.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Vloží nový moderní komentář do kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index of the element in a collection at which modern comment should be inserted. |
| text | java.lang.String | Plain text of a new modern comment. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide in a presentation where to add a new modern comment. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape on a slide to which a new modern comment is associated. |
| position | java.awt.geom.Point2D.Float | Position on a slide where to add a new modern comment. |
| creationTime | java.util.Date | Time of a modern comment creation. |

**Vrací:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Vložený moderní komentář.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```

Vytvoří a vrátí pole se všemi komentáři.

**Vrací:**
com.aspose.slides.IComment[] - Pole [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```

Vytvoří a vrátí pole se všemi komentáři ze zadaného rozsahu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | int | An index of a first comment to return. |
| count | int | A number of comments to return. |

**Vrací:**
com.aspose.slides.IComment[] - Pole [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraní prvek na zadaném indexu v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

Odstraní první výskyt zadaného komentáře v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | The comment to remove from a collection. |

### clear() {#clear--}
```
public abstract void clear()
```

Odstraní všechny komentáře z kolekce.