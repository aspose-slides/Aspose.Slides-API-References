---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides for Android の Java API リファレンス
description: WOFF 形式でプレゼンテーションのすべてのフォントを埋め込むために使用するフォーマットコントローラクラスです。
type: docs
url: /ja/com.aspose.slides/embedallfontshtmlcontroller/
---
**継承:**
java.lang.Object

**実装されたインターフェイス:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

プレゼンテーションのすべてのフォントをWOFF形式で埋め込むために使用するフォーマットコントローラ・クラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | 新しいインスタンスを作成します |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | 新しいインスタンスを作成します |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTMLドキュメントのヘッダーを書き込むために呼び出されます。 |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTMLドキュメントのフッターを書き込むために呼び出されます。 |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTMLスライドのヘッダーを書き込むために呼び出されます。 |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTMLスライドのフッターを書き込むために呼び出されます。 |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | シェイプのレンダリング前に呼び出されます。 |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | シェイプのレンダリング前に呼び出されます。 |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | [Presentation](../../com.aspose.slides/presentation)に含まれるすべてのフォントを書き込みます。 |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | データをBase64としてHTMLドキュメント自体に書き込みます |
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

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | 埋め込みから除外するフォント |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

HTMLドキュメントのヘッダーを書き込むために呼び出されます。プレゼンテーション変換ごとに1回呼び出されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 出力オブジェクト。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 現在レンダリング中のプレゼンテーション。 |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

HTMLドキュメントのフッターを書き込むために呼び出されます。プレゼンテーション変換ごとに1回呼び出されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 出力オブジェクト。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 現在レンダリング中のプレゼンテーション。 |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

HTMLスライドのヘッダーを書き込むために呼び出されます。各スライドごとに1回呼び出されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 出力オブジェクト。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 現在レンダリング中のスライド。 |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

HTMLスライドのフッターを書き込むために呼び出されます。各スライドごとに1回呼び出されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 出力オブジェクト。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 現在レンダリング中のスライド。 |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

シェイプのレンダリング前に呼び出されます。各シェイプごとに1回呼び出されます。この関数がジェネレーターに何らかの出力を書き込むと、現在のスライド画像生成は終了し、追加されたHTMLフラグメントが挿入され、前の画像の上に新しい画像が開始されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 出力オブジェクト。 |
| shape | [IShape](../../com.aspose.slides/ishape) | レンダリングしようとしているシェイプ。 |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

シェイプのレンダリング前に呼び出されます。各シェイプごとに1回呼び出されます。この関数がジェネレーターに何らかの出力を書き込むと、現在のスライド画像生成は終了し、追加されたHTMLフラグメントが挿入され、前の画像の上に新しい画像が開始されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 出力オブジェクト。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 最後にレンダリングされたシェイプ。 |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

[Presentation](../../com.aspose.slides/presentation)に含まれるすべてのフォントを書き込みます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 出力オブジェクト。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 現在レンダリング中のプレゼンテーション。 |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```

データをBase64としてHTMLドキュメント自体に書き込みます

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | HTMLジェネレーター |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | シリアライズ対象のフォント |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | 置換フォント（フォント置換が発生した場合）。それ以外はnull |
| fontStyle | java.lang.String | フォントスタイル |
| fontWeight | java.lang.String | フォントウェイト |
| fontData | byte[] | フォントデータ |
