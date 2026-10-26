---
title: ICommentAuthorCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API
description: Reprezentuje kolekci autorů komentářů.
type: docs
url: /cs/com.aspose.slides/icommentauthorcollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

Reprezentuje kolekci autorů komentářů.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na určeném indexu. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Přidá nového autora na konec kolekce. |
| [toArray()](#toArray--) | Vytvoří a vrátí pole se všemi autory. |
| [findByName(String name)](#findByName-java.lang.String-) | Najde autora v kolekci podle jména. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Najde autora v kolekci podle jména a iniciál. |
| [removeAt(int index)](#removeAt-int-) | Odstraní autora na určeném indexu v kolekci. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Odstraní první výskyt daného autora v kolekci. |
| [clear()](#clear--) | Odstraní všechny autory z kolekce. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```


Získá prvek na určeném indexu. Pouze ke čtení [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```


Přidá nového autora na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Jméno nového autora. |
| initials | java.lang.String | Iniciály nového autora. |

**Návratová hodnota:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Nový [ICommentAuthor](../../com.aspose.slides/icommentauthor) objekt.
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```


Vytvoří a vrátí pole se všemi autory.

**Návratová hodnota:**
com.aspose.slides.ICommentAuthor[] - Pole [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```


Najde autora v kolekci podle jména.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Jméno autora, kterého hledáte. |

**Návratová hodnota:**
com.aspose.slides.ICommentAuthor[] - Autor nebo null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


Najde autora v kolekci podle jména a iniciál.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Jméno autora, kterého hledáte. |
| initials | java.lang.String | Iniciály autora, kterého hledáte. |

**Návratová hodnota:**
com.aspose.slides.ICommentAuthor[] - Autor nebo null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Odstraní autora na určeném indexu v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index prvku, který má být odstraněn. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```


Odstraní první výskyt daného autora v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Autor, který má být odstraněn z kolekce. |

### clear() {#clear--}
```
public abstract void clear()
```


Odstraní všechny autory z kolekce.