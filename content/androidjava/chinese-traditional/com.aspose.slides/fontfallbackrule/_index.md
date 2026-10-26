---
title: FontFallBackRule
second_title: Aspose.Slides for Android via Java API 參考
description: 表示字型回退規則
type: docs
url: /zh-hant/com.aspose.slides/fontfallbackrule/
---
**繼承:**  
java.lang.Object

**已實作介面:**  
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)  
```
public class FontFallBackRule implements IFontFallBackRule
```

表示字型回退規則

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | 建立新實例。 |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | 建立新實例。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | 將新的字型加入回退字型清單。 |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | 將新的字型加入回退字型清單。 |
| [getRangeStartIndex()](#getRangeStartIndex--) | 取得連續 Unicode 範圍的起始索引。 |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | 取得連續 Unicode 範圍的起始索引。 |
| [getRangeEndIndex()](#getRangeEndIndex--) | 取得連續 Unicode 範圍的結束索引。 |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | 取得連續 Unicode 範圍的結束索引。 |
| [getCount()](#getCount--) | 取得範圍內實際定義的字型數量。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的字型名稱。 |
| [clear()](#clear--) | 從清單中移除所有字型。 |
| [remove(String fontName)](#remove-java.lang.String-) | 從清單中移除特定回退字型的第一個出現項目。 |
| [removeAt(int index)](#removeAt-int-) | 從清單中移除指定索引處的回退字型。 |
| [toArray()](#toArray--) | 建立並傳回此規則的所有回退字型陣列。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 建立並傳回清單中指定範圍的所有回退字型陣列。 |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | 傳回集合中指定規則的索引。 |

### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```

建立新實例。

--------------------

> ```
> // 建立 FantFallBackRule 的新實例，使用一個字型。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // 建立 FantFallBackRule 的新實例，使用多個字型。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| startIndex | long | Unicode 範圍的起始索引 |
| endIndex | long | Unicode 範圍的結束索引 |
| fontNames | java.lang.String | 回退字型的名稱或多個名稱（以逗號分隔） |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```

建立新實例。

--------------------

> ```
> // 建立 FantFallBackRule 的新實例，使用兩個字型
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // 建立 FantFallBackRule 的新實例，使用多個字型。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| startIndex | long | Unicode 範圍的起始索引 |
| endIndex | long | Unicode 範圍的結束索引 |
| fontNames | java.lang.String[] | 回退字型的名稱或多個名稱（以逗號分隔） |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```

將新的字型加入回退字型清單。

--------------------

> ```
> // 建立 FontFallBackRule 的新實例
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //將第二個字型加入規則 
>  newRule.addFallBackFonts("MS Gothic");
>  //將第三與第四個字型加入規則 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| fontName | java.lang.String | 回退字型的名稱或多個名稱（以逗號分隔） |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```

將新的字型加入回退字型清單。

--------------------

> ```
> //建立 FontFallBackRule 的新實例
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //將另外三個字型加入規則 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| fontNames | java.lang.String[] | 回退字型的名稱或多個名稱（以逗號分隔） |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```

取得連續 Unicode 範圍的起始索引。

**返回值:**
long

### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```

取得連續 Unicode 範圍的起始索引。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```

取得連續 Unicode 範圍的結束索引。

**返回值:**
long

### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```

取得連續 Unicode 範圍的結束索引。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```

取得範圍內實際定義的字型數量。唯讀 int。

**返回值:**
int

### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```

取得指定索引處的字型名稱。唯讀 [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回值:**
java.lang.String

### clear() {#clear--}
```
public final void clear()
```

從清單中移除所有字型。

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```

從清單中移除特定回退字型的第一個出現項目。

--------------------

> ```
> // 建立包含字型清單的規則。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 從清單中移除 Tahoma。
>  newRule.remove("Tahoma");
> ```

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| fontName | java.lang.String | 要從清單中移除的字型名稱。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

從清單中移除指定索引處的回退字型。

--------------------

> ```
> // 建立包含字型清單的規則。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //從清單中移除 Tahoma。
>  newRule.remove(2);
> ```

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 要移除的字型的零基索引。 |

### toArray() {#toArray--}
```
public final String[] toArray()
```

建立並傳回此規則的所有回退字型陣列。

--------------------

> ```
> // 建立包含字型清單的規則。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 取得所有字型名稱作為陣列。
>  String[] fontNames = newRule.toArray();
> ```

**返回值:**
java.lang.String[] - 字串陣列

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```

建立並傳回清單中指定範圍的所有回退字型陣列。

```
// 建立包含字型清單的規則。
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // 取得最後兩個字型名稱作為陣列。
 String[] fontNames = newRule.toArray(2, 2);
```

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| startIndex | int | 要加入的第一個字型的索引。 |
| count | int | 要加入的字型數量。 |

**返回值:**
java.lang.String[] - 字串陣列

### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```

傳回集合中指定規則的索引。

--------------------

> ```
> // 建立包含字型清單的規則。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Minjo, MS Gothic, Tahoma, Times New Roman");
>  // 取得 Tahoma 的索引。
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| fontName | java.lang.String | 要查找的字型名稱。 |

**返回值:**
int - 字型的索引，若清單中未找到則為 -1