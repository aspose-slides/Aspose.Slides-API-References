---
title: IFillOverlay
second_title: Java API Referansı ile Android için Aspose.Slides
description: Bir Fill Overlay etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/ifilloverlay/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Bir Fill Overlay etkisini temsil eder. Bir fill overlay, bir nesne için ek bir dolgu belirlemek ve iki dolguyu birleştirmek için kullanılabilir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Fill format. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```

FillBlendMode. Okunur/Yazılabilir [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Döndürür:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```

FillBlendMode. Okunur/Yazılabilir [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Fill format. Yalnızca okuma [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)