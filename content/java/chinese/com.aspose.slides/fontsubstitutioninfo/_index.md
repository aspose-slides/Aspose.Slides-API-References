---
title: FontSubstitutionInfo
second_title: Aspose.Slides for Java API 参考
description: 此结构表示在渲染时的字体替换信息。
type: docs
url: /zh/com.aspose.slides/fontsubstitutioninfo/
---
**继承:**  
java.lang.Object  
```
public class FontSubstitutionInfo
```

此结构表示在渲染时的字体替换信息。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions())
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 构造函数

| Constructor | Description |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | 创建 [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) 类的实例。 |
## 方法

| Method | Description |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | 指示演示文稿中的源字体名称。 |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | 指示原始字体的替换字体名称。 |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```


创建 [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) 类的实例。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| originFontName | java.lang.String | 演示文稿中的源字体名称 String |
| substFontName | java.lang.String | 原始字体的替换字体名称 String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```


指示演示文稿中的源字体名称。只读 String

**返回:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```


指示原始字体的替换字体名称。只读 String

**返回:**
java.lang.String