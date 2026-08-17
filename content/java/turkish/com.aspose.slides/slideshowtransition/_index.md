---
title: SlideShowTransition
second_title: Aspose.Slides için Java API Referansı
description: Slayt gösterisi geçişini temsil eder.
type: docs
url: /tr/com.aspose.slides/slideshowtransition/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

Slayt gösterisi geçişini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSound()](#getSound--) | Gömülü ses verisini döndürür veya ayarlar. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Gömülü ses verisini döndürür veya ayarlar. |
| [getSoundMode()](#getSoundMode--) | Slayt geçişi için ses modunu ayarlar veya döndürür. |
| [setSoundMode(int value)](#setSoundMode-int-) | Slayt geçişi için ses modunu ayarlar veya döndürür. |
| [getSoundLoop()](#getSoundLoop--) | Bu öznitelik, sesin slayt gösterisinde bir sonraki ses olayına kadar döngüye girip girmeyeceğini belirler. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Bu öznitelik, sesin slayt gösterisinde bir sonraki ses olayına kadar döngüye girip girmeyeceğini belirler. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Bir fare tıklamasının slaytı ilerletip ilerletmeyeceğini belirtir. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Bir fare tıklamasının slaytı ilerletip ilerletmeyeceğini belirtir. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Bu öznitelik, slayt gösterisinin belirli bir süreden sonra sonraki slayta geçip geçmeyeceğini belirler. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Bu öznitelik, slayt gösterisinin belirli bir süreden sonra sonraki slayta geçip geçmeyeceğini belirler. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Geçişin başlaması gereken süreyi, milisaniye cinsinden belirtir. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Geçişin başlaması gereken süreyi, milisaniye cinsinden belirtir. |
| [getSpeed()](#getSpeed--) | Mevcut slayttan sonraki slayta geçişte kullanılacak geçiş hızını belirtir. |
| [setSpeed(int value)](#setSpeed-int-) | Mevcut slayttan sonraki slayta geçişte kullanılacak geçiş hızını belirtir. |
| [getValue()](#getValue--) | Slayt gösterisi geçiş değeri. |
| [getType()](#getType--) | Geçiş türü. |
| [setType(int value)](#setType-int-) | Geçiş türü. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Bu sesin yerleşik bir ses olup olmadığını belirtir. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Bu sesin yerleşik bir ses olup olmadığını belirtir. |
| [getSoundName()](#getSoundName--) | Geçiş sesinin insanlar tarafından okunabilir adını belirtir. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Geçiş sesinin insanlar tarafından okunabilir adını belirtir. |
| [getDuration()](#getDuration--) | Slayt geçiş efekti süresini milisaniye cinsinden alır veya ayarlar. |
| [setDuration(int value)](#setDuration-int-) | Slayt geçiş efekti süresini milisaniye cinsinden alır veya ayarlar. |
| [equals(Object obj)](#equals-java.lang.Object-) | İki SlideShowTransition örneğinin eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tip için, hash tabloları gibi veri yapılarına ve hashleme algoritmalarına uygun bir hash fonksiyonu sağlar. |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Gömülü ses verisini döndürür veya ayarlar. Okunur/Yazılır [IAudio](../../com.aspose.slides/iaudio).

**Döndürür:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Gömülü ses verisini döndürür veya ayarlar. Okunur/Yazılır [IAudio](../../com.aspose.slides/iaudio).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

Slayt geçişi için ses modunu ayarlar veya döndürür. Okunur/Yazılır [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Döndürür:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

Slayt geçişi için ses modunu ayarlar veya döndürür. Okunur/Yazılır [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

Bu öznitelik, sesin slayt gösterisinde bir sonraki ses olayına kadar döngüye girip girmeyeceğini belirler. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Bu öznitelik, sesin slayt gösterisinde bir sonraki ses olayına kadar döngüye girip girmeyeceğini belirler. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Bir fare tıklamasının slaytı ilerletip ilerletmeyeceğini belirtir. Bu öznitelik belirtilmezse true değeri varsayılır. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Bir fare tıklamasının slaytı ilerletip ilerletmeyeceğini belirtir. Bu öznitelik belirtilmezse true değeri varsayılır. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

Bu öznitelik, slayt gösterisinin belirli bir süreden sonra sonraki slayta geçip geçmeyeceğini belirler. Okunur/Yazılır boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // İlk slayt geçişini alın
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Advance Slide After bayrağının işaretli olup olmadığını kontrol edin
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Advance Slide After Time değerini alın
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

Bu öznitelik, slayt gösterisinin belirli bir süreden sonra sonraki slayta geçip geçmeyeceğini belirler. Okunur/Yazılır boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // İlk slayt geçişini al
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Advance Slide After bayrağının işaretli olup olmadığını kontrol edin
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

Geçişin başlaması gereken süreyi, milisaniye cinsinden belirtir. Bu ayar advClick özniteliğiyle birlikte kullanılabilir. Bu öznitelik belirtilmezse otomatik ilerlemenin gerçekleşmeyeceği varsayılır. Okunur/Yazılır long.

**Döndürür:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Geçişin başlaması gereken süreyi, milisaniye cinsinden belirtir. Bu ayar advClick özniteliğiyle birlikte kullanılabilir. Bu öznitelik belirtilmezse otomatik ilerlemenin gerçekleşmeyeceği varsayılır. Okunur/Yazılır long.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Mevcut slayttan sonraki slayta geçişte kullanılacak geçiş hızını belirtir. Okunur/Yazılır [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Döndürür:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Mevcut slayttan sonraki slayta geçişte kullanılacak geçiş hızını belirtir. Okunur/Yazılır [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

Slayt gösterisi geçiş değeri. Sadece-okunur [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Döndürür:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public final int getType()
```

Geçiş türü. Okunur/Yazılır [TransitionType](../../com.aspose.slides/transitiontype).

**Döndürür:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Geçiş türü. Okunur/Yazılır [TransitionType](../../com.aspose.slides/transitiontype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

Bu sesin yerleşik bir ses olup olmadığını belirtir. Bu öznitelik true olarak ayarlanırsa, oluşturucu uygulama bu sesin listesinde belirtilen ad özniteliğini kontrol eder ve gerektiğinde özel bir ad ya da arayüz sunabilir. Okunur-yazılır boolean.

**Döndürür:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Bu sesin yerleşik bir ses olup olmadığını belirtir. Bu öznitelik true olarak ayarlanırsa, oluşturucu uygulama bu sesin listesinde belirtilen ad özniteliğini kontrol eder ve gerektiğinde özel bir ad ya da arayüz sunabilir. Okunur-yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Geçiş sesinin insanlar tarafından okunabilir adını belirtir. Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) özelliği ses adını almak veya ayarlamak için atanmalıdır. Okunur-yazılır String.

**Döndürür:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Geçiş sesinin insanlar tarafından okunabilir adını belirtir. Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) özelliği ses adını almak veya ayarlamak için atanmalıdır. Okunur-yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

Slayt geçiş efekti süresini milisaniye cinsinden alır veya ayarlar. Okunur/Yazılır int.

--------------------

PresentationML şemasındaki p:transition öğesinin p14:dur özniteliğine karşılık gelir. Ayarlanmamışsa, süre otomatik olarak \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) özelliği ve geçiş türüne göre belirlenir.

**Döndürür:**
int

### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Slayt geçiş efekti süresini milisaniye cinsinden alır veya ayarlar. Okunur/Yazılır int.

--------------------

PresentationML şemasındaki p:transition öğesinin p14:dur özniteliğine karşılık gelir. Ayarlanmamışsa, süre otomatik olarak \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) özelliği ve geçiş türüne göre belirlenir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

İki SlideShowTransition örneğinin eşit olup olmadığını belirler. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak SlideShowTransition. |

**Döndürür:**
boolean -  **true**  eğer belirtilen SlideShowTransition mevcut SlideShowTransition ile eşitse; aksi takdirde **false** .

### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tip için, hash tabloları gibi veri yapılarına ve hashleme algoritmalarına uygun bir hash fonksiyonu sağlar.

**Döndürür:**
int - 23454

--------------------

Derleyiciyi mutlu etmek için ezilmiştir. Nesne değiştirilebilir olduğu için her zaman sabit bir değer döndürür.