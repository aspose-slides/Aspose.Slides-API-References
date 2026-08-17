---
title: IHtmlFormattingController
second_title: Aspose.Slides for Java API Reference
description: HTMLファイルの生成を制御します。
type: docs
url: /ja/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

HTMLファイルの生成を制御します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Called to write html document header. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Called to write html document footer. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Called to write html slide header. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Called to write html slide footer. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Called before shape's rendering. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Called before shape's rendering. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

HTMLドキュメントヘッダーの書き込みを行います。プレゼンテーションの変換ごとに一度呼び出されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Output object. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentation which being currently rendered. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

HTMLドキュメントフッターの書き込みを行います。プレゼンテーションの変換ごとに一度呼び出されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Output object. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentation which being currently rendered. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

HTMLスライドヘッダーの書き込みを行います。各スライドごとに一度呼び出されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Output object. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide which being currently rendered. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

HTMLスライドフッターの書き込みを行います。各スライドごとに一度呼び出されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Output object. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide which being currently rendered. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

シェイプの描画前に呼び出されます。シェイプごとに一度呼び出されます。この関数が generator に何かを書き込むと、現在のスライド画像の生成が終了し、追加された HTML フラグメントが挿入され、前の画像の上に新しい画像が開始されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Output object. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape which is about to render. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

シェイプの描画前に呼び出されます。シェイプごとに一度呼び出されます。この関数が generator に何かを書き込むと、現在のスライド画像の生成が終了し、追加された HTML フラグメントが挿入され、前の画像の上に新しい画像が開始されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Output object. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape which is rendered last. |