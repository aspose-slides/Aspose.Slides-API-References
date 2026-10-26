---
title: FontsManager
second_title: Aspose.Slides for Java API リファレンス
description: プレゼンテーション全体のフォントを管理します。
type: docs
url: /ja/com.aspose.slides/fontsmanager/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)  
```
public class FontsManager implements IFontsManager
```

プレゼンテーション全体のフォントを管理します。

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // プレゼンテーションを読み込む
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // 置き換えるソースフォントを読み込む
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // プレゼンテーションを保存する
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | レンダリング時に使用するフォント置換。 |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | レンダリング時に使用するフォント置換。 |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | フォールバック機能による適切な置換のために、フォントコレクションを管理する FontFallBack ルールのユーザーコレクションを表します。読み取り/書き込み [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。 |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | フォールバック機能による適切な置換のために、フォントコレクションを管理する FontFallBack ルールのユーザーコレクションを表します。読み取り/書き込み [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。 |
| [getFonts()](#getFonts--) | プレゼンテーションで使用されているフォントを返します。 |
| [getSubstitutions()](#getSubstitutions--) | プレゼンテーションのレンダリング時に置き換えられるフォントに関する情報を取得します。 |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | 指定されたスライドのレンダリング時に置き換えられるフォントに関する情報を取得します。 |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | プレゼンテーションに埋め込まれたフォントを返します。 |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | 埋め込まれたフォントを削除します。 |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | 埋め込まれたフォントを追加します。 |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | 埋め込まれたフォントを追加します。 |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | プレゼンテーション内のフォントを置換します。 |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | [FontSubstRule](../../com.aspose.slides/fontsubstrule) で提供された情報を使用してプレゼンテーション内のフォントを置換します。 |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | [FontSubstRule](../../com.aspose.slides/fontsubstrule) コレクションで提供された情報を使用してプレゼンテーション内のフォントを置換します。 |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | 指定されたフォントスタイルとフォントデータに対するフォントデータを表すバイト配列を取得します。 |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | 指定されたバイト配列とフォント名からフォントの埋め込みレベルを判定します。 |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

レンダリング時に使用するフォント置換。読み取り/書き込み [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。

**戻り値:**  
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

レンダリング時に使用するフォント置換。読み取り/書き込み [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

フォールバック機能による適切な置換のために、フォントコレクションを管理する FontFallBack ルールのユーザーコレクションを表します。読み取り/書き込み [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager から空または事前に初期化されたルールコレクションを取得
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // コレクションにルールを追加
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // または
>      // 新しいルールコレクションのインスタンスを初期化
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // コレクションにルールを追加
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // FontsManager で既存のコレクションを新しいものに置き換え
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**  
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)

### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

フォールバック機能による適切な置換のために、フォントコレクションを管理する FontFallBack ルールのユーザーコレクションを表します。読み取り/書き込み [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager から空または事前に初期化されたルールコレクションを取得
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // コレクションにルールを追加
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // または
>      // 新しいルールコレクションのインスタンスを初期化
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // コレクションにルールを追加
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // FontsManager で既存のコレクションを新しいものに置き換え
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public final IFontData[] getFonts()
```

プレゼンテーションで使用されているフォントを返します。

**戻り値:**  
com.aspose.slides.IFontData[] - フォントの配列

### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

プレゼンテーションのレンダリング時に置き換えられるフォントに関する情報を取得します。

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


**戻り値:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - すべてのフォント置換のコレクション [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)。

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

指定されたスライドのレンダリング時に置き換えられるフォントに関する情報を取得します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      int[] targetSlides = { 1, 2, 5 };
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions(targetSlides))
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| slides | int[] | 1 から始まるスライドインデックスの配列 |

**戻り値:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - 指定されたスライドのすべてのフォント置換 ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo))。

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

プレゼンテーションに埋め込まれたフォントを返します。

**戻り値:**  
com.aspose.slides.IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

埋め込まれたフォントを削除します。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

埋め込まれたフォントを追加します。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

埋め込まれたフォントを追加します。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

プレゼンテーション内のフォントを置換します。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | ソースフォント |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 置換先フォント |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

[FontSubstRule](../../com.aspose.slides/fontsubstrule) で提供された情報を使用してプレゼンテーション内のフォントを置換します。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | フォント置換情報 |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

[FontSubstRule](../../com.aspose.slides/fontsubstrule) コレクションで提供された情報を使用してプレゼンテーション内のフォントを置換します。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | フォント置換ルールコレクション |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

指定されたフォントスタイルとフォントデータに対するフォントデータを表すバイト配列を取得します。

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // プレゼンテーションで使用されているすべてのフォントを取得
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // プレゼンテーションの最初のフォントの通常スタイルを表すバイト配列を取得
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | フォントに関する情報を含むフォントデータオブジェクト [IFontData](../../com.aspose.slides/ifontdata)。 |
| fontStyle | int | データを取得するフォントのスタイル [FontStyleType](../../com.aspose.slides/fontstyletype)。 |

**戻り値:**  
byte[] - 指定されたフォントスタイルのフォントデータを含むバイト配列。フォントデータまたはスタイルが見つからない場合は null を返します。

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

指定されたバイト配列とフォント名からフォントの埋め込みレベルを判定します。

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // プレゼンテーションで使用されているすべてのフォントを取得
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // プレゼンテーションの最初のフォントの通常スタイルを表すバイト配列を取得
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // フォントの埋め込みレベルを判定
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontBytes | byte[] | フォントデータを含むバイト配列。 |
| fontName | java.lang.String | フォント名。 |

**戻り値:**  
int - 指定されたフォントの埋め込みレベル。