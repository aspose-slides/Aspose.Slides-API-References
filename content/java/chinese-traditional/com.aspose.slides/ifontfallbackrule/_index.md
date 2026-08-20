---
title: IFontFallBackRule
second_title: Aspose.Slides for Java API Reference
description: 表示字體回退規則
type: docs
url: /zh-hant/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

表示字體回退規則
## 方法

| 方法 | 描述 |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | 將新字體（複數）加入回退字體清單。 |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | 將新字體加入回退字體清單。 |
| [getRangeStartIndex()](#getRangeStartIndex--) | 取得連續 Unicode 範圍的起始索引。 |
| [getRangeEndIndex()](#getRangeEndIndex--) | 取得連續 Unicode 範圍的結束索引。 |
| [getCount()](#getCount--) | 取得在該範圍內實際定義的字體數量。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的字體名稱。 |
| [clear()](#clear--) | 從清單中移除所有字體。 |
| [remove(String fontName)](#remove-java.lang.String-) | 從清單中移除特定回退字體的第一次出現。 |
| [removeAt(int index)](#removeAt-int-) | 從清單中移除指定索引處的回退字體。 |
| [toArray()](#toArray--) | 建立並返回包含此規則所有回退字體的陣列。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 建立並返回清單中指定範圍內所有回退字體的陣列。 |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | 返回集合中指定規則的索引。 |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

將新字體（複數）加入回退字體清單。

--------------------

> ```
> //建立 FantFallBackRule 的新實例
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //加入第二個字體到此規則 
>  newRule.addFallBackFonts("MS Gothic");
>  //加入第三與第四個字體到此規則 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | 用於回退的字體名稱或多個名稱（以逗號分隔） |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

將新字體加入回退字體清單。

--------------------

> ```
> //建立 FontFallBackRule 的新實例
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //為此規則加入另外三個字體 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontNames | java.lang.String[] | 用於回退的字體名稱或多個名稱（以逗號分隔） |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

取得連續 Unicode 範圍的起始索引。

**Returns:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

取得連續 Unicode 範圍的結束索引。

**Returns:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

取得在該範圍內實際定義的字體數量。

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

取得指定索引處的字體名稱。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```

從清單中移除所有字體。

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

從清單中移除特定回退字體的第一次出現。

--------------------

> ```
> // 建立一個包含字體清單的規則。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //從清單中移除 Tahoma。
>  newRule.remove("Tahoma");
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | 要從清單中移除的字體名稱。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

從清單中移除指定索引處的回退字體。

--------------------

> ```
> // 建立一個包含字體清單的規則。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 從清單中移除 Tahoma。
>  newRule.remove(2);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要移除的字體的零基索引。 |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

建立並返回包含此規則所有回退字體的陣列。

--------------------

> ```
> // 建立一個包含字體清單的規則。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 取得所有字體名稱作為陣列
>  String[] fontNames = newRule.toArray();
> ```


**Returns:**
java.lang.String[] - 陣列 of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

建立並返回清單中指定範圍內所有回退字體的陣列。

--------------------

> ```
> //建立一個包含字體清單的規則。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //取得最後兩個字體名稱作為陣列
>  String[] fontNames = newRule.toArray(2,2);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | 要新增的第一個字體的索引。 |
| count | int | 要新增的字體數量。 |

**Returns:**
java.lang.String[] - 陣列 of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

返回集合中指定規則的索引。

--------------------

> ```
> // 建立一個包含字體清單的規則。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //取得 Tahoma 的索引
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | 要查找的字體名稱。 |

**Returns:**
int - 字體的索引，若未在清單中找到則為 -1。