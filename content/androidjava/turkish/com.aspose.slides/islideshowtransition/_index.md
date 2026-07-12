---
title: ISlideShowTransition
second_title: Aspose.Slides for Android via Java API Reference
description: Slayt gösterisi geçişini temsil eder.
type: docs
url: /tr/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

Slayt gösterisi geçişini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSound()](#getSound--) | Gömülü ses verisini döndürür veya ayarlar. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Gömülü ses verisini döndürür veya ayarlar. |
| [getSoundMode()](#getSoundMode--) | Slayt geçişi için ses modunu ayarlar veya döndürür. |
| [setSoundMode(int value)](#setSoundMode-int-) | Slayt geçişi için ses modunu ayarlar veya döndürür. |
| [getSoundLoop()](#getSoundLoop--) | Bu öznitelik, sesin slayt gösterisinde bir sonraki ses olayına kadar döngü yapıp yapmayacağını belirtir. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Bu öznitelik, sesin slayt gösterisinde bir sonraki ses olayına kadar döngü yapıp yapmayacağını belirtir. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Bir fare tıklamasının slaytı ilerletip ilerletmeyeceğini belirtir. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Bir fare tıklamasının slaytı ilerletip ilerletmeyeceğini belirtir. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Bu öznitelik, slayt gösterisinin belirli bir süreden sonra bir sonraki slayta geçip geçmeyeceğini belirtir. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Bu öznitelik, slayt gösterisinin belirli bir süreden sonra bir sonraki slayta geçip geçmeyeceğini belirtir. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Geçişin başlaması gereken zamanı milisaniye cinsinden belirtir. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Geçişin başlaması gereken zamanı milisaniye cinsinden belirtir. |
| [getSpeed()](#getSpeed--) | Mevcut slayttan sonraki slayta geçişte kullanılacak geçiş hızını belirtir. |
| [setSpeed(int value)](#setSpeed-int-) | Mevcut slayttan sonraki slayta geçişte kullanılacak geçiş hızını belirtir. |
| [getValue()](#getValue--) | Slayt gösterisi geçiş değeri. |
| [getType()](#getType--) | Geçiş türü. |
| [setType(int value)](#setType-int-) | Geçiş türü. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Bu sesin yerleşik bir ses olup olmadığını belirtir. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Bu sesin yerleşik bir ses olup olmadığını belirtir. |
| [getSoundName()](#getSoundName--) | Geçiş sesinin insan tarafından okunabilir adını belirtir. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Geçiş sesinin insan tarafından okunabilir adını belirtir. |
| [getDuration()](#getDuration--) | Slayt geçiş etkisinin süresini milisaniye cinsinden alır veya ayarlar. |
| [setDuration(int value)](#setDuration-int-) | Slayt geçiş etkisinin süresini milisaniye cinsinden alır veya ayarlar. |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Gömülü ses verisini döndürür veya ayarlar. Okunabilir-yazılabilir [IAudio](../../com.aspose.slides/iaudio).

**Döndürür:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Gömülü ses verisini döndürür veya ayarlar. Okunabilir-yazılabilir [IAudio](../../com.aspose.slides/iaudio).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

Slayt geçişi için ses modunu ayarlar veya döndürür. Okunabilir-yazılabilir [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Döndürür:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

Slayt geçişi için ses modunu ayarlar veya döndürür. Okunabilir-yazılabilir [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

Bu öznitelik, sesin slayt gösterisinde bir sonraki ses olayına kadar döngü yapıp yapmayacağını belirtir. Okunabilir-yazılabilir boolean.

**Döndürür:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

Bu öznitelik, sesin slayt gösterisinde bir sonraki ses olayına kadar döngü yapıp yapmayacağını belirtir. Okunabilir-yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

Bir fare tıklamasının slaytı ilerletip ilerletmeyeceğini belirtir. Bu öznitelik belirtilmezse true varsayılır. Okunabilir-yazılabilir boolean.

**Döndürür:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

Bir fare tıklamasının slaytı ilerletip ilerletmeyeceğini belirtir. Bu öznitelik belirtilmezse true varsayılır. Okunabilir-yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

Bu öznitelik, slayt gösterisinin belirli bir süreden sonra bir sonraki slayta geçip geçmeyeceğini belirtir. Okunabilir/yazılabilir boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // İlk slayt geçişini al
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Advance Slide After bayrağının işaretlenip işaretlenmediğini kontrol et
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Advance Slide After Time değerini al
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:** boolean

### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```

Bu öznitelik, slayt gösterisinin belirli bir süreden sonra bir sonraki slayta geçip geçmeyeceğini belirtir. Okunabilir/yazılabilir boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // İlk slayt geçişini al
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Advance Slide After bayrağının işaretlenip işaretlenmediğini kontrol et
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
public abstract long getAdvanceAfterTime()
```

Geçişin başlaması gereken zamanı milisaniye cinsinden belirtir. Bu ayar, advClick özniteliğiyle birlikte kullanılabilir. Bu öznitelik belirtilmezse otomatik ilerleme gerçekleşmez. Okunabilir-yazılabilir long.

**Döndürür:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

Geçişin başlaması gereken zamanı milisaniye cinsinden belirtir. Bu ayar, advClick özniteliğiyle birlikte kullanılabilir. Bu öznitelik belirtilmezse otomatik ilerleme gerçekleşmez. Okunabilir-yazılabilir long.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

Mevcut slayttan sonraki slayta geçişte kullanılacak geçiş hızını belirtir. Okunabilir-yazılabilir [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Döndürür:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

Mevcut slayttan sonraki slayta geçişte kullanılacak geçiş hızını belirtir. Okunabilir-yazılabilir [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

Slayt gösterisi geçiş değeri. Salt-okunur [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Döndürür:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public abstract int getType()
```

Geçiş türü. Okunabilir-yazılabilir [TransitionType](../../com.aspose.slides/transitiontype).

**Döndürür:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Geçiş türü. Okunabilir-yazılabilir [TransitionType](../../com.aspose.slides/transitiontype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

Bu sesin yerleşik bir ses olup olmadığını belirtir. Bu öznitelik true olarak ayarlanırsa, uygulama bu sesin adını yerleşik ses listesinde kontrol eder ve gerektiğinde özel bir ad veya UI gösterir. Okunabilir-yazılabilir boolean.

**Döndürür:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

Bu sesin yerleşik bir ses olup olmadığını belirtir. Bu öznitelik true olarak ayarlanırsa, uygulama bu sesin adını yerleşik ses listesinde kontrol eder ve gerektiğinde özel bir ad veya UI gösterir. Okunabilir-yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

Geçiş sesinin insan tarafından okunabilir adını belirtir. Ses adını almak veya ayarlamak için \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) özelliği kullanılmalıdır. Okunabilir-yazılabilir String.

**Döndürür:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

Geçiş sesinin insan tarafından okunabilir adını belirtir. Ses adını almak veya ayarlamak için \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) özelliği kullanılmalıdır. Okunabilir-yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

Slayt geçiş etkisinin süresini milisaniye cinsinden alır veya ayarlar. Okunabilir/yazılabilir int.

--------------------

PresentationML şemasındaki p:transition öğesinin p14:dur özniteliğine karşılık gelir. Ayarlanmamışsa, süre \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) özelliği ve geçiş türüne göre otomatik belirlenir.

**Döndürür:**
int

### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

Slayt geçiş etkisinin süresini milisaniye cinsinden alır veya ayarlar. Okunabilir/yazılabilir int.

--------------------

PresentationML şemasındaki p:transition öğesinin p14:dur özniteliğine karşılık gelir. Ayarlanmamışsa, süre \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) özelliği ve geçiş türüne göre otomatically determined.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |