---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides for Java API リファレンス
description: WOFF 形式でプレゼンテーションのすべてのフォントを埋め込むために使用するフォーマット コントローラクラスです。
type: docs
url: /ja/com.aspose.slides/embedallfontshtmlcontroller/
---
**継承:**
java.lang.Object

**実装された全インターフェイス:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

プレゼンテーションのすべてのフォントを WOFF 形式で埋め込むために使用するフォーマット コントローラクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | 新しいインスタンスを作成します |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | 新しいインスタンスを作成します |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML ドキュメントのヘッダーを書き込むために呼び出されます。 |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML ドキュメントのフッターを書き込むために呼び出されます。 |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML スライドのヘッダーを書き込むために呼び出されます。 |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML スライドのフッターを書き込むために呼び出されます。 |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | 形状のレンダリング前に呼び出されます。 |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | 形状のレンダリング前に呼び出されます。 |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | [Presentation](../../com.aspose.slides/presentation) に含まれるすべてのフォントを書き込みます。 |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | データを base64 として HTML ドキュメント自体に書き込みます |

### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```

新しいインスタンスを作成します

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```

新しいインスタンスを作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | 埋め込みから除外するフォント |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

HTML ドキュメントのヘッダーを書き込むために呼び出されます。プレゼンテーション変換ごとに一度呼び出されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 出力オブジェクト。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 現在レンダリング中のプレゼンテーション。 |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

HTML ドキュメントのフッターを書き込むために呼び出されます。プレゼンテーション変換ごとに一度呼び出されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 出力オブジェクト。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 現在レンダリング中のプレゼンテーション。 |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

HTML スライドのヘッダーを書き込むために呼び出されます。各スライドごとに一度呼び出されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 出力オブジェクト。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 現在レンダリング中のスライド。 |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

HTML スライドのフッターを書き込むために呼び出されます。各スライドごとに一度呼び出されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 出力オブジェクト。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 現在レンダリング中のスライド。 |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

形状のレンダリング前に呼び出されます。各形状ごとに一度呼び出されます。この関数が generator に何かを書き込むと、現在のスライド画像生成が終了し、HTML フラグメントが挿入され、前の画像の上に新しい画像が開始されます。

**パラメータ:**
| パラメータ | 型 | 記述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 出力オブジェクト。 |
| shape | [IShape](../../com.aspose.slides/ishape) | これからレンダリングされる形状。 |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

形状のレンダリング前に呼び出されます。各形状ごとに一度呼び出されます。この関数が generator に何かを書き込むと、現在のスライド画像生成が終了し、HTML フラグメントが挿入され、前の画像の上に新しい画像が開始されます。

**パラメータ:**
| パラメータ | 型 | 記述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 出力オブジェクト。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 最後にレンダリングされた形状。 |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

[Presentation](../../com.aspose.slides/presentation) に含まれるすべてのフォントを書き込みます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 出力オブジェクト。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 現在レンダリング中のプレゼンテーション。 |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```

データを base64 として HTML ドキュメント自体に書き込みます

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | HTML ジェネレーター |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | シリアライズされるフォント |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | 置換フォント（フォント置換が発生した場合）、それ以外は null |
| fontStyle | java.lang.String | フォントスタイル |
| fontWeight | java.lang.String | フォントの太さ |
| fontData | byte[] | フォントデータ |