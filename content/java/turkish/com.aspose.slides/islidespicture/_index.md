---
title: ISlidesPicture
second_title: Aspose.Slides for Java API Referansı
description: Bir sunumdaki resmi temsil eder.
type: docs
url: /tr/com.aspose.slides/islidespicture/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

Bir sunumdaki resmi temsil eder.
## Yöntemler

| Metod | Açıklama |
| --- | --- |
| [getImage()](#getImage--) | Gömülü resmi döndürür veya ayarlar. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Gömülü resmi döndürür veya ayarlar. |
| [getLinkPathLong()](#getLinkPathLong--) | Bağlantılı görüntünün URL'sini döndürür veya ayarlar. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Bağlantılı görüntünün URL'sini döndürür veya ayarlar. |
| [getImageTransform()](#getImageTransform--) | Görüntü dönüşüm etkileri koleksiyonunu döndürür. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

Gömülü resmi döndürür veya ayarlar. Okunur/Yazılabilir [IPPImage](../../com.aspose.slides/ippimage).

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```

Gömülü resmi döndürür veya ayarlar. Okunur/Yazılabilir [IPPImage](../../com.aspose.slides/ippimage).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Bağlantılı görüntünün URL'sini döndürür veya ayarlar. Okunur/Yazılabilir String.

**Döndürür:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Bağlantılı görüntünün URL'sini döndürür veya ayarlar. Okunur/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```

Görüntü dönüşüm etkileri koleksiyonunu döndürür. Yalnızca okunur [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Döndürür:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)