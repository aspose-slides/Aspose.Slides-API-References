---
title: ITextAnimation
second_title: Aspose.Slides for Android via Java API Reference
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
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Mevcut dizinin sonuna grup metin animasyonlarının sonuna yeni bir etki ekler. |
| [getBuildType()](#getBuildType--) | Derleme türü listesi (örnek: |
| [setBuildType(int value)](#setBuildType-int-) | Derleme türü listesi (örnek: |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Grup ile ya da olmadan bağlanmış şekil etkisi (null) Okunur/Yazılabilir [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Grup ile ya da olmadan bağlanmış şekil etkisi (null) Okunur/Yazılabilir [IEffect](../../com.aspose.slides/ieffect). |

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

Mevcut dizinin sonuna grup metin animasyonlarının sonuna yeni bir etki ekler. Yalnızca metin paragraf sayısı bu grubun efekt sayısına eşit veya daha fazla olduğunda geçerlidir!

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| effectType | int | Bir animasyon efektinin türü [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animasyon efektinin alt türleri [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Efektin tetikleme türü [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Dönüş Değeri:**
[IEffect](../../com.aspose.slides/ieffect) - Yeni etki nesnesi [IEffect](../../com.aspose.slides/ieffect)

### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

Metin animasyonunun derleme türü listesi (örnek: Paragraph 1,2,3, All at Once). Okunur/Yazılabilir \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Dönüş Değeri:**
int

### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

Metin animasyonunun derleme türü listesi (örnek: Paragraph 1,2,3, All at Once). Okunur/Yazılabilir \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

Grup ile ya da olmadan bağlanmış şekil etkisi (null) Okunur/Yazılabilir [IEffect](../../com.aspose.slides/ieffect).

**Dönüş Değeri:**
[IEffect](../../com.aspose.slides/ieffect)

### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

Grup ile ya da olmadan bağlanmış şekil etkisi (null) Okunur/Yazılabilir [IEffect](../../com.aspose.slides/ieffect).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |