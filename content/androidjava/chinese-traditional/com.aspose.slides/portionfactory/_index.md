---
title: PortionFactory
second_title: Aspose.Slides for Android 之 Java API 參考
description: 允許建立測試段落
type: docs
url: /zh-hant/com.aspose.slides/portionfactory/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

允許建立測試段落

--------------------

用於 COM 相容性
## 建構子

| 建構函式 | 說明 |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [createPortion()](#createPortion--) | 建立空的文字 portion。 |
| [createPortion(String str)](#createPortion-java.lang.String-) | 從指定的字串建立文字 portion。 |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | 使用指定的 portion 資料建立 portion。 |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


建立空的文字 portion。

**返回：**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


從指定的字串建立文字 portion。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| str | java.lang.String | String. |

**返回：**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```


使用指定的 portion 資料建立 portion。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | 要使用的 portion。 |

**返回：**
[IPortion](../../com.aspose.slides/iportion) - Portion.