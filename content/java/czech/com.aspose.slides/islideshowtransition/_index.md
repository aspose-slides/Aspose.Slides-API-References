---
title: ISlideShowTransition
second_title: Aspose.Slides for Java API Reference
description: Represents slide show transition.
type: docs
url: /cs/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

Reprezentuje přechod prezentace.
## Metody

| Metoda | Popis |
| --- | --- |
| [getSound()](#getSound--) | Vrací nebo nastavuje vložená audio data. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Vrací nebo nastavuje vložená audio data. |
| [getSoundMode()](#getSoundMode--) | Nastavuje nebo vrací režim zvuku pro přechod snímku. |
| [setSoundMode(int value)](#setSoundMode-int-) | Nastavuje nebo vrací režim zvuku pro přechod snímku. |
| [getSoundLoop()](#getSoundLoop--) | Tento atribut určuje, zda se zvuk bude opakovat, dokud nenastane další zvuková událost v prezentaci. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Tento atribut určuje, zda se zvuk bude opakovat, dokud nenastane další zvuková událost v prezentaci. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Určuje, zda kliknutí myší posune snímek dál, nebo ne. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Určuje, zda kliknutí myší posune snímek dál, nebo ne. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Tento atribut určuje, zda se prezentace přesune na další snímek po určité době. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Tento atribut určuje, zda se prezentace přesune na další snímek po určité době. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Určuje čas v milisekundách, po kterém by měl přechod začít. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Určuje čas v milisekundách, po kterém by měl přechod začít. |
| [getSpeed()](#getSpeed--) | Určuje rychlost přechodu, která se má použít při přechodu ze současného snímku na další. |
| [setSpeed(int value)](#setSpeed-int-) | Určuje rychlost přechodu, která se má použít při přechodu ze současného snímku na další. |
| [getValue()](#getValue--) | Hodnota přechodu prezentace. |
| [getType()](#getType--) | Typ přechodu. |
| [setType(int value)](#setType-int-) | Typ přechodu. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Určuje, zda je tento zvuk vestavěný. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Určuje, zda je tento zvuk vestavěný. |
| [getSoundName()](#getSoundName--) | Určuje člověkem čitelný název zvuku přechodu. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Určuje člověkem čitelný název zvuku přechodu. |
| [getDuration()](#getDuration--) | Vrací nebo nastavuje dobu trvání efektu přechodu snímku v milisekundách. |
| [setDuration(int value)](#setDuration-int-) | Vrací nebo nastavuje dobu trvání efektu přechodu snímku v milisekundách. |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


Vrací nebo nastavuje vložená audio data. Čtení a zápis [IAudio](../../com.aspose.slides/iaudio).

**Vrací:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```


Vrací nebo nastavuje vložená audio data. Čtení a zápis [IAudio](../../com.aspose.slides/iaudio).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```


Nastavuje nebo vrací režim zvuku pro přechod snímku. Čtení a zápis [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Vrací:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```


Nastavuje nebo vrací režim zvuku pro přechod snímku. Čtení a zápis [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```


Tento atribut určuje, zda se zvuk bude opakovat, dokud nenastane další zvuková událost v prezentaci. Čtení a zápis boolean.

**Vrací:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```


Tento atribut určuje, zda se zvuk bude opakovat, dokud nenastane další zvuková událost v prezentaci. Čtení a zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```


Určuje, zda kliknutí myší posune snímek dál, nebo ne. Pokud tento atribut není zadán, předpokládá se hodnota true. Čtení a zápis boolean.

**Vrací:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```


Určuje, zda kliknutí myší posune snímek dál, nebo ne. Pokud tento atribut není zadán, předpokládá se hodnota true. Čtení a zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```


Tento atribut určuje, zda se prezentace přesune na další snímek po určité době. Čtení/zápis boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Získat první přechod snímku
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Zkontrolovat, zda je nastaven příznak Advance Slide After
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Získat hodnotu Advance Slide After Time
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```


Tento atribut určuje, zda se prezentace přesune na další snímek po určité době. Čtení/zápis boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Získat první přechod snímku
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Zkontrolovat, zda je nastaven příznak Advance Slide After
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Získat hodnotu Advance Slide After Time
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```


Určuje čas v milisekundách, po kterém by měl přechod začít. Toto nastavení může být použito spolu s atributem advClick. Pokud tento atribut není zadán, předpokládá se, že automatické posunutí nebude probíhat. Čtení a zápis long.

**Vrací:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```


Určuje čas v milisekundách, po kterém by měl přechod začít. Toto nastavení může být použito spolu s atributem advClick. Pokud tento atribut není zadán, předpokládá se, že automatické posunutí nebude probíhat. Čtení a zápis long.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```


Určuje rychlost přechodu, která se má použít při přechodu ze současného snímku na další. Čtení a zápis [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Vrací:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```


Určuje rychlost přechodu, která se má použít při přechodu ze současného snímku na další. Čtení a zápis [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```


Hodnota přechodu prezentace. Pouze ke čtení [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Vrací:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```


Typ přechodu. Čtení a zápis [TransitionType](../../com.aspose.slides/transitiontype).

**Vrací:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


Typ přechodu. Čtení a zápis [TransitionType](../../com.aspose.slides/transitiontype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```


Určuje, zda je tento zvuk vestavěný. Pokud je tento atribut nastaven na true, generující aplikace je upozorněna, aby zkontrolovala atribut name uvedený pro tento zvuk v seznamu vestavěných zvuků a případně zobrazila vlastní název nebo UI. Čtení a zápis boolean.

**Vrací:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```


Určuje, zda je tento zvuk vestavěný. Pokud je tento atribut nastaven na true, generující aplikace je upozorněna, aby zkontrolovala atribut name uvedený pro tento zvuk v seznamu vestavěných zvuků a případně zobrazila vlastní název nebo UI. Čtení a zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```


Určuje člověkem čitelný název zvuku přechodu. Vlastnost \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) musí být přiřazena pro získání nebo nastavení názvu zvuku. Čtení a zápis String.

**Vrací:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```


Určuje člověkem čitelný název zvuku přechodu. Vlastnost \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) musí být přiřazena pro získání nebo nastavení názvu zvuku. Čtení a zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```


Vrací nebo nastavuje dobu trvání efektu přechodu snímku v milisekundách. Čtení/zápis int.

--------------------

Odpovídá atributu p14:dur elementu p:transition ve schématu PresentationML. Pokud není nastaveno, doba trvání je určena automaticky na základě vlastnosti \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) a typu přechodu.

**Vrací:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```


Vrací nebo nastavuje dobu trvání efektu přechodu snímku v milisekundách. Čtení/zápis int.

--------------------

Odpovídá atributu p14:dur elementu p:transition ve schématu PresentationML. Pokud není nastaveno, doba trvání je určena automaticky na základě vlastnosti \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) a typu přichodu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |