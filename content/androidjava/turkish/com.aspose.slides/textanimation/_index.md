---
title: TextAnimation
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Metin animasyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/textanimation/
---
**Kalıtım:**
java.lang.Object

**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

Metin animasyonunu temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Mevcut dizinin sonuna yeni etki ekler ve grup metin animasyonlarının sonuna ekler. |
| [getBuildType()](#getBuildType--) | Yapı tipi listesi (örnek olarak |
| [setBuildType(int value)](#setBuildType-int-) | Yapı tipi listesi (örnek olarak |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Grup ile birlikte ya da olmadan bağlanmış şekil etkisi (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Grup ile birlikte ya da olmadan bağlanmış şekil etkisi (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```


### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```


Mevcut dizinin sonuna yeni etki ekler ve grup metin animasyonlarının sonuna ekler. Yalnızca metin paragraf sayısı bu grubun etki sayısına eşit ya da daha fazla ise geçerlidir!

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
public final int getBuildType()
```


Metin animasyonunun yapı tipi listesi (örnek: Paragraf 1,2,3, Hepsi Birden). Okunur/Yazılır [BuildType](../../com.aspose.slides/buildtype).

**Dönüş Değeri:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```


Metin animasyonunun yapı tipi listesi (örnek: Paragraf 1,2,3, Hepsi Birden). Okunur/Yazılır [BuildType](../../com.aspose.slides/buildtype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```


Grup ile birlikte ya da olmadan bağlanmış şekil etkisi (null). Okunur/Yazılır [IEffect](../../com.aspose.slides/ieffect).

**Dönüş Değeri:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```


Grup ile birlikte ya da olmadan bağlanmış şekil etkisi (null). Okunur/Yazılır [IEffect](../../com.aspose.slides/ieffect).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |