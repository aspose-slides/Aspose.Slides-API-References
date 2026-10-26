---
title: IMasterTheme
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个主主题。
type: docs
url: /zh/com.aspose.slides/imastertheme/
---
**所有已实现的接口：**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

表示一个主主题。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | 返回附加配色方案的集合。 |
| [getName()](#getName--) | 返回主题的名称。 |
| [setName(String value)](#setName-java.lang.String-) | 返回主题的名称。 |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```

返回附加配色方案的集合。这些方案不影响演示文稿的外观，可被选为幻灯片的主配色方案。只读 [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**返回：**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```

返回主题的名称。可读写 String.

**返回：**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

返回主题的名称。可读写 String.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |