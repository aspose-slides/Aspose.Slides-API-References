---
title: ITab
second_title: Aspose.Slides 適用於 Android 的 Java API 參考
description: 表示文字的定位點。
type: docs
url: /zh-hant/com.aspose.slides/itab/
---
**所有已實作的介面：**
java.lang.Comparable
```
public interface ITab extends Comparable
```

表示文字的定位點。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getPosition()](#getPosition--) | 取得或設定定位點的位置。 |
| [setPosition(double value)](#setPosition-double-) | 取得或設定定位點的位置。 |
| [getAlignment()](#getAlignment--) | 取得或設定定位點的對齊樣式。 |
| [setAlignment(int value)](#setAlignment-int-) | 取得或設定定位點的對齊樣式。 |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```


取得或設定定位點的位置。指派此屬性可能會變更集合中定位點的索引，並使Enumerator失效。可讀寫 double。

**傳回：**
double
### setPosition(double value) {#setPosition-double-}
```
public abstract void setPosition(double value)
```


取得或設定定位點的位置。指派此屬性可能會變更集合中定位點的索引，並使Enumerator失效。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


取得或設定定位點的對齊樣式。可讀寫 [TabAlignment](../../com.aspose.slides/tabalignment)。

**傳回：**
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```


取得或設定定位點的對齊樣式。可讀寫 [TabAlignment](../../com.aspose.slides/tabalignment)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |