---
title: IPortionFactory
second_title: Aspose.Slides for Java API 參考
description: 允許建立測試段落
type: docs
url: /zh-hant/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

允許建立測試段落

--------------------

用於 COM 相容性
## 方法

| 方法 | 說明 |
| --- | --- |
| [createPortion()](#createPortion--) | 建立一個空的文字段落。 |
| [createPortion(String str)](#createPortion-java.lang.String-) | 從指定的字串建立文字段落。 |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | 使用指定的段落資料建立段落。 |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```

建立一個空的文字段落。

**傳回:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```

從指定的字串建立文字段落。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | java.lang.String | String. |

**傳回:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```

使用指定的段落資料建立段落。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | 要使用的段落。 |

**傳回:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.