---
title: IPPImage
second_title: Aspose.Slides for Java API Reference
description: プレゼンテーション内の画像を表します。
type: docs
url: /ja/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

プレゼンテーション内の画像を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | 画像データのコピーを返します。 |
| [getImage()](#getImage--) | 画像のコピーを返します。 |
| [getSvgImage()](#getSvgImage--) | ISvgImage オブジェクトを取得または設定します [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | ISvgImage オブジェクトを取得または設定します [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | 画像データを置き換えます。 |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | 画像を置き換えます。 |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | 画像を置き換えます。 |
| [getContentType()](#getContentType--) | 画像の MIME タイプを返します（\#getBinaryData.getBinaryData でエンコード）。 |
| [getWidth()](#getWidth--) | 画像の幅を返します。 |
| [getHeight()](#getHeight--) | 画像の高さを返します。 |
| [getX()](#getX--) | 画像の X オフセットを返します。 |
| [getY()](#getY--) | 画像の Y オフセットを返します。 |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

画像データのコピーを返します。読み取り専用 byte[]。

**戻り値:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

画像のコピーを返します。読み取り専用 \#getImage.getImage。

**戻り値:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```

ISvgImage オブジェクトを取得または設定します [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

この値は、この画像が SVG から作成されたことを示します。

**戻り値:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```

ISvgImage オブジェクトを取得または設定します [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

この値は、この画像が SVG から作成されたことを示します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```

画像データを置き換えます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newImageData | byte[] | 新しい画像のデータ。 |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```

画像を置き換えます。注意: 画像がメタファイルの場合、ラスタライズされます。代わりに replaceImage(byte[]) を使用してください。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | 新しい画像。 |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```

画像を置き換えます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | 新しい IPPImage。 |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

画像の MIME タイプを返します（\#getBinaryData.getBinaryData でエンコード）。読み取り専用 String。

**戻り値:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

画像の幅を返します。読み取り専用 int。

**戻り値:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

画像の高さを返します。読み取り専用 int。

**戻り値:**
int
### getX() {#getX--}
```
public abstract int getX()
```

画像の X オフセットを返します。読み取り専用 int。

**戻り値:**
int
### getY() {#getY--}
```
public abstract int getY()
```

画像の Y オフセットを返します。読み取り専用 int。

**戻り値:**
int