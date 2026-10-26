---
title: IFontData
second_title: Aspose.Slides 的 Java API 参考
description: 表示一个字体定义。
type: docs
url: /zh/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

表示一个字体定义。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFontName()](#getFontName--) | 返回字体名称。 |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | 返回字体名称，将主题引用替换为实际使用的字体。 |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

返回字体名称。只读 String。

**返回:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

返回字体名称，将主题引用替换为实际使用的字体。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | 应该从中获取主题化字体名称的主题。由调用者提供正确的值。 |

**返回:**
java.lang.String - 字体名称。