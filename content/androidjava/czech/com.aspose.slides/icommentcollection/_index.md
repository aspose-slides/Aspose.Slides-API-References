---
title: ICommentCollection
second_title: Aspose.Slides pro Android – referenční příručka Java API
description: Představuje kolekci komentářů jednoho autora.
type: docs
url: /cs/com.aspose.slides/icommentcollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

Představuje kolekci komentářů jednoho autora.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Přidá nový komentář na konec kolekce. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Přidá nový moderní komentář na konec kolekce. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Vloží nový komentář do kolekce na zadaném indexu. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Vloží nový moderní komentář do kolekce na zadaném indexu. |
| [toArray()](#toArray--) | Vytvoří a vrátí pole se všemi komentáři. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Vytvoří a vrátí pole se všemi komentáři ze zadaného rozsahu. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu v kolekci. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Odstraní první výskyt zadaného komentáře v kolekci. |
| [clear()](#clear--) | Odstraní všechny komentáře z kolekce. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```

Získá prvek na zadaném indexu. Pouze ke čtení [IComment](../../com.aspose.slides/icomment).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

Přidá nový komentář na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Prostý text nového komentáře. |
| slide | [ISlide](../../com.aspose.slides/islide) | Snímek v prezentaci, do kterého se má přidat nový komentář. |
| position | android.graphics.PointF | Pozice na snímku, kde se má přidat nový komentář. |
| creationTime | java.util.Date | Čas vytvoření komentáře. |

**Návratová hodnota:**
[IComment](../../com.aspose.slides/icomment) - Přidaný komentář.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Přidá nový moderní komentář na konec kolekce.

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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Prostý text nového moderního komentáře. |
| slide | [ISlide](../../com.aspose.slides/islide) | Snímek v prezentaci, do kterého se má přidat nový moderní komentář. |
| shape | [IShape](../../com.aspose.slides/ishape) | Tvar na snímku, ke kterému je nový moderní komentář přiřazen. |
| position | android.graphics.PointF | Pozice na snímku, kde se má přidat nový moderní komentář. |
| creationTime | java.util.Date | Čas vytvoření moderního komentáře. |

**Návratová hodnota:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Přidaný moderní komentář.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

Vloží nový komentář do kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index prvku v kolekci, do kterého má být komentář vložen. |
| text | java.lang.String | Prostý text nového komentáře. |
| slide | [ISlide](../../com.aspose.slides/islide) | Snímek v prezentaci, do kterého se má přidat nový komentář. |
| position | android.graphics.PointF | Pozice na snímku, kde se má přidat nový komentář. |
| creationTime | java.util.Date | Čas vytvoření komentáře. |

**Návratová hodnota:**
[IComment](../../com.aspose.slides/icomment) - Vložený komentář.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Vloží nový moderní komentář do kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index prvku v kolekci, do kterého má být moderní komentář vložen. |
| text | java.lang.String | Prostý text nového moderního komentáře. |
| slide | [ISlide](../../com.aspose.slides/islide) | Snímek v prezentaci, do kterého se má přidat nový moderní komentář. |
| shape | [IShape](../../com.aspose.slides/ishape) | Tvar na snímku, ke kterému je nový moderní komentář přiřazen. |
| position | android.graphics.PointF | Pozice na snímku, kde se má přidat nový moderní komentář. |
| creationTime | java.util.Date | Čas vytvoření moderního komentáře. |

**Návratová hodnota:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Vložený moderní komentář.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```

Vytvoří a vrátí pole se všemi komentáři.

**Návratová hodnota:**
com.aspose.slides.IComment[] - Pole typu [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```

Vytvoří a vrátí pole se všemi komentáři ze zadaného rozsahu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | int | Index prvního komentáře, který se má vrátit. |
| count | int | Počet komentářů k vrácení. |

**Návratová hodnota:**
com.aspose.slides.IComment[] - Pole typu [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraní prvek na zadaném indexu v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index prvku, který se má odstranit. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

Odstraní první výskyt zadaného komentáře v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Komentář, který se má odstranit z kolekce. |

### clear() {#clear--}
```
public abstract void clear()
```

Odstraní všechny komentáře z kolekce.