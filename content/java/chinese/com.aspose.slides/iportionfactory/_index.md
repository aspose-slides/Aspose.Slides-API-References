---
title: IPortionFactory
second_title: Aspose.Slides for Java API Reference
description: 允许创建测试部分
type: docs
url: /zh/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

允许创建测试部分

--------------------

用于 COM 兼容性
## Methods

| Method | Description |
| --- | --- |
| [createPortion()](#createPortion--) | 创建一个空的文本部分。 |
| [createPortion(String str)](#createPortion-java.lang.String-) | 从指定字符串创建文本部分。 |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | 使用指定的部分数据创建部分。 |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```

创建一个空的文本部分。

**Returns:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```

从指定字符串创建文本部分。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String | String. |

**Returns:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```

使用指定的部分数据创建部分。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | A portion to use. |

**Returns:**
[IPortion](../../com.aspose.slides/iportion) - Portion.