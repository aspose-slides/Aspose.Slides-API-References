---
title: VideoPlayerHtmlController
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: このクラスはビデオおよびオーディオファイルを HTML にエクスポートすることを可能にします
type: docs
url: /ja/com.aspose.slides/videoplayerhtmlcontroller/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IVideoPlayerHtmlController](../../com.aspose.slides/ivideoplayerhtmlcontroller)  
```
public class VideoPlayerHtmlController implements IVideoPlayerHtmlController
```

このクラスはビデオおよびオーディオファイルをHTMLにエクスポートすることを可能にします。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [VideoPlayerHtmlController(String path, String fileName, String baseUri)](#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-) | Creates a new instance of controller |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) |  |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) |  |
| [getUrl(int id, int referrer)](#getUrl-int-int-) |  |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) |  |

### VideoPlayerHtmlController(String path, String fileName, String baseUri) {#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-}
```
public VideoPlayerHtmlController(String path, String fileName, String baseUri)
```

Creates a new instance of controller

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | java.lang.String | The path where video and audio files will be generated |
| fileName | java.lang.String | The name of the HTML file |
| baseUri | java.lang.String | The base URI which will be used for links generating |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

HTML ドキュメントのヘッダーを書き込むために呼び出されます。プレゼンテーションの変換ごとに一度呼び出されます。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

HTML ドキュメントのフッターを書き込むために呼び出されます。プレゼンテーションの変換ごとに一度呼び出されます。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

HTML スライドのヘッダーを書き込むために呼び出されます。各スライドごとに一度呼び出されます。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

HTML スライドのフッターを書き込むために呼び出されます。各スライドごとに一度呼び出されます。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

シェイプの描画の前に呼び出されます。各シェイプごとに一度呼び出されます。この関数が generator に何かを書き込むと、現在のスライド画像の生成が終了し、追加された HTML フラグメントが挿入され、前の画像の上に新しい画像が開始されます。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

シェイプの描画の前に呼び出されます。各シェイプごとに一度呼び出されます。この関数が generator に何かを書き込むと、現在のスライド画像の生成が終了し、追加された HTML フラグメントが挿入され、前の画像の上に新しい画像が開始されます。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public final void formatShape(ISvgShape svgShape, IShape shape)
```

この関数は、シェイプを SVG にレンダリングする前に呼び出され、ユーザーが生成される SVG を制御できるようにします。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public final int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

オブジェクトの保存場所を決定します。このメソッドは各オブジェクト ID ごとに一度呼び出されます。同じデータ、semanticName、contentType を持ち、異なる id を持つオブジェクトが二つ存在しないことは保証されません。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |
| semanticName | java.lang.String |  |
| contentType | java.lang.String |  |
| recomendedExtension | java.lang.String |  |

**戻り値:**  
int

### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public final String getUrl(int id, int referrer)
```

外部オブジェクトへの URL を返します。このメソッドは、\#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) が [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) を返した場合に常に呼び出され、[LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) を返したが埋め込みが不可能な場合にも呼び出される可能性があります。同じオブジェクト ID に対して複数回呼び出すことができます。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | int |  |
| referrer | int |  |

**戻り値:**  
java.lang.String

### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public final void saveExternal(int id, byte[] entityData)
```

外部オブジェクトを保存します。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |