---
title: FontScheme
second_title: Aspose.Slides for Android via Java API 参考
description: 存储主题定义的字体。
type: docs
url: /zh/com.aspose.slides/fontscheme/
---
**继承自:**
java.lang.Object

**所有实现的接口:**
[com.aspose.slides.IFontScheme](../../com.aspose.slides/ifontscheme), com.aspose.slides.IDOMObject
```
public class FontScheme implements IFontScheme, IDOMObject
```

存储主题定义的字体。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMinor()](#getMinor--) | 返回幻灯片"body"部分的字体集合。 |
| [getMajor()](#getMajor--) | 返回幻灯片"heading"部分的字体集合。 |
| [getName()](#getName--) | 返回字体方案名称。 |
| [setName(String value)](#setName-java.lang.String-) | 返回字体方案名称。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getMinor() {#getMinor--}
```
public final IFonts getMinor()
```


返回幻灯片"body"部分的字体集合。只读 [IFonts](../../com.aspose.slides/ifonts)。

**返回:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public final IFonts getMajor()
```


返回幻灯片"heading"部分的字体集合。只读 [IFonts](../../com.aspose.slides/ifonts)。

**返回:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public final String getName()
```


返回字体方案名称。读写 String。

**返回:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


返回字体方案名称。读写 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


返回 Parent_Immediate 对象。只读 IDOMObject。

**返回:**
com.aspose.slides.IDOMObject