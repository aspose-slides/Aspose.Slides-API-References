---
title: FontSubstitutionInfo
second_title: Aspose.Slides for Android via Java API 参考
description: 此结构表示在渲染时字体替换的信息。
type: docs
url: /zh/com.aspose.slides/fontsubstitutioninfo/
---
**继承:** 
java.lang.Object
```
public class FontSubstitutionInfo
```

此结构表示字体替换在渲染时的信息。

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
## Constructors

| Constructor | Description |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Creates an instance of [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) class. |
## Methods

| Method | Description |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Indicates source font name in presentation. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Indicates the replacement font name for the original font. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```

Creates an instance of [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| originFontName | java.lang.String | Source font name in presentation String |
| substFontName | java.lang.String | Replacement font name for the original font String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```

Indicates source font name in presentation. Read-only String

**Returns:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()

指示原始字体的替代字体名称。只读 String

**返回值:**
java.lang.String