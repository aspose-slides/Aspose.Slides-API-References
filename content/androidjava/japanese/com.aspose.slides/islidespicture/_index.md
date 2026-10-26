---
title: ISlidesPicture
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: プレゼンテーション内の画像を表します。
type: docs
url: /ja/com.aspose.slides/islidespicture/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

プレゼンテーション内の画像を表します。
## メソッド

| Method | Description |
| --- | --- |
| [getImage()](#getImage--) | 埋め込み画像を取得または設定します。 |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | 埋め込み画像を取得または設定します。 |
| [getLinkPathLong()](#getLinkPathLong--) | リンクされた画像の URL を取得または設定します。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | リンクされた画像の URL を取得または設定します。 |
| [getImageTransform()](#getImageTransform--) | 画像変換エフェクトのコレクションを取得します。 |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

埋め込み画像を取得または設定します。読み取り/書き込み [IPPImage](../../com.aspose.slides/ippimage)。

**戻り値:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```

埋め込み画像を取得または設定します。読み取り/書き込み [IPPImage](../../com.aspose.slides/ippimage)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

リンクされた画像の URL を取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

リンクされた画像の URL を取得または設定します。読み取り/書き込み String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```

画像変換エフェクトのコレクションを取得します。読み取り専用 [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)。

**戻り値:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)