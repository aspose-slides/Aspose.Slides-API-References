---
title: IFontScheme
second_title: Aspose.Slides for Java API 参考
description: 存储主题定义的字体。
type: docs
url: /zh/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

存储主题定义的字体。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMinor()](#getMinor--) | 返回幻灯片“正文”部分的字体集合。 |
| [getMajor()](#getMajor--) | 返回幻灯片“标题”部分的字体集合。 |
| [getName()](#getName--) | 返回字体方案名称。 |
| [setName(String value)](#setName-java.lang.String-) | 返回字体方案名称。 |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```


返回幻灯片“正文”部分的字体集合。只读 [IFonts](../../com.aspose.slides/ifonts)。

**返回:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```


返回幻灯片“标题”部分的字体集合。只读 [IFonts](../../com.aspose.slides/ifonts)。

**返回:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```


返回字体方案名称。可读写 String。

**返回:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


返回字体方案名称。可读写 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |