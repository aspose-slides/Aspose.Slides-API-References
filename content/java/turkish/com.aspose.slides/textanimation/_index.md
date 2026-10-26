---
title: TextAnimation
second_title: Aspose.Slides for Java API Referansı
description: Metin animasyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/textanimation/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

Metin animasyonunu temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Add new effect to the end of current sequence to end of group text animations. |
| [getBuildType()](#getBuildType--) | List of build type (for exp. |
| [setBuildType(int value)](#setBuildType-int-) | List of build type (for exp. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Linked shape effect with group or not (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Linked shape effect with group or not (null). |

### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```

Mevcut dizinin sonuna yeni bir etki ekleyerek grup metin animasyonlarının sonuna ekler. Bu, metin paragraf sayısı bu grubun etki sayısına eşit veya daha fazla ise geçerlidir!

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| effectType | int | Animasyon etkisinin türü [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animasyon etkisinin alt türleri [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Etkinin tetikleme türü [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Döndürür:**
[IEffect](../../com.aspose.slides/ieffect) - Yeni etki nesnesi [IEffect](../../com.aspose.slides/ieffect)

### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```

Metin animasyonunun yapı tipi (örnek: Paragraf 1,2,3, Hepsi Birlikte) listesi. Okunabilir/Yazılabilir [BuildType](../../com.aspose.slides/buildtype).

**Döndürür:**
int

### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```

Metin animasyonunun yapı tipi (örnek: Paragraf 1,2,3, Hepsi Birlikte) listesi. Okunabilir/Yazılabilir [BuildType](../../com.aspose.slides/buildtype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```

Grup ile bağlantılı şekil etkisi veya olmayan (null). Okunabilir/Yazılabilir [IEffect](../../com.aspose.slides/ieffect).

**Döndürür:**
[IEffect](../../com.aspose.slides/ieffect)

### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```

Grup ile bağlantılı şekil etkisi veya olmayan (null). Okunabilir/Yazılabilir [IEffect](../../com.aspose.slides/ieffect).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |