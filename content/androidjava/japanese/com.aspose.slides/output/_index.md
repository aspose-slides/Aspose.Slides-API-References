---
title: Output
second_title: Java API リファレンスを使用した Aspose.Slides for Android
description: IWebDocument 用の出力要素のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/output/
---
**継承:**
java.lang.Object
```
public final class Output
```

IWebDocument 用の出力要素コレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | コンテキストオブジェクトの出力要素を追加します。 |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | 画像の出力要素を追加します。 |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | 画像の出力要素を追加します。 |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | 動画の出力要素を追加します。 |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | 指定されたフォントの出力ファイル要素を作成して追加します。 |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | テキストコンテンツの出力要素を追加します。 |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | リソースを出力ファイルにバインドします。 |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | 指定されたリソースのパスを返します。 |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

コンテキストオブジェクトの出力要素を追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | java.lang.String | 出力パス。 |
| templateKey | java.lang.String | 出力前にコンテキストオブジェクトを変換するために使用されるテンプレートのキー。 |
| contextObject | TContextObject | コンテキストオブジェクト。 |

**戻り値:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) コンテキストオブジェクト用のオブジェクト。

### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

画像の出力要素を追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | java.lang.String | 出力パス。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 出力する画像。 |

**戻り値:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 画像用のオブジェクト。

### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

画像の出力要素を追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | java.lang.String | 出力パス。 |
| image | [IImage](../../com.aspose.slides/iimage) | 出力する画像。 |

**戻り値:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 画像用のオブジェクト。

### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

動画の出力要素を追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | java.lang.String | 出力パス。 |
| video | [IVideo](../../com.aspose.slides/ivideo) | 出力する動画。 |

**戻り値:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 動画用のオブジェクト。

### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

指定されたフォントの出力ファイル要素を作成して追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | java.lang.String | フォント出力を保存するファイルパス。 |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 出力に書き込むフォントデータ。 |
| fontStyle | int | フォントのスタイル（例: Regular, Bold, Italic）。 |

**戻り値:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - 生成されたフォント用の [IOutputFile](../../com.aspose.slides/ioutputfile) インスタンス。

### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

テキストコンテンツの出力要素を追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | java.lang.String | 出力パス。 |
| textContent | java.lang.String | 出力するコンテンツ。 |

**戻り値:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) テキストコンテンツ用のオブジェクト。

### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

リソースを出力ファイルにバインドします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | 出力ファイル。 |
| obj | java.lang.Object | リソースオブジェクト。 |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```

指定されたリソースのパスを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | リソースオブジェクト。 |

**戻り値:**
java.lang.String - リソースパス。