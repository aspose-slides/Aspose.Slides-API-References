---
title: IPictureFillFormatEffectiveData
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 画像塗りつぶしのプロパティを含む不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/ipicturefillformateffectivedata/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

画像塗りつぶしのプロパティを含む不変オブジェクトです。

--------------------

このインターフェイスは [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) の一部として使用されます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDpi()](#getDpi--) | 画像を塗りつぶす際に使用される dpi を返します。 |
| [getPictureFillMode()](#getPictureFillMode--) | 画像塗りつぶしモードを返します。 |
| [getPicture()](#getPicture--) | 画像を返します。 |
| [getCropLeft()](#getCropLeft--) | 画像の左側から切り取られる実際の画像幅のパーセント数を返します。 |
| [getCropTop()](#getCropTop--) | 画像の上部から切り取られる実際の画像高さのパーセント数を返します。 |
| [getCropRight()](#getCropRight--) | 画像の右側から切り取られる実際の画像幅のパーセント数を返します。 |
| [getCropBottom()](#getCropBottom--) | 画像の下部から切り取られる実際の画像高さのパーセント数を返します。 |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

画像を塗りつぶす際に使用される dpi を返します。読み取り専用 int。

**戻り値:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

画像塗りつぶしモードを返します。読み取り専用 [PictureFillMode](../../com.aspose.slides/picturefillmode)。

**戻り値:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

画像を返します。読み取り専用 [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)。

**戻り値:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

画像の左側から切り取られる実際の画像幅のパーセント数を返します。読み取り専用 float。

**戻り値:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

画像の上部から切り取られる実際の画像高さのパーセント数を返します。読み取り専用 float。

**戻り値:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

画像の右側から切り取られる実際の画像幅のパーセント数を返します。読み取り専用 float。

**戻り値:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

画像の下部から切り取られる実際の画像高さのパーセント数を返します。読み取り専用 float。

**戻り値:**
float