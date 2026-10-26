---
title: ITabCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling tabs voor.
type: docs
url: /nl/com.aspose.slides/itabcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Stelt een verzameling tabs voor.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [add(double position, int align)](#add-double-int-) | Adds a Tab to the collection. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Adds a Tab to the collection. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```


Gets the element at the specified index. Alleen-lezen [ITab](../../com.aspose.slides/itab).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```


Adds a Tab to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | double | Tab position. |
| align | int | Tab alignment. |

**Returns:**
[ITab](../../com.aspose.slides/itab) - Toegevoegde tab.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```


Adds a Tab to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Het Tab-object dat aan het einde van de verzameling moet worden toegevoegd. |

**Returns:**
int - De index waarop de tab is toegevoegd.
### clear() {#clear--}
```
public abstract void clear()
```


Removes all elements from the collection.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the element at the specified index of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het te verwijderen element. |