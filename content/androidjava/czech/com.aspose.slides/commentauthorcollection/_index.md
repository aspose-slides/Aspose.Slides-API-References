---
title: CommentAuthorCollection
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje kolekci autorů komentářů.
type: docs
url: /cs/com.aspose.slides/commentauthorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

Representuje kolekci autorů komentářů.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Získá počet prvků skutečně obsažených v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Přidá nového autora na konec kolekce. |
| [toArray()](#toArray--) | Vytvoří a vrátí pole se všemi autory. |
| [findByName(String name)](#findByName-java.lang.String-) | Najde autora v kolekci podle jména. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Najde autora v kolekci podle jména a iniciál. |
| [removeAt(int index)](#removeAt-int-) | Odstraní autora na zadaném indexu kolekce. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Odstraní první výskyt zadaného autora v kolekci. |
| [clear()](#clear--) | Odstraní všechny autory z kolekce. |
| [iterator()](#iterator--) | Vrátí enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrátí java iterátor pro celou kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje všechny prvky z kolekce do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrátí hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrátí kořen synchronizace. |
### size() {#size--}
```
public final int size()
```

Získá počet prvků skutečně obsažených v kolekci. Pouze ke čtení int.

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```

Získá prvek na zadaném indexu. Pouze ke čtení [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```

Přidá nového autora na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Jméno nového autora. |
| initials | java.lang.String | Iniciály nového autora. |

**Vrací:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Nový [ICommentAuthor](../../com.aspose.slides/icommentauthor) objekt.
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```

Vytvoří a vrátí pole se všemi autory.

**Vrací:**
com.aspose.slides.ICommentAuthor[] - Pole typu [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```

Najde autora v kolekci podle jména.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Jméno autora, který se má najít. |

**Vrací:**
com.aspose.slides.ICommentAuthor[] - Autor nebo null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

Najde autora v kolekci podle jména a iniciál.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Jméno autora, který se má najít. |
| initials | java.lang.String | Iniciály autora, který se má najít. |

**Vrací:**
com.aspose.slides.ICommentAuthor[] - Autor nebo null.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odstraní autora na zadaném indexu kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index prvku, který se má odstranit. |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```

Odstraní první výskyt zadaného autora v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Autor, který se má odstranit z kolekce. |
### clear() {#clear--}
```
public final void clear()
```

Odstraní všechny autory z kolekce.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```

Vrátí enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - IGenericEnumerator, který může být použit k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```

Vrátí java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - java.util.Iterator pro celou kolekci.
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

Vrátí hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze ke čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrátí kořen synchronizace. Pouze ke čtení Object.

**Vrací:**
java.lang.Object