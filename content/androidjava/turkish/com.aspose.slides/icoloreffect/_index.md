---
title: IColorEffect
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir animasyon davranışı için renk etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/icoloreffect/
---
**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

Bir animasyon davranışı için renk etkisini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFrom()](#getFrom--) | Bu değer, davranışın başlangıç rengini belirtmek için kullanılır. |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | Bu değer, davranışın başlangıç rengini belirtmek için kullanılır. |
| [getTo()](#getTo--) | Animasyon renk değişikliği için ortaya çıkan rengi açıklar. |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | Animasyon renk değişikliği için ortaya çıkan rengi açıklar. |
| [getBy()](#getBy--) | Renk animasyonu için göreceli offset değerini açıklar. |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | Renk animasyonu için göreceli offset değerini açıklar. |
| [getColorSpace()](#getColorSpace--) | Davranışın renk uzayını temsil eder. |
| [setColorSpace(int value)](#setColorSpace-int-) | Davranışın renk uzayını temsil eder. |
| [getDirection()](#getDirection--) | Renk tonunun renk çarkı etrafında hangi yönde döneceğini belirtir. |
| [setDirection(int value)](#setDirection-int-) | Renk tonunun renk çarkı etrafında hangi yönde döneceğini belirtir. |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```

Bu değer, davranışın başlangıç rengini belirtmek için kullanılır. Okuma/yazma [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```

Bu değer, davranışın başlangıç rengini belirtmek için kullanılır. Okuma/yazma [IColorFormat](../../com.aspose.slides/icolorformat).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```

Animasyon renk değişikliği için ortaya çıkan rengi açıklar. Okuma/yazma [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```

Animasyon renk değişikliği için ortaya çıkan rengi açıklar. Okuma/yazma [IColorFormat](../../com.aspose.slides/icolorformat).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```

Renk animasyonu için göreceli offset değerini açıklar. Okuma/yazma [IColorOffset](../../com.aspose.slides/icoloroffset).

**Döndürür:**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```

Renk animasyonu için göreceli offset değerini açıklar. Okuma/yazma [IColorOffset](../../com.aspose.slides/icoloroffset).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |

### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```

Davranışın renk uzayını temsil eder. Okuma/yazma [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Döndürür:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```

Davranışın renk uzayını temsil eder. Okuma/yazma [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Renk tonunun renk çarkı etrafında hangi yönde döneceğini belirtir. Okuma/yazma [ColorDirection](../../com.aspose.slides/colordirection).

**Döndürür:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Renk tonunun renk çarkı etrafında hangi yönde döneceğini belirtir. Okuma/yazma [ColorDirection](../../com.aspose.slides/colordirection).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |