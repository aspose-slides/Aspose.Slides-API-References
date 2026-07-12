---
title: ImageCollection
second_title: Java API を介した Android 用 Aspose.Slides リファレンス
description: PPImage のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/imagecollection/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されている全インターフェイス:**  
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

PPImage のコレクションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクション内の画像の数を返します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | 別のプレゼンテーションから画像のコピーを追加します。 |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | プレゼンテーションに画像を追加します。 |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | ストリームからプレゼンテーションに画像を追加します。 |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | ストリームから画像を作成し、プレゼンテーションに追加します。 |
| [addImage(byte[] buffer)](#addImage-byte---) | 指定されたバッファからプレゼンテーションに画像を追加します。 |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Svg オブジェクトからプレゼンテーションに画像を追加します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期化ルートを返します。 |

### size() {#size--}
```
public final int size()
```

コレクション内の画像の数を返します。読み取り専用 int 。

**戻り値:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```

指定されたインデックスの要素を取得します。読み取り専用 [IPPImage](../../com.aspose.slides/ippimage)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IPPImage](../../com.aspose.slides/ippimage)

### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```

別のプレゼンテーションから画像のコピーを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | ソース画像。 |

**戻り値:**
[IPPImage](../../com.aspose.slides/ippimage) - 追加された画像。

### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```

プレゼンテーションに画像を追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | 追加する画像。

--------------------

このメソッドは、WMF/EMF メタファイルをプレゼンテーションに挿入する前にラスタ PNG 画像に変換します。 |

**戻り値:**
[IPPImage](../../com.aspose.slides/ippimage) - 追加された画像。

### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```

ストリームからプレゼンテーションに画像を追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | 画像を追加するストリーム。

--------------------

このメソッドは、WMF/EMF メタファイルをラスタ PNG 画像に変換せずにプレゼンテーションに追加できます。 |

**戻り値:**
[IPPImage](../../com.aspose.slides/ippimage) - 追加された画像。

### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

ストリームから画像を作成し、プレゼンテーションに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | 画像ファイルを追加するストリーム。 |
| loadingStreamBehavior | int | ストリームに適用される動作。 |

**戻り値:**
[IPPImage](../../com.aspose.slides/ippimage) - 追加された [IPPImage](../../com.aspose.slides/ippimage)。

### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```

指定されたバッファからプレゼンテーションに画像を追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | byte[] | バッファ。 |

**戻り値:**
[IPPImage](../../com.aspose.slides/ippimage) - 追加された画像。

### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```

Svg オブジェクトからプレゼンテーションに画像を追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Svg 画像オブジェクト [ISvgImage](../../com.aspose.slides/isvgimage) |

**戻り値:**
[IPPImage](../../com.aspose.slides/ippimage) - 追加された画像。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - コレクションを反復処理できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - コレクション全体の java.util.Iterator。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクションのすべての要素を指定された配列にコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 対象配列。 |
| index | int | 対象配列の開始インデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を返します。読み取り専用 boolean 。

**戻り値:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期化ルートを返します。読み取り専用 Object 。

**戻り値:**
java.lang.Object