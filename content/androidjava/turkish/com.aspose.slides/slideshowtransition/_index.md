---
title: SlideShowTransition
second_title: Aspose.Slides for Android için Java API Referansı
description: Slayt gösterisi geçişini temsil eder.
type: docs
url: /tr/com.aspose.slides/slideshowtransition/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

Slayt gösterisi geçişini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSound()](#getSound--) | Gömülü ses verilerini döndürür veya ayarlar. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Gömülü ses verilerini döndürür veya ayarlar. |
| [getSoundMode()](#getSoundMode--) | Slayt geçişi için ses modunu ayarlar veya döndürür. |
| [setSoundMode(int value)](#setSoundMode-int-) | Slayt geçişi için ses modunu ayarlar veya döndürür. |
| [getSoundLoop()](#getSoundLoop--) | Bu öznitelik, sesin slayt gösterisinde bir sonraki ses olayına kadar döngüye alınıp alınmayacağını belirtir. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Bu öznitelik, sesin slayt gösterisinde bir sonraki ses olayına kadar döngüye alınıp alınmayacağını belirtir. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Bir fare tıklamasının slaytı ilerletip ilerletmeyeceğini belirtir. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Bir fare tıklamasının slaytı ilerletip ilerletmeyeceğini belirtir. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Bu öznitelik, slayt gösterisinin belirli bir süreden sonra bir sonraki slayta geçip geçmeyeceğini belirtir. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Bu öznitelik, slayt gösterisinin belirli bir süreden sonra bir sonraki slayta geçip geçmeyeceğini belirtir. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Geçişin başlaması gereken zamanı milisaniye cinsinden belirtir. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Geçişin başlaması gereken zamanı milisaniye cinsinden belirtir. |
| [getSpeed()](#getSpeed--) | Mevcut slayttan bir sonraki slayta geçişte kullanılacak geçiş hızını belirtir. |
| [setSpeed(int value)](#setSpeed-int-) | Mevcut slayttan bir sonraki slayta geçişte kullanılacak geçiş hızını belirtir. |
| [getValue()](#getValue--) | Slayt gösterisi geçiş değeri. |
| [getType()](#getType--) | Geçiş türü. |
| [setType(int value)](#setType-int-) | Geçiş türü. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Bu sesin yerleşik bir ses olup olmadığını belirtir. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Bu sesin yerleşik bir ses olup olmadığını belirtir. |
| [getSoundName()](#getSoundName--) | Geçiş sesinin insanlar tarafından okunabilir bir adını belirtir. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Geçiş sesinin insanlar tarafından okunabilir bir adını belirtir. |
| [getDuration()](#getDuration--) | Slayt geçişi etkisinin süresini milisaniye cinsinden alır veya ayarlar. |
| [setDuration(int value)](#setDuration-int-) | Slayt geçişi etkisinin süresini milisaniye cinsinden alır veya ayarlar. |
| [equals(Object obj)](#equals-java.lang.Object-) | İki SlideShowTransition örneğinin eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tip için bir hash işlevi görevi görür, hashing algoritmaları ve hash tablosu gibi veri yapılarında kullanılmak üzere uygundur. |
### getSound() {#getSound--}
```
public final IAudio getSound()
```

Gömülü ses verilerini döndürür veya ayarlar. Okunur/yazılır [IAudio](../../com.aspose.slides/iaudio).

**Döndürür:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Gömülü ses verilerini döndürür veya ayarlar. Okunur/yazılır [IAudio](../../com.aspose.slides/iaudio).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

Slayt geçişi için ses modunu ayarlar veya döndürür. Okunur/yazılır [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Döndürür:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

Slayt geçişi için ses modunu ayarlar veya döndürür. Okunur/yazılır [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

Bu öznitelik, sesin slayt gösterisinde bir sonraki ses olayına kadar döngüye alınıp alınmayacağını belirtir. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Bu öznitelik, sesin slayt gösterisinde bir sonraki ses olayına kadar döngüye alınıp alınmayacağını belirtir. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Bir fare tıklamasının slaytı ilerletip ilerletmeyeceğini belirtir. Bu öznitelik belirtilmemişse true değeri varsayılır. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Bir fare tıklamasının slaytı ilerletip ilerletmeyeceğini belirtir. Bu öznitelik belirtilmemişse true değeri varsayılır. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

Bu öznitelik, slayt gösterisinin belirli bir süreden sonra bir sonraki slayta geçip geçmeyeceğini belirtir. Okunur/yazılır boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // İlk slayt geçişini al
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Advance Slide After bayrağının işaretli olup olmadığını kontrol et
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Advance Slide After Time değerini al
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public final void setAdvanceAfter(boolean value)
```

Bu öznitelik, slayt gösterisinin belirli bir süreden sonra bir sonraki slayta geçip geçmeyeceğini belirtir. Okunur/yazılır boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // İlk slayt geçişini al
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Advance Slide After bayrağının işaretli olup olmadığını kontrol et
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Advance Slide After Time değerini al
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public final long getAdvanceAfterTime()
```

Geçişin başlaması gereken zamanı milisaniye cinsinden belirtir. Bu ayar, advClick özniteliğiyle birlikte kullanılabilir. Bu öznitelik belirtilmemişse otomatik ilerlemenin gerçekleşmeyeceği varsayılır. Okunur/yazılır long.

**Döndürür:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Geçişin başlaması gereken zamanı milisaniye cinsinden belirtir. Bu ayar, advClick özniteliğiyle birlikte kullanılabilir. Bu öznitelik belirtilmemişse otomatik ilerlemenin gerçekleşmeyeceği varsayılır. Okunur/yazılır long.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |
### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Mevcut slayttan bir sonraki slayta geçişte kullanılacak geçiş hızını belirtir. Okunur/yazılır [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Döndürür:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Mevcut slayttan bir sonraki slayta geçişte kullanılacak geçiş hızını belirtir. Okunur/yazılır [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

Slayt gösterisi geçiş değeri. Yalnızca okunur [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Döndürür:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public final int getType()
```

Geçiş türü. Okunur/yazılır [TransitionType](../../com.aspose.slides/transitiontype).

**Döndürür:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Geçiş türü. Okunur/yazılır [TransitionType](../../com.aspose.slides/transitiontype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

Bu sesin yerleşik bir ses olup olmadığını belirtir. Bu öznitelik true olarak ayarlanırsa, oluşturucu uygulama bu sesin yerleşik sesler listesinde belirtilen name özniteliğini kontrol eder ve gerekirse özel bir ad veya UI sunar. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Bu sesin yerleşik bir ses olup olmadığını belirtir. Bu öznitelik true olarak ayarlanırsa, oluşturucu uygulama bu sesin yerleşik sesler listesinde belirtilen name özniteliğini kontrol eder ve gerekirse özel bir ad veya UI sunar. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Geçiş sesinin insanlar tarafından okunabilir bir adını belirtir. Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) özelliği ses adını almak veya ayarlamak için atanmalıdır. Okunur/yazılır String.

**Döndürür:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Geçiş sesinin insanlar tarafından okunabilir bir adını belirtir. Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) özelliği ses adını almak veya ayarlamak için atanmalıdır. Okunur/yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getDuration() {#getDuration--}
```
public final int getDuration()
```

Slayt geçişi etkisinin süresini milisaniye cinsinden alır veya ayarlar. Okunur/yazılır int.

--------------------

PresentationML şemasındaki p:transition öğesinin p14:dur özniteliğine karşılık gelir. Ayarlanmamışsa, süre \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) özelliği ve geçiş türüne göre otomatik olarak belirlenir.

**Döndürür:**
int
### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Slayt geçişi etkisinin süresini milisaniye cinsinden alır veya ayarlar. Okunur/yazılır int.

--------------------

PresentationML şemasındaki p:transition öğesinin p14:dur özniteliğine karşılık gelir. Ayarlanmamışsa, süre \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) özelliği ve geçiş türüne göre otomatik olarak belirlenir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

İki SlideShowTransition örneğinin eşit olup olmadığını belirler. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Mevcut SlideShowTransition ile karşılaştırılacak SlideShowTransition. |

**Döndürür:**
boolean -  **true**  belirtilen SlideShowTransition mevcut SlideShowTransition ile eşitse; aksi halde  **false** .
### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tip için hash işlevi olarak hizmet eder, hashing algoritmaları ve hash tablosu gibi veri yapılarında kullanılmak üzere uygundur.

**Döndürür:**
int - 23454

--------------------

Derleyiciyi mutlu etmek için geçersiz kılınmıştır. Nesne değiştirilebilir olduğundan her zaman sabit bir değer döndürür.