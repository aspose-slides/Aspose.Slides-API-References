---
title: IHtmlFormattingController
second_title: Aspose.Slides for Android via Java API Reference
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
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTMLドキュメントヘッダーを書き込むために呼び出されます。 |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTMLドキュメントフッターを書き込むために呼び出されます。 |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTMLスライドヘッダーを書き込むために呼び出されます。 |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTMLスライドフッターを書き込むために呼び出されます。 |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | シェイプのレンダリング前に呼び出されます。 |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | シェイプのレンダリング前に呼び出されます。 |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

HTMLドキュメントヘッダーを書き込むために呼び出されます。プレゼンテーションの変換ごとに1回呼び出されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 出力オブジェクト。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 現在レンダリング中のプレゼンテーション。 |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

HTMLドキュメントフッターを書き込むために呼び出されます。プレゼンテーションの変換ごとに1回呼び出されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 出力オブジェクト。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 現在レンダリング中のプレゼンテーション。 |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

HTMLスライドヘッダーを書き込むために呼び出されます。各スライドごとに1回呼び出されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 出力オブジェクト。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 現在レンダリング中のスライド。 |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

HTMLスライドフッターを書き込むために呼び出されます。各スライドごとに1回呼び出されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 出力オブジェクト。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 現在レンダリング中のスライド。 |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

シェイプのレンダリング前に呼び出されます。各シェイプごとに1回呼び出されます。この関数がジェネレーターに何かを書き込むと、現在のスライド画像生成が終了し、HTMLフラグメントが挿入され、前の画像の上に新しい画像が開始されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 出力オブジェクト。 |
| shape | [IShape](../../com.aspose.slides/ishape) | レンダリングされるシェイプ。 |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

シェイプのレンダリング前に呼び出されます。各シェイプごとに1回呼び出されます。この関数がジェネレーターに何かを書き込むと、現在のスライド画像生成が終了し、HTMLフラグメントが挿入され、前の画像の上に新しい画像が開始されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 出力オブジェクト。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 最後にレンダリングされたシェイプ。 |