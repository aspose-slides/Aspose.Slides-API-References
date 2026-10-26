---
title: IMathBlockCollection
second_title: Aspose.Slides für Android über Java API Referenz
description: Sammlung von mathematischen Blöcken IMathBlock
type: docs
url: /de/com.aspose.slides/imathblockcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

Sammlung von mathematischen Blöcken (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Fügt IMathBlock am Ende der Sammlung hinzu. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | Fügt IMathBlock in die Sammlung an der angegebenen Position ein. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt ein Element an dem angegebenen Index der Sammlung. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Bestimmt, ob die Sammlung einen bestimmten Wert enthält. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Bestimmt den Index eines bestimmten IMathBlock in der Sammlung. |
| [getCount()](#getCount--) | Ermittelt die tatsächlich in der Sammlung enthaltene Elementanzahl. |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Gibt das Element am angegebenen Index zurück. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```


Fügt IMathBlock am Ende der Sammlung hinzu.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Ein mathematischer Block, der am Ende der Sammlung hinzugefügt wird |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```


Fügt IMathBlock in die Sammlung an der angegebenen Position ein.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem ein Element eingefügt werden soll. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Der IMathBlock, der eingefügt werden soll. |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```


Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Das zu entfernende Objekt aus der Sammlung. |

**Rückgabewert:**
boolean - true, wenn das Element erfolgreich aus der Sammlung entfernt wurde; andernfalls false. Diese Methode gibt ebenfalls false zurück, wenn das Element in der ursprünglichen Sammlung nicht gefunden wird.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Entfernt ein Element an dem angegebenen Index der Sammlung.

--------------------

> ```
> Beispiel:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```


Bestimmt, ob die Sammlung einen bestimmten Wert enthält.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Das zu findende Objekt in der Sammlung. |

**Rückgabewert:**
boolean - true, wenn das Element in der Sammlung gefunden wird; andernfalls false.
### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```


Bestimmt den Index eines bestimmten IMathBlock in der Sammlung.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Das Element, das in der Sammlung gesucht werden soll. |

**Rückgabewert:**
int - Der Index des Elements, falls es in der Sammlung gefunden wird; andernfalls -1.
### getCount() {#getCount--}
```
public abstract int getCount()
```


Ermittelt die tatsächlich in der Sammlung enthaltene Elementanzahl. Nur lesbarer int.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**Rückgabewert:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```


Gibt das Element am angegebenen Index zurück. Nur lesbarer [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Beispiel:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des abzurufenden Elements. |

**Rückgabewert:**
[IMathBlock](../../com.aspose.slides/imathblock) - Der Block eines mathematischen Textes.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```


Gibt das Element am angegebenen Index zurück. Nur lesbarer [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu setzenden Elements. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Der Block eines mathematischen Textes. |

### clear() {#clear--}
```
public abstract void clear()
```


Entfernt alle Elemente aus der Sammlung.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```