---
title: IPictureFrame
second_title: Aspose.Slides for Android Java API Referansı
description: İçinde bir resim bulunan bir çerçeveyi temsil eder.
type: docs
url: /tr/com.aspose.slides/ipictureframe/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

İçinde bir resim bulunan bir çerçeveyi temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | PictureFrame'in kilitlerini döndürür. |
| [getPictureFormat()](#getPictureFormat--) | Resim çerçevesi için PictureFillFormat nesnesini döndürür. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Resim çerçevesinin yüksekliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Resim çerçevesinin yüksekliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Resim çerçevesinin genişliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Resim çerçevesinin genişliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```

PictureFrame'in kilitlerini döndürür. Salt okunur [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Döndürür:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```

Resim çerçevesi için PictureFillFormat nesnesini döndürür. Salt okunur [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Döndürür:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```

Resim çerçevesinin yüksekliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. Değer 1.0, %100'e karşılık gelir. Okunabilir/yazılabilir float.

**Döndürür:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```

Resim çerçevesinin yüksekliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. Değer 1.0, %100'e karşılık gelir. Okunabilir/yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```

Resim çerçevesinin genişliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. Değer 1.0, %100'e karşılık gelir. Okunabilir/yazılabilir float.

**Döndürür:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```

Resim çerçevesinin genişliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. Değer 1.0, %100'e karşılık gelir. Okunabilir/yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |