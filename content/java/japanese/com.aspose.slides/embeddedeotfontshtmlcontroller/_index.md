---
title: EmbeddedEotFontsHtmlController
second_title: Aspose.Slides for Java API リファレンス
description: EOT 形式でフォントを埋め込む際に使用するフォーマットコントローラクラス
type: docs
url: /ja/com.aspose.slides/embeddedeotfontshtmlcontroller/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IEmbeddedEotFontsHtmlController](../../com.aspose.slides/iembeddedeotfontshtmlcontroller)  
```
public class EmbeddedEotFontsHtmlController implements IEmbeddedEotFontsHtmlController
```

EOT 形式でフォントを埋め込むために使用するフォーマットコントローラクラス

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [EmbeddedEotFontsHtmlController()](#EmbeddedEotFontsHtmlController--) | 新しいインスタンスを作成します。 |
| [EmbeddedEotFontsHtmlController(IHtmlFormattingController controller)](#EmbeddedEotFontsHtmlController-com.aspose.slides.IHtmlFormattingController-) | 新しいインスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |

### EmbeddedEotFontsHtmlController() {#EmbeddedEotFontsHtmlController--}
```
public EmbeddedEotFontsHtmlController()
```

新しいインスタンスを作成します。

### EmbeddedEotFontsHtmlController(IHtmlFormattingController controller) {#EmbeddedEotFontsHtmlController-com.aspose.slides.IHtmlFormattingController-}
```
public EmbeddedEotFontsHtmlController(IHtmlFormattingController controller)
```

新しいインスタンスを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| controller | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | HTML フォーマットコントローラ。 |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

HTML ドキュメントのヘッダーを書き込むために呼び出されます。プレゼンテーション変換ごとに 1 回呼び出されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

HTML ドキュメントのフッターを書き込むために呼び出されます。プレゼンテーション変換ごとに 1 回呼び出されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

HTML スライドのヘッダーを書き込むために呼び出されます。各スライドごとに 1 回呼び出されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

HTML スライドのフッターを書き込むために呼び出されます。各スライドごとに 1 回呼び出されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

シェイプの描画前に呼び出されます。各シェイプごとに 1 回呼び出されます。この関数が generator に何かを書き込むと、現在のスライド画像の生成が終了し、追加された HTML フラグメントが挿入され、前の画像の上に新しい画像が開始されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

シェイプの描画前に呼び出されます。各シェイプごとに 1 回呼び出されます。この関数が generator に何かを書き込むと、現在のスライド画像の生成が終了し、追加された HTML フラグメントが挿入され、前の画像の上に新しい画像が開始されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |