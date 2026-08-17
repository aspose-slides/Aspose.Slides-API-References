---
title: IFillOverlay
second_title: Aspose.Slides için Java API Referansı
description: Bir Fill Overlay etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/ifilloverlay/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Bir Fill Overlay efekti temsil eder. Fill overlay, bir nesne için ek bir doldurma belirlemek ve iki doldurmayı birleştirmek için kullanılabilir.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Dolgu biçimi. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```


FillBlendMode. Okuma/Yazma [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Döndürür:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```


FillBlendMode. Okuma/Yazma [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Dolgu biçimi. Sadece okuma [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)