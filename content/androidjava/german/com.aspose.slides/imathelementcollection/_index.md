---
title: IMathElementCollection
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Stellt eine Sammlung mathematischer Elemente MathElement dar.
type: docs
url: /de/com.aspose.slides/imathelementcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

Stellt eine Sammlung mathematischer Elemente (MathElement) dar.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ruft das Element am angegebenen Index ab. |
| [getCount()](#getCount--) | Ruft die tatsächlich in der Sammlung enthaltene Anzahl von Elementen ab. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Fügt ein mathematisches Element am Ende der Sammlung hinzu. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Bestimmt den Index eines bestimmten mathematischen Elements in der Sammlung. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Fügt ein mathematisches Element an dem angegebenen Index in die Sammlung ein. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Bestimmt, ob die Sammlung einen bestimmten Wert enthält. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index der Sammlung. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Copy to specified array. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```

Ruft das Element am angegebenen Index ab. Nur lesbar [IMathElement](../../com.aspose.slides/imathelement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des abzurufenden Elements |

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Ruft die tatsächlich in der Sammlung enthaltene Anzahl von Elementen ab. Nur lesbar int.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**Rückgabewert:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```

Fügt ein mathematisches Element am Ende der Sammlung hinzu.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Das IMathElement, das am Ende der Sammlung hinzugefügt werden soll. |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```

Bestimmt den Index eines bestimmten mathematischen Elements in der Sammlung.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = collection.indexOf(plusElement);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Das zu lokalisierende Element in der Sammlung. |

**Rückgabewert:**
int – Der Index des Elements, falls es in der Sammlung gefunden wird; andernfalls -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```

Fügt ein mathematisches Element an dem angegebenen Index in die Sammlung ein.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem das IMathElement eingefügt werden soll. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Das einzufügende IMathElement. |

### clear() {#clear--}
```
public abstract void clear()
```

Entfernt alle Elemente aus der Sammlung.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public abstract boolean contains(IMathElement item)
```

Bestimmt, ob die Sammlung einen bestimmten Wert enthält.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  bool contains = collection.contains(plusElement);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Das zu lokalisierende Objekt in der Sammlung. |

**Rückgabewert:**
boolean – true, wenn das Objekt in der Sammlung gefunden wird; andernfalls false.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```

Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.remove(plusElement);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Das zu entfernende Objekt aus der Sammlung. |

**Rückgabewert:**
boolean – true, wenn das Objekt erfolgreich aus der Sammlung entfernt wurde; andernfalls false. Diese Methode gibt ebenfalls false zurück, wenn das Objekt in der ursprünglichen Sammlung nicht gefunden wurde.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Entfernt das Element am angegebenen Index der Sammlung.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.removeAt(2);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```

Kopiert in das angegebene Array.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[collection.Count];
>  collection.copyTo(destinationArray, 0);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Array, in das kopiert werden soll. |
| arrayIndex | int | Index, ab dem das Kopieren beginnen soll. |