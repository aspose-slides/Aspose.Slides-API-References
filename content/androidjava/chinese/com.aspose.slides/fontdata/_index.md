---
title: FontData
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示字体定义。
type: docs
url: /zh/com.aspose.slides/fontdata/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

表示字体定义。不可变。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | 使用指定的字体名称创建一个新的 FontData 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFontName()](#getFontName--) | 返回字体名称。 |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | 返回字体名称，将主题引用替换为实际使用的字体。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定两个 FontData 实例是否相等。 |
| [hashCode()](#hashCode--) | 作为特定类型的哈希函数，适用于哈希算法和哈希表等数据结构。 |
| [toString()](#toString--) | 返回字符串表示。 |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

使用指定的字体名称创建一个新的 FontData 对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | 字体名称。 |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

返回字体名称。读/写 String。

**返回值：**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

返回字体名称，将主题引用替换为实际使用的字体。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | 应从中获取主题化字体名称的主题。调用方必须提供正确的值。参见 [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**返回值：**
java.lang.String - 字体名称。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定两个 FontData 实例是否相等。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要与当前 FontData 比较的 FontData。 |

**返回值：**
boolean - **true** 如果指定的 FontData 等于当前 FontData；否则 **false**。
### hashCode() {#hashCode--}
```
public int hashCode()
```

作为特定类型的哈希函数，适用于哈希算法和哈希表等数据结构。

**返回值：**
int - FontData 的哈希码。
### toString() {#toString--}
```
public String toString()
```

返回字符串表示。

**返回值：**
java.lang.String - String 表示。