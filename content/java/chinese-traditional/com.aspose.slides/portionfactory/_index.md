---
title: PortionFactory
second_title: Aspose.Slides for Java API 參考
description: 允許建立測試段落
type: docs
url: /zh-hant/com.aspose.slides/portionfactory/
---
**繼承:**  
java.lang.Object

**所有實作的介面:**  
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)  
```
public class PortionFactory implements IPortionFactory
```

允許建立測試段落

--------------------

用於 COM 相容性
## 建構函式

| 建構函式 | 描述 |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createPortion()](#createPortion--) | Creates an empty text portion. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Creates a text portion from specified string. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Creates a portion with the using of a specified portion data. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```

### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```

建立一個空的文字段落。

**回傳:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```

從指定的字串建立文字段落。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| str | java.lang.String | String. |

**回傳:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```

使用指定的段落資料建立段落。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | 要使用的段落。 |

**回傳:**
[IPortion](../../com.aspose.slides/iportion) - Portion.