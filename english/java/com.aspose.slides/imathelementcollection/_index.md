---
title: IMathElementCollection
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents a collection of mathematical elements MathElement.
type: docs
weight: 893
url: /java/com.aspose.slides/imathelementcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

Represents a collection of mathematical elements (MathElement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Adds a math element to the end of the collection. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Determines the index of a specific math element in collection. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Inserts a math element into the collection at the specified index. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Determines whether the collection contains a specific value. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Removes the first occurrence of a specific object from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Copy to specified array. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```


Gets the element at the specified index. Read-only [IMathElement](../../com.aspose.slides/imathelement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the item to get |

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Gets the number of elements actually contained in the collection. Read-only int.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**Returns:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```


Adds a math element to the end of the collection.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | The IMathElement to be added to the end of the collection. |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```


Determines the index of a specific math element in collection.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | The element to locate in the collection. |

**Returns:**
int - The index of item if found in the collection; otherwise, -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```


Inserts a math element into the collection at the specified index.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which IMathElement should be inserted. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | The IMathElement to insert. |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all elements from the collection.

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


Determines whether the collection contains a specific value.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | The object to locate in the collection. |

**Returns:**
boolean - true if item is found in the collection; otherwise, false.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```


Removes the first occurrence of a specific object from the collection.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | The object to remove from the collection. |

**Returns:**
boolean - true if item was successfully removed from the collection; otherwise, false. This method also returns false if item is not found in the original collection.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the element at the specified index of the collection.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```


Copy to specified array.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.slides.IMathElement[] | Array to copy to. |
| arrayIndex | int | Index to begin copying. |

