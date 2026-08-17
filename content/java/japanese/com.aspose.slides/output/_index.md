---
title: Output
second_title: Aspose.Slides の Java API リファレンス
description: IWebDocument 用の出力要素のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/output/
---
**継承:**
java.lang.Object
```
public final class Output
```

IWebDocument 用の出力要素のコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Adds an output element for the context object. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Adds an output element for the image. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Adds an output element for the image. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Adds an output element for the video. |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | Adds an output element for the audio. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Creates and adds an output file element for the specified font. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Adds an output element for the text content. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Binds resource to output file. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Returns the path for a given resource. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

コンテキスト オブジェクト用の出力要素を追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | java.lang.String | 出力パス。 |
| templateKey | java.lang.String | 出力前にコンテキスト オブジェクトを変換するために使用されるテンプレートのキー。 |
| contextObject | TContextObject | コンテキスト オブジェクト。 |

**戻り値:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) コンテキスト オブジェクト用のオブジェクト。

### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

画像用の出力要素を追加します。

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

画像用の出力要素を追加します。

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

ビデオ用の出力要素を追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | java.lang.String | 出力パス。 |
| video | [IVideo](../../com.aspose.slides/ivideo) | 出力するビデオ。 |

**戻り値:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) ビデオ用のオブジェクト。

### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```

オーディオ用の出力要素を追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | java.lang.String | 出力パス。 |
| audio | [IAudio](../../com.aspose.slides/iaudio) | 出力するオーディオ。 |

**戻り値:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) オーディオ用のオブジェクト。

### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

指定されたフォント用の出力ファイル要素を作成し、追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | java.lang.String | フォント出力が保存されるファイル パス。 |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 出力に書き込むフォント データ。 |
| fontStyle | int | フォントのスタイル（例: Regular、Bold、Italic）。 |

**戻り値:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - 生成されたフォント用の [IOutputFile](../../com.aspose.slides/ioutputfile) インスタンス。

### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

テキスト コンテンツ用の出力要素を追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | java.lang.String | 出力パス。 |
| textContent | java.lang.String | 出力するコンテンツ。 |

**戻り値:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) テキスト コンテンツ用のオブジェクト。

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
java.lang.String - リソース パス。