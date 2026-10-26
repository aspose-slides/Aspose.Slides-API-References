---
title: FontSubstitutionInfo
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 此結構表示字型置換在呈現時的資訊。
type: docs
url: /zh-hant/com.aspose.slides/fontsubstitutioninfo/
---
**繼承:**  
java.lang.Object  
```
public class FontSubstitutionInfo
```

此結構表示字型置換在呈現時的資訊。

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
## 建構子

| 建構子 | 描述 |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | 建立 [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) 類別的實例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | 指示簡報中的來源字型名稱。 |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | 指示原始字型的替代字型名稱。 |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```

建立 [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) 類別的實例。

**參數:**  
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| originFontName | java.lang.String | 簡報中的來源字型名稱 String |
| substFontName | java.lang.String | 原始字型的替代字型名稱 String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```

指示簡報中的來源字型名稱。唯讀 String

**傳回:**  
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```

指示原始字型的替代字型名稱。唯讀 String

**傳回:**  
java.lang.String