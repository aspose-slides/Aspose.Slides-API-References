---
title: Tab
second_title: Aspose.Slides for Java API 參考
description: 表示文字的定位點。
type: docs
url: /zh-hant/com.aspose.slides/tab/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有已實作的介面:**  
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

表示文字的定位點。

## 建構函式

| 建構式 | 說明 |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | 建立新的 Tab |

## 方法

| 方法 | 說明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | 傳回或設定 Tab 的位置。 |
| [setPosition(double value)](#setPosition-double-) | 傳回或設定 Tab 的位置。 |
| [getAlignment()](#getAlignment--) | 傳回或設定 Tab 的對齊樣式。 |
| [setAlignment(int value)](#setAlignment-int-) | 傳回或設定 Tab 的對齊樣式。 |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | 比較目前實例與相同類型的其他物件。 |

### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

建立新的 Tab

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| position | double | Tab 位置。 |
| align | int | 對齊方式。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**傳回值:**
long

### getPosition() {#getPosition--}
```
public final double getPosition()
```

傳回或設定 Tab 的位置。設定此屬性可能會變更 Tab 在集合中的索引並使列舉器失效。可讀寫 double。

**傳回值:**
double

### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

傳回或設定 Tab 的位置。設定此屬性可能會變更 Tab 在集合中的索引並使列舉器失效。可讀寫 double。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

傳回或設定 Tab 的對齊樣式。可讀寫 [TabAlignment](../../com.aspose.slides/tabalignment)。

**傳回值:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

傳回或設定 Tab 的對齊樣式。可讀寫 [TabAlignment](../../com.aspose.slides/tabalignment)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```

比較目前實例與相同類型的其他物件。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 用於與此實例比較的物件。 |

**傳回值:**
int - 一個 32 位元的整數，指示比較項目的相對順序。返回值具有以下含義：

 *  < 0 - 此實例小於 obj。
 *  = 0 - 此實例等於 obj。
 *  > 0 - 此實例大於 obj。