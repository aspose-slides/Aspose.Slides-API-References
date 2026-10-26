---
title: PPImage
second_title: Aspose.Slides の Java API リファレンス
description: プレゼンテーション内の画像を表します。
type: docs
url: /ja/com.aspose.slides/ppimage/
---
**継承:**
java.lang.Object

**実装されたインターフェイス:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

プレゼンテーション内の画像を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | 画像のデータのコピーを返します。 |
| [getImage()](#getImage--) | 画像のコピーを返します。 |
| [getSvgImage()](#getSvgImage--) | ISvgImageオブジェクト [ISvgImage](../../com.aspose.slides/isvgimage) を取得または設定します。 |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | ISvgImageオブジェクト [ISvgImage](../../com.aspose.slides/isvgimage) を取得または設定します。 |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | 画像データを置き換えます。 |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | 画像データを置き換えます。 |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | 画像データを置き換えます。 |
| [getContentType()](#getContentType--) | BinaryData (\#getBinaryData.getBinaryData) でエンコードされた画像のMIMEタイプを返します。 |
| [getWidth()](#getWidth--) | 画像の幅を返します。 |
| [getHeight()](#getHeight--) | 画像の高さを返します。 |
| [getX()](#getX--) | 画像のXオフセットを返します。 |
| [getY()](#getY--) | 画像のYオフセットを返します。 |
| [hashCode()](#hashCode--) | 画像のハッシュコードを返します。 |
| [dispose()](#dispose--) | オブジェクトを破棄します。 |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


画像のデータのコピーを返します。読み取り専用  byte[] 。

**返り値:**
byte[] - バイト配列
### getImage() {#getImage--}
```
public final IImage getImage()
```


画像のコピーを返します。読み取り専用 [IImage](../../com.aspose.slides/iimage)。

**返り値:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```


ISvgImageオブジェクト [ISvgImage](../../com.aspose.slides/isvgimage) を取得または設定します。

--------------------

この値は、この画像が SVG から作成されたことを示します。

**返り値:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```


ISvgImageオブジェクト [ISvgImage](../../com.aspose.slides/isvgimage) を取得または設定します。

--------------------

この値は、この画像が SVG から作成されたことを示します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```


画像データを置き換えます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newImageData | byte[] | 新しい画像のデータ。 |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```


画像データを置き換えます。注意: Image がメタファイルの場合、ラスタライズされます。代わりに ReplaceImage(byte[]) を使用してください

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | 新しい画像。 |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```


画像データを置き換えます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | 新しい IPPImage。 |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


BinaryData (\#getBinaryData.getBinaryData) でエンコードされた画像のMIMEタイプを返します。読み取り専用 String。

**返り値:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```


画像の幅を返します。読み取り専用  int 。

**返り値:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


画像の高さを返します。読み取り専用  int 。

**返り値:**
int
### getX() {#getX--}
```
public final int getX()
```


画像のXオフセットを返します。読み取り専用  int 。

**返り値:**
int
### getY() {#getY--}
```
public final int getY()
```


画像のYオフセットを返します。読み取り専用  int 。

**返り値:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


画像のハッシュコードを返します。

**返り値:**
int - ハッシュコード。
### dispose() {#dispose--}
```
public final void dispose()
```


オブジェクトを破棄します。