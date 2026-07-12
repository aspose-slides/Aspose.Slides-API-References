---
title: IFontsManager
second_title: Aspose.Slides for Android via Java API Reference
description: プレゼンテーション全体のフォントを管理します。
type: docs
url: /ja/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

プレゼンテーション全体のフォントを管理します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | レンダリング時に使用するフォント置換。読み取り/書き込み [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。 |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | レンダリング時に使用するフォント置換。読み取り/書き込み [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。 |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | ユーザーの FontFallBack ルールコレクションを表し、フォールバック機能による適切な置換のためのフォントコレクションを管理します。読み取り/書き込み [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。 |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | ユーザーの FontFallBack ルールコレクションを表し、フォールバック機能による適切な置換のためのフォントコレクションを管理します。読み取り/書き込み [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。 |
| [getFonts()](#getFonts--) | プレゼンテーションで使用されているフォントを返します |
| [getSubstitutions()](#getSubstitutions--) | プレゼンテーションのレンダリング時に置換されるフォントに関する情報を取得します。 |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | 指定されたスライドのレンダリング時に置換されるフォントに関する情報を取得します。 |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | プレゼンテーションに埋め込まれているフォントを返します |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | 埋め込みフォントを削除します |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | 埋め込みフォントを追加します。 |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | 埋め込みフォントを追加します |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | プレゼンテーション内のフォントを置換します |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) で提供された情報を使用してプレゼンテーション内のフォントを置換します |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) のコレクションで提供された情報を使用してプレゼンテーション内のフォントを置換します |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | 指定されたフォントスタイルとフォントデータに対するフォントデータを表すバイト配列を取得します。 |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | 指定されたバイト配列とフォント名からフォントの埋め込みレベルを決定します。 |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```


レンダリング時に使用するフォント置換。読み取り/書き込み [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。

**戻り値:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```


レンダリング時に使用するフォント置換。読み取り/書き込み [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```


ユーザーの FontFallBack ルールコレクションを表し、フォールバック機能による適切な置換のためのフォントコレクションを管理します。読み取り/書き込み [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager から空または事前に初期化されたルールコレクションを取得
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // コレクションへルールを追加
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // または
>      // 新しいルールコレクションインスタンスの初期化
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // コレクションへルールを追加
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
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```


ユーザーの FontFallBack ルールコレクションを表し、フォールバック機能による適切な置換のためのフォントコレクションを管理します。読み取り/書き込み [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)。

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // FontsManager から空または事前に初期化されたルールコレクションを取得
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // コレクションにルールを追加
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // または 
>      // ルールコレクションの新しいインスタンスを初期化
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public abstract IFontData[] getFonts()
```


プレゼンテーションで使用されているフォントを返します

**戻り値:**
com.aspose.slides.IFontData[] - フォントの配列
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```


プレゼンテーションのレンダリング時に置換されるフォントに関する情報を取得します。

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
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```


指定されたスライドのレンダリング時に置換されるフォントに関する情報を取得します。

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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| slides | int[] | 1 から始まるスライドインデックスの配列で、フォント置換情報を取得する対象です。 |

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - 指定されたスライドのすべてのフォント置換のコレクション ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo))。
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```


プレゼンテーションに埋め込まれているフォントを返します

**戻り値:**
com.aspose.slides.IFontData[] - 埋め込みフォント IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```


埋め込みフォントを削除します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | フォントデータオブジェクト [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```


埋め込みフォントを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | フォントデータオブジェクト [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | 埋め込みフォントルール [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

埋め込みフォントをコピーする際は、ほとんどのフォントが著作権で保護されていることに注意してください。事前にフォントのライセンスを確認し、別のマシンへ自由に転送できるかどうかを確認してください。 |
### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```


埋め込みフォントを追加します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontData | byte[] | フォントデータ byte[] |
| embedFontRule | int | 埋め込みフォントルール [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

埋め込みフォントを追加する際は、ほとんどのフォントが著作権で保護されていることに注意してください。事前にフォントのライセンスを確認し、別のマシンへ自由に転送できるかどうかを確認してください。 |
### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```


プレゼンテーション内のフォントを置換します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | ソースフォント |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 宛先フォント |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```


[IFontSubstRule](../../com.aspose.slides/ifontsubstrule) で提供された情報を使用してプレゼンテーション内のフォントを置換します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | フォント置換情報 |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```


[IFontSubstRule](../../com.aspose.slides/ifontsubstrule) のコレクションで提供された情報を使用してプレゼンテーション内のフォントを置換します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | フォント置換情報コレクション |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```


指定されたフォントスタイルとフォントデータに対するフォントデータを表すバイト配列を取得します。

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // プレゼンテーションで使用されているすべてのフォントを取得
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // プレゼンテーション内の最初のフォントの Regular スタイルを表すバイト配列を取得
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | フォントデータオブジェクトで、フォントに関する情報を含みます [IFontData](../../com.aspose.slides/ifontdata)。 |
| fontStyle | int | 取得するデータのフォントスタイル [FontStyleType](../../com.aspose.slides/fontstyletype)。 |

**戻り値:**
byte[] - 指定されたフォントスタイルのフォントデータを含むバイト配列。フォントデータまたはスタイルが見つからない場合は null を返します。
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```


指定されたバイト配列とフォント名からフォントの埋め込みレベルを決定します。

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // プレゼンテーションで使用されているすべてのフォントを取得
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // プレゼンテーション内の最初のフォントの Regular スタイルを表すバイト配列を取得
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // フォントの埋め込みレベルを決定
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontBytes | byte[] | フォントデータを含むバイト配列。 |
| fontName | java.lang.String | フォント名。 |

**戻り値:**
int - 指定されたフォントの埋め込みレベル。