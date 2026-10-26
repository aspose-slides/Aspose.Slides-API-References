---
title: CommentCollection
second_title: Aspose.Slides pro Android prostřednictvím referenční příručky Java API
description: Představuje kolekci komentářů od jednoho autora.
type: docs
url: /cs/com.aspose.slides/commentcollection/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

Represents a collection of comments of one author.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Získá počet skutečně obsažených prvků v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Přidá nový komentář na konec kolekce. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Přidá nový moderní komentář na konec kolekce. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Vloží nový komentář do kolekce na zadaném indexu. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Vloží nový moderní komentář do kolekce na zadaném indexu. |
| [toArray()](#toArray--) | Vytvoří a vrátí pole se všemi komentáři. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Vytvoří a vrátí pole se všemi komentáři ze zadaného rozsahu. |
| [removeAt(int index)](#removeAt-int-) | Odebere prvek na zadaném indexu v kolekci. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Odebere první výskyt zadaného komentáře v kolekci. |
| [clear()](#clear--) | Odebere všechny komentáře z kolekce. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Najde komentář v kolekci podle indexu. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje všechny prvky z kolekce do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu indikující, zda je přístup ke kolekci synchronizovaný (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |

### size() {#size--}
```
public final int size()
```

Získá počet skutečně obsažených prvků v kolekci. Pouze pro čtení  int .

**Vrací:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

Získá prvek na zadaném indexu. Pouze pro čtení [Comment](../../com.aspose.slides/comment).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IComment](../../com.aspose.slides/icomment)

### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

Přidá nový komentář na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Prostý text nového komentáře. |
| slide | [ISlide](../../com.aspose.slides/islide) | Snímek v prezentaci, do kterého se má přidat nový komentář. |
| position | android.graphics.PointF | Pozice na snímku, kde se má přidat nový komentář. |
| creationTime | java.util.Date | Čas vytvoření komentáře. |

**Vrací:**
[IComment](../../com.aspose.slides/icomment) - Přidaný komentář.

### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
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

**Vrací:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Přidaný moderní komentář.

### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

Vloží nový komentář do kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index prvku v kolekci, na který má být komentář vložen. |
| text | java.lang.String | Prostý text nového komentáře. |
| slide | [ISlide](../../com.aspose.slides/islide) | Snímek v prezentaci, do kterého se má přidat nový komentář. |
| position | android.graphics.PointF | Pozice na snímku, kde se má přidat nový komentář. |
| creationTime | java.util.Date | Čas vytvoření komentáře. |

**Vrací:**
[IComment](../../com.aspose.slides/icomment) - Vložený komentář.

### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Vloží nový moderní komentář do kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index prvku v kolekci, na který má být moderní komentář vložen. |
| text | java.lang.String | Prostý text nového moderního komentáře. |
| slide | [ISlide](../../com.aspose.slides/islide) | Snímek v prezentaci, do kterého se má přidat nový moderní komentář. |
| shape | [IShape](../../com.aspose.slides/ishape) | Tvar na snímku, ke kterému je nový moderní komentář přiřazen. |
| position | android.graphics.PointF | Pozice na snímku, kde se má přidat nový moderní komentář. |
| creationTime | java.util.Date | Čas vytvoření moderního komentáře. |

**Vrací:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Vložený moderní komentář.

### toArray() {#toArray--}
```
public final IComment[] toArray()
```

Vytvoří a vrátí pole se všemi komentáři.

**Vrací:**
com.aspose.slides.IComment[] - Pole typu [Comment](../../com.aspose.slides/comment).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

Vytvoří a vrátí pole se všemi komentáři ze zadaného rozsahu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | int | Index prvního komentáře, který se má vrátit. |
| count | int | Počet komentářů, které se mají vrátit. |

**Vrací:**
com.aspose.slides.IComment[] - Pole typu [Comment](../../com.aspose.slides/comment).

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odebere prvek na zadaném indexu v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulovým indexem prvku, který se má odebrat. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

Odebere první výskyt zadaného komentáře v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Komentář, který se má odebrat z kolekce. |

### clear() {#clear--}
```
public final void clear()
```

Odebere všechny komentáře z kolekce.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - IGenericEnumerator, který lze použít k iteraci kolekcí.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - java.util.Iterator pro celou kolekci.

### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

Najde komentář v kolekci podle indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| idx | int | Jedinečný index komentáře, který se má najít  int . |

**Vrací:**
[IComment](../../com.aspose.slides/icomment) - Nalezený komentář nebo null [IComment](../../com.aspose.slides/icomment).

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Zkopíruje všechny prvky z kolekce do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu indikující, zda je přístup ke kolekci synchronizovaný (vláknově bezpečný). Pouze pro čtení  boolean .

**Vrací:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Pouze pro čtení  Object .

**Vrací:**
java.lang.Object