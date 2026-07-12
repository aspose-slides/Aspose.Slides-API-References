---
title: EmbeddedWoffFontsHtmlController
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: WOFF 形式でフォントを埋め込むために使用するフォーマットコントローラクラス
type: docs
url: /ja/com.aspose.slides/embeddedwofffontshtmlcontroller/
---
**継承:**
java.lang.Object

**すべて実装されたインターフェイス:**
[com.aspose.slides.IEmbeddedWoffFontsHtmlController](../../com.aspose.slides/iembeddedwofffontshtmlcontroller)
```
public class EmbeddedWoffFontsHtmlController implements IEmbeddedWoffFontsHtmlController
```

WOFF形式でフォントを埋め込むために使用するフォーマットコントローラクラス
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [EmbeddedWoffFontsHtmlController()](#EmbeddedWoffFontsHtmlController--) | 新しいインスタンスを作成します。 |
| [EmbeddedWoffFontsHtmlController(IHtmlFormattingController controller)](#EmbeddedWoffFontsHtmlController-com.aspose.slides.IHtmlFormattingController-) | 新しいインスタンスを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
### EmbeddedWoffFontsHtmlController() {#EmbeddedWoffFontsHtmlController--}
```
public EmbeddedWoffFontsHtmlController()
```


新しいインスタンスを作成します。

### EmbeddedWoffFontsHtmlController(IHtmlFormattingController controller) {#EmbeddedWoffFontsHtmlController-com.aspose.slides.IHtmlFormattingController-}
```
public EmbeddedWoffFontsHtmlController(IHtmlFormattingController controller)
```


新しいインスタンスを作成します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| controller | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | HTML フォーマットコントローラ。 |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


HTMLドキュメントヘッダーを書き込むために呼び出されます。プレゼンテーション変換ごとに一度呼び出されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


HTMLドキュメントフッターを書き込むために呼び出されます。プレゼンテーション変換ごとに一度呼び出されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


HTMLスライドヘッダーを書き込むために呼び出されます。各スライドごとに一度呼び出されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


HTMLスライドフッターを書き込むために呼び出されます。各スライドごとに一度呼び出されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


シェイプの描画前に呼び出されます。各シェイプごとに一度呼び出されます。この関数が generator に何かを書き込むと、現在のスライド画像生成が終了し、追加された HTML フラグメントが挿入され、前の画像の上に新しい画像が開始されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


シェイプの描画前に呼び出されます。各シェイプごとに一度呼び出されます。この関数が generator に何かを書き込むと、現在のスライド画像生成が終了し、追加された HTML フラグメントが挿入され、前の画像の上に新しい画像が開始されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |