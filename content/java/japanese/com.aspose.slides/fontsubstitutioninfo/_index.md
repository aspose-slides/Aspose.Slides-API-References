---
title: FontSubstitutionInfo
second_title: Aspose.Slides for Java API リファレンス
description: この構造体は、フォントが置き換えられる際の情報を表します。
type: docs
url: /ja/com.aspose.slides/fontsubstitutioninfo/
---
**継承:**
java.lang.Object
```
public class FontSubstitutionInfo
```

この構造体は、フォントが置き換えられる際の情報を表します。

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
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) クラスのインスタンスを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | プレゼンテーション内の元フォント名を示します。 |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | 元フォントの置き換えフォント名を示します。 |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```

[FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) クラスのインスタンスを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| originFontName | java.lang.String | プレゼンテーション内の元フォント名 String |
| substFontName | java.lang.String | 元フォントの置き換えフォント名 String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```

プレゼンテーション内の元フォント名を示します。読み取り専用 String

**戻り値:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```

元フォントの置き換えフォント名を示します。読み取り専用 String

**戻り値:**
java.lang.String