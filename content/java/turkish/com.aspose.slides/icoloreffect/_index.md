---
title: IColorEffect
second_title: Aspose.Slides için Java API Referansı
description: Bir animasyon davranışı için renk etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/icoloreffect/
---
**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

Bir animasyon davranışı için renk efekti temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFrom()](#getFrom--) | Bu değer, davranışın başlangıç rengini belirtmek için kullanılır. |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | Bu değer, davranışın başlangıç rengini belirtmek için kullanılır. |
| [getTo()](#getTo--) | Animasyon renk değişimi için ortaya çıkan rengi açıklar. |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | Animasyon renk değişimi için ortaya çıkan rengi açıklar. |
| [getBy()](#getBy--) | Renk animasyonu için göreceli ofset değerini açıklar. |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | Renk animasyonu için göreceli ofset değerini açıklar. |
| [getColorSpace()](#getColorSpace--) | Davranışın renk uzayını temsil eder. |
| [setColorSpace(int value)](#setColorSpace-int-) | Davranışın renk uzayını temsil eder. |
| [getDirection()](#getDirection--) | Renk çarkı etrafında tonun hangi yönde döneceğini belirler. |
| [setDirection(int value)](#setDirection-int-) | Renk çarkı etrafında tonun hangi yönde döneceğini belirler. |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```

Bu değer, davranışın başlangıç rengini belirtmek için kullanılır. Okuma/Yazma [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```

Bu değer, davranışın başlangıç rengini belirtmek için kullanılır. Okuma/Yazma [IColorFormat](../../com.aspose.slides/icolorformat).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```

Animasyon renk değişimi için ortaya çıkan rengi açıklar. Okuma/Yazma [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```

Animasyon renk değişimi için ortaya çıkan rengi açıklar. Okuma/Yazma [IColorFormat](../../com.aspose.slides/icolorformat).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```

Renk animasyonu için göreceli ofset değerini açıklar. Okuma/Yazma [IColorOffset](../../com.aspose.slides/icoloroffset).

**Döndürür:**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```

Renk animasyonu için göreceli ofset değerini açıklar. Okuma/Yazma [IColorOffset](../../com.aspose.slides/icoloroffset).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |

### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```

Davranışın renk uzayını temsil eder. Okuma/Yazma [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Döndürür:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```

Davranışın renk uzayını temsil eder. Okuma/Yazma [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Renk çarkı etrafında tonun hangi yönde döneceğini belirler. Okuma/Yazma [ColorDirection](../../com.aspose.slides/colordirection).

**Döndürür:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Renk çarkı etrafında tonun hangi yönde döneceğini belirler. Okuma/Yazma [ColorDirection](../../com.aspose.slides/colordirection).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |