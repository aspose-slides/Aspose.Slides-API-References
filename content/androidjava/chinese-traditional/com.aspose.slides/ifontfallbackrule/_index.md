---
title: IFontFallBackRule
second_title: Aspose.Slides for Android via Java API 參考
description: 表示字體回退規則
type: docs
url: /zh-hant/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

表示字體回退規則
## 方法

| 方法 | 說明 |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | 將新字體（複數）新增至回退字體清單。 |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | 將新字體新增至回退字體清單。 |
| [getRangeStartIndex()](#getRangeStartIndex--) | 取得連續 Unicode 範圍的起始索引。 |
| [getRangeEndIndex()](#getRangeEndIndex--) | 取得連續 Unicode 範圍的結束索引。 |
| [getCount()](#getCount--) | 取得此範圍實際定義的字體數量。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的字體名稱。 |
| [clear()](#clear--) | 移除清單中的所有字體。 |
| [remove(String fontName)](#remove-java.lang.String-) | 移除清單中第一個出現的特定回退字體。 |
| [removeAt(int index)](#removeAt-int-) | 移除清單中指定索引處的回退字體。 |
| [toArray()](#toArray--) | 建立並回傳此規則的所有回退字體陣列。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 建立並回傳清單中指定範圍的所有回退字體陣列。 |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | 回傳此規則在集合中的索引。 |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

將新字體（複數）新增至回退字體清單。

--------------------

> ```
> //建立 FantFallBackRule 的新實例
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //將第二個字體加入規則
>  newRule.addFallBackFonts("MS Gothic");
>  //將第三和第四個字體加入規則
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| fontName | java.lang.String | 回退字體的名稱或多個名稱（以逗號分隔） |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

將新字體新增至回退字體清單。

--------------------

> ```
> //建立 FontFallBackRule 的新實例
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //將另外三個字體加入規則 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| fontNames | java.lang.String[] | 回退字體的名稱或多個名稱（以逗號分隔） |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

取得連續 Unicode 範圍的起始索引。

**返回值:**
long

### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

取得連續 Unicode 範圍的結束索引。

**返回值:**
long

### getCount() {#getCount--}
```
public abstract int getCount()
```

取得此範圍實際定義的字體數量。

**返回值:**
int

### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

取得指定索引處的字體名稱。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回值:**
java.lang.String

### clear() {#clear--}
```
public abstract void clear()
```

移除清單中的所有字體。

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

移除清單中第一個出現的特定回退字體。

--------------------

> ```
> // 建立包含字體清單的規則。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 從清單中移除 Tahoma
>  newRule.remove("Tahoma");
> ```


**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| fontName | java.lang.String | 要從清單移除的字體名稱。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除清單中指定索引處的回退字體。

--------------------

> ```
> // 建立包含字體清單的規則。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 從清單中移除 Tahoma
>  newRule.remove(2);
> ```


**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 要移除的字體之零基索引。 |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

建立並回傳此規則的所有回退字體陣列。

--------------------

> ```
> // 建立包含字體清單的規則。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincha, MS Gothic, Tahoma, Times New Roman");
>  // 取得所有字體名稱作為陣列
>  String[] fontNames = newRule.toArray();
> ```


**返回值:**
java.lang.String[] - 字串陣列

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

建立並回傳清單中指定範圍的所有回退字體陣列。

--------------------

> ```
> // 建立包含字體清單的規則。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //取得最後兩個字體名稱作為陣列
>  String[] fontNames = newRule.toArray(2,2);
> ```


**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| startIndex | int | 要加入的第一個字體之索引。 |
| count | int | 要加入的字體數量。 |

**返回值:**
java.lang.String[] - 字串陣列

### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

回傳指定規則在集合中的索引。

--------------------

> ```
> // 建立包含字體清單的規則。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //取得 Tahoma 的索引
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| fontName | java.lang.String | 要查找的字體名稱。 |

**返回值:**
int - 字體的索引，若未在清單中找到則返回 -1。