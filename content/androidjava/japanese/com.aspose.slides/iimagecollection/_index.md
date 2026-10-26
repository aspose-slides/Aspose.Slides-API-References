---
title: IImageCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: PPImage のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/iimagecollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

PPImage のコレクションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | インデックスで画像を返します。 |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | プレゼンテーションに画像を追加します。 |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | ストリームからプレゼンテーションに画像を追加します。 |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | ストリームから画像を作成し、プレゼンテーションに追加します。 |
| [addImage(byte[] buffer)](#addImage-byte---) | 指定されたバッファからプレゼンテーションに画像を追加します。 |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | 別のプレゼンテーションから画像のコピーを追加します。 |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | SVG オブジェクトからプレゼンテーションに画像を追加します。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```

インデックスで画像を返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | インデックス。 |

**戻り値:**
[IPPImage](../../com.aspose.slides/ippimage) - Image.

### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```

プレゼンテーションに画像を追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | 追加する画像。

--------------------

このメソッドは、WMF/EMF メタファイルをラスタ PNG 画像に変換してからプレゼンテーションに挿入します。 |

**戻り値:**
[IPPImage](../../com.aspose.slides/ippimage) - 追加された画像。

### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```

ストリームからプレゼンテーションに画像を追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | 画像を追加するストリーム。

--------------------

このメソッドは、WMF/EMF メタファイルをラスタ PNG 画像に変換せずにプレゼンテーションに追加できます。 |

**戻り値:**
[IPPImage](../../com.aspose.slides/ippimage) - 追加された画像。

### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

ストリームから画像を作成し、プレゼンテーションに追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | 画像ファイルを追加するストリーム。 |
| loadingStreamBehavior | int | ストリームに適用される動作。 |

**戻り値:**
[IPPImage](../../com.aspose.slides/ippimage) - 追加された [IPPImage](../../com.aspose.slides/ippimage)。

### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```

指定されたバッファからプレゼンテーションに画像を追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | byte[] | バッファ。 |

**戻り値:**
[IPPImage](../../com.aspose.slides/ippimage) - 追加された画像。

### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```

別のプレゼンテーションから画像のコピーを追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | ソース画像。 |

**戻り値:**
[IPPImage](../../com.aspose.slides/ippimage) - 追加された画像。

### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```

SVG オブジェクトからプレゼンテーションに画像を追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG 画像オブジェクト [ISvgImage](../../com.aspose.slides/isvgimage) |

**戻り値:**
[IPPImage](../../com.aspose.slides/ippimage) - 追加された画像。