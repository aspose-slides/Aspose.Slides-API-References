---
title: IPortionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: 允许创建测试 Portion
type: docs
url: /zh/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

允许创建测试 Portion

--------------------

用于 COM 兼容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createPortion()](#createPortion--) | 创建一个空的文本 Portion。 |
| [createPortion(String str)](#createPortion-java.lang.String-) | 从指定字符串创建文本 Portion。 |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | 使用指定的 portion 数据创建 Portion。 |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


创建一个空的文本 Portion。

**返回值：**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```


从指定字符串创建文本 Portion。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | java.lang.String | 字符串。 |

**返回值：**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```


使用指定的 portion 数据创建 Portion。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | 要使用的 Portion。 |

**返回值：**
[IPortion](../../com.aspose.slides/iportion) - Portion.