---
title: MarkdownSaveOptions
second_title: Aspose.Slides for Android via Java API リファレンス
description: プレゼンテーションを Markdown に保存する方法を制御するオプションを表します。
type: docs
url: /ja/com.aspose.slides/markdownsaveoptions/
---
**継承:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

プレゼンテーションを Markdown に保存する方法を制御するオプションを表します。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getExportType()](#getExportType--) | プレゼンテーションを変換するための Markdown 仕様を指定します。 |
| [setExportType(int value)](#setExportType-int-) | プレゼンテーションを変換するための Markdown 仕様を指定します。 |
| [getBasePath()](#getBasePath--) | リソースを含むドキュメントの保存先となるベースパスを指定します。 |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | リソースを含むドキュメントの保存先となるベースパスを指定します。 |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | 画像を保存するフォルダー名を指定します。 |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | 画像を保存するフォルダー名を指定します。 |
| [getNewLineType()](#getNewLineType--) | 生成されたドキュメントが新しい行 \\r（Macintosh）や \\n（Unix）または \\r\\n（Windows）を使用するかどうかを指定します。 |
| [setNewLineType(int value)](#setNewLineType-int-) | 生成されたドキュメントが新しい行 \\r（Macintosh）や \\n（Unix）または \\r\\n（Windows）を使用するかどうかを指定します。 |
| [getShowComments()](#getShowComments--) | 生成されたドキュメントにコメントを表示するかどうかを指定します。 |
| [setShowComments(boolean value)](#setShowComments-boolean-) | 生成されたドキュメントにコメントを表示するかどうかを指定します。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [getShowSlideNumber()](#getShowSlideNumber--) | 生成されたドキュメントに各スライドの番号を表示するかどうかを指定します。 |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | 生成されたドキュメントに各スライドの番号を表示するかどうかを指定します。 |
| [getFlavor()](#getFlavor--) | プレゼンテーションを変換するための Markdown 仕様を指定します。 |
| [setFlavor(int value)](#setFlavor-int-) | プレゼンテーションを変換するための Markdown 仕様を指定します。 |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Markdown 出力におけるスライド番号ヘッダーに使用される書式文字列を取得または設定します。 |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Markdown 出力におけるスライド番号ヘッダーに使用される書式文字列を取得または設定します。 |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Markdown エクスポート時に繰り返し出現する通常のスペース文字の取り扱い方法を指定します。 |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Markdown エクスポート時に繰り返し出現する通常のスペース文字の取り扱い方法を指定します。 |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | true に設定すると、最終的な Markdown 出力から空行または空白のみの行を削除します。 |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | true に設定すると、最終的な Markdown出力から空行または空白のみの行を削除します。 |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Markdown エクスポート中に SVG 以外の画像（ビットマップまたはメタファイル）ごとに発生します。 |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Markdown エクスポート中に SVG 画像ごとに発生します。 |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

コンストラクタ。

### getExportType() {#getExportType--}
```
public final int getExportType()
```

プレゼンテーションを変換するための Markdown 仕様を指定します。デフォルトは TextOnly です。

**戻り値:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

プレゼンテーションを変換するための Markdown 仕様を指定します。デフォルトは TextOnly です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

リソースを含むドキュメントの保存先となるベースパスを指定します。デフォルトはアプリケーションの現在のディレクトリです。

**戻り値:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

リソースを含むドキュメントの保存先となるベースパスを指定します。デフォルトはアプリケーションの現在のディレクトリです。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

画像を保存するフォルダー名を指定します。デフォルトは Images です。

**戻り値:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

画像を保存するフォルダー名を指定します。デフォルトは Images です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

生成されたドキュメントが新しい行 \\r（Macintosh）や \\n（Unix）または \\r\\n（Windows）を使用するかどうかを指定します。デフォルトは Unix です。

**戻り値:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

生成されたドキュメントが新しい行 \\r（Macintosh）や \\n（Unix）または \\r\\n（Windows）を使用するかどうかを指定します。デフォルトは Unix です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

生成されたドキュメントにコメントを表示するかどうかを指定します。デフォルトは false です。

**戻り値:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

生成されたドキュメントにコメントを表示するかどうかを指定します。デフォルトは false です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは false です。

**戻り値:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは false です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

生成されたドキュメントに各スライドの番号を表示するかどうかを指定します。デフォルトは false です。

**戻り値:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

生成されたドキュメントに各スライドの番号を表示するかどうかを指定します。デフォルトは false です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

プレゼンテーションを変換するための Markdown 仕様を指定します。デフォルトは Multi-markdown です。

**戻り値:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

プレゼンテーションを変換するための Markdown 仕様を指定します。デフォルトは Multi-markdown です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

Markdown 出力におけるスライド番号ヘッダーに使用される書式文字列を取得または設定します。書式には必ず「\{0\}」プレースホルダーを含める必要があり、エクスポート時にスライドインデックスに置き換えられます。例: 「\# Slide \{0\}」は「\# Slide 1」「\# Slide 2」などを生成します。

**戻り値:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

Markdown 出力におけるスライド番号ヘッダーに使用される書式文字列を取得または設定します。書式には必ず「\{0\}」プレースホルダーを含める必要があり、エクスポート時にスライドインデックスに置き換えられます。例: 「\# Slide \{0\}」は「\# Slide 1」「\# Slide 2」などを生成します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

Markdown エクスポート時に繰り返し出現する通常のスペース文字の取り扱い方法を指定します。このプロパティは、連続するスペースが以下のいずれかになるかを定義します:
- 通常のスペース文字として保持する
- 通常のスペースとノーブレークスペースエンティティ（�）を交互にする
- 最初のスペース以降をノーブレークスペースで完全に置換し、Markdown 出力で視覚的な整列を保持する
デフォルト値は [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp) です。

**戻り値:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

Markdown エクスポート時に繰り返し出現する通常のスペース文字の取り扱い方法を指定します。このプロパティは、連続するスペースが以下のいずれかになるかを定義します:
- 通常のスペース文字として保持する
- 通常のスペースとノーブレークスペースエンティティ（�）を交互にする
- 最初のスペース以降をノーブレークスペースで完全に置換し、Markdown 出力で視覚的な整列を保持する
デフォルト値は [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp) です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

true に設定すると、最終的な Markdown 出力から空行または空白のみの行を削除します。デフォルトは false です。

**戻り値:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

true に設定すると、最終的な Markdown 出力から空行または空白のみの行を削除します。デフォルトは false です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

Markdown エクスポート中に SVG 以外の画像（ビットマップまたはメタファイル）ごとに発生します。画像の保存方法および参照方法をカスタマイズできます。処理しない場合、画像はローカルに相対リンクで保存されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Markdown 画像保存イベント。 |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

Markdown エクスポート中に SVG 画像ごとに発生します。デフォルトの保存方法とリンク生成を上書きできます。処理しない場合、SVG はローカルに相対リンクで保存されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Markdown SVG 画像保存イベント。 |