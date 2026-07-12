---
title: IPictureEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective picture properties.
type: docs
url: /ja/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

有効な画像プロパティを含む不変オブジェクトです。

--------------------

このインターフェイスは [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) と [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) の一部として使用されます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getImage()](#getImage--) | 埋め込み画像を返します。 |
| [getLinkPathLong()](#getLinkPathLong--) | リンクされた画像の URL を返します。 |
| [getImageTransform()](#getImageTransform--) | 画像変換エフェクトのコレクションを返します。 |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

埋め込み画像を返します。読み取り専用 [IPPImage](../../com.aspose.slides/ippimage)。

**戻り値:**  
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

リンクされた画像の URL を返します。読み取り専用 String。

**戻り値:**  
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```

画像変換エフェクトのコレクションを返します。読み取り専用 [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)。

**戻り値:**  
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)