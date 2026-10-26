---
title: ITab
second_title: Aspose.Slides for Java API 參考
description: 表示文字的製表位。
type: docs
url: /zh-hant/com.aspose.slides/itab/
---
**All Implemented Interfaces:**
java.lang.Comparable
```
public interface ITab extends Comparable
```

表示文字的製表位。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getPosition()](#getPosition--) | 回傳或設定定位點的位置。 |
| [setPosition(double value)](#setPosition-double-) | 回傳或設定定位點的位置。 |
| [getAlignment()](#getAlignment--) | 回傳或設定定位點的對齊樣式。 |
| [setAlignment(int value)](#setAlignment-int-) | 回傳或設定定位點的對齊樣式。 |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```

回傳或設定定位點的位置。指派此屬性可能會變更定位點在集合中的索引，並使列舉器失效。讀寫 double.

**回傳：**
double
### setPosition(double value) {#setPosition-double-}
```
public abstract void setPosition(double value)
```

回傳或設定定位點的位置。指派此屬性可能會變更定位點在集合中的索引，並使列舉器失效。讀寫 double.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

回傳或設定定位點的對齊樣式。讀寫 [TabAlignment](../../com.aspose.slides/tabalignment)。

**回傳：**
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

回傳或設定定位點的對齊樣式。讀寫 [TabAlignment](../../com.aspose.slides/tabalignment)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |