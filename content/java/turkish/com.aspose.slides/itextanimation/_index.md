---
title: ITextAnimation
second_title: Aspose.Slides for Java API Reference
description: Metin animasyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Metin animasyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Mevcut dizinin sonuna yeni etki ekleyerek grup metin animasyonunun sonuna ekler. |
| [getBuildType()](#getBuildType--) | Oluşturma türünün listesi (örnek olarak |
| [setBuildType(int value)](#setBuildType-int-) | Oluşturma türünün listesi (örnek olarak |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Grup ile ya da olmadan bağlantılı şekil etkisi (null) Okunur/Yazılabilir [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Grup ile ya da olmadan bağlantılı şekil etkisi (null) Okunur/Yazılabilir [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```


Mevcut dizinin sonuna yeni etki ekleyerek grup metin animasyonunun sonuna ekler. Yalnızca, metin paragraflarının sayısı bu grubun etki sayısına eşit ya da daha fazla ise geçerlidir!

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| effectType | int | Bir animasyon etkisinin türü [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animasyon etkisinin alt türleri [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Etkinin tetikleme türü [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Dönüş Değeri:**
[IEffect](../../com.aspose.slides/ieffect) - Yeni etki nesnesi [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```


Metin animasyonunun oluşturma türünün listesi (örnek: Paragraf 1,2,3, Hepsi Birden). Okunur/Yazılabilir \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Dönüş Değeri:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```


Metin animasyonunun oluşturma türünün listesi (örnek: Paragraf 1,2,3, Hepsi Birden). Okunur/Yazılabilir \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```


Grup ile ya da olmadan bağlantılı şekil etkisi (null) Okunur/Yazılabilir [IEffect](../../com.aspose.slides/ieffect).

**Dönüş Değeri:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```


Grup ile ya da olmadan bağlantılı şekil etkisi (null) Okunur/Yazılabilir [IEffect](../../com.aspose.slides/ieffect).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |