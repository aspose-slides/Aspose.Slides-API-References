---
title: IMathElementCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示一個數學元素 MathElement 的集合。
type: docs
url: /zh-hant/com.aspose.slides/imathelementcollection/
---
**所有實作的介面：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

表示一個數學元素 (MathElement) 的集合。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [getCount()](#getCount--) | 取得集合中實際包含的元素數量。 |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | 在集合的末端新增一個數學元素。 |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | 判斷特定數學元素在集合中的索引。 |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | 在指定索引處將數學元素插入集合。 |
| [clear()](#clear--) | 從集合中移除所有元素。 |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | 判斷集合是否包含特定值。 |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | 從集合中移除特定物件的第一個出現。 |
| [removeAt(int index)](#removeAt-int-) | 從集合中移除指定索引處的元素。 |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | 複製至指定的陣列。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```


取得指定索引處的元素。唯讀 [IMathElement](../../com.aspose.slides/imathelement)。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 要取得之項目的零基索引 |

**傳回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```


取得集合中實際包含的元素數量。唯讀 int。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**傳回值：**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```


在集合的末端新增一個數學元素。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要新增至集合末端的 IMathElement。 |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```


判斷特定數學元素在集合中的索引。

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

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要在集合中定位的元素。 |

**傳回值：**
int - 若在集合中找到項目，則回傳其索引；否則回傳 -1。
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```


在指定索引處將數學元素插入集合。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 要插入 IMathElement 的零基索引。 |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要插入的 IMathElement。 |

### clear() {#clear--}
```
public abstract void clear()
```


從集合中移除所有元素。

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


判斷集合是否包含特定值。

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

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要在集合中定位的物件。 |

**傳回值：**
boolean - 若在集合中找到項目則回傳 true；否則回傳 false。
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```


從集合中移除特定物件的第一個出現。

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

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要從集合中移除的物件。 |

**傳回值：**
boolean - 若成功從集合中移除項目則回傳 true；否則回傳 false。如果原始集合中未找到項目，亦回傳 false。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


從集合中移除指定索引處的元素。

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

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 要移除之元素的零基索引 |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```


複製至指定的陣列。

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

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | 要複製至的陣列。 |
| arrayIndex | int | 開始複製的索引。 |