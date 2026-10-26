---
title: PortionFactory
second_title: Aspose.Slides for Android via Java API 参考
description: 允许创建测试段落
type: docs
url: /zh/com.aspose.slides/portionfactory/
---
**继承：**
java.lang.Object

**所有已实现的接口：**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

允许创建测试段落

--------------------

用于 COM 兼容性
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createPortion()](#createPortion--) | 创建一个空文本段落。 |
| [createPortion(String str)](#createPortion-java.lang.String-) | 从指定字符串创建文本段落。 |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | 使用指定的段落数据创建段落。 |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


创建一个空文本段落。

**返回：**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


从指定字符串创建文本段落。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | java.lang.String | String. |

**返回：**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```


使用指定的段落数据创建段落。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | 要使用的段落。 |

**返回：**
[IPortion](../../com.aspose.slides/iportion) - Portion.