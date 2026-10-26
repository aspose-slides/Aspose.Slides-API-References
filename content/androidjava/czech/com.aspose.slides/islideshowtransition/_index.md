---
title: ISlideShowTransition
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje přechod snímkové prezentace.
type: docs
url: /cs/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

Reprezentuje přechod snímkové prezentace.
## Metody

| Metoda | Popis |
| --- | --- |
| [getSound()](#getSound--) | Vrací nebo nastavuje vložená audio data. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Vrací nebo nastavuje vložená audio data. |
| [getSoundMode()](#getSoundMode--) | Nastaví nebo vrátí režim zvuku pro přechod snímku. |
| [setSoundMode(int value)](#setSoundMode-int-) | Nastaví nebo vrátí režim zvuku pro přechod snímku. |
| [getSoundLoop()](#getSoundLoop--) | Tento atribut určuje, zda se zvuk bude opakovat, dokud nenastane další zvuková událost v prezentaci. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Tento atribut určuje, zda se zvuk bude opakovat, dokud nenastane další zvuková událost v prezentaci. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Určuje, zda kliknutí myší posune snímek vpřed, nebo ne. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Určuje, zda kliknutí myší posune snímek vpřed, nebo ne. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Tento atribut určuje, zda se prezentace přesune na další snímek po určité době. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Tento atribut určuje, zda se prezentace přesune na další snímek po určité době. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Určuje čas v milisekundách, po kterém má přechod začít. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Určuje čas v milisekundách, po kterém má přechod začít. |
| [getSpeed()](#getSpeed--) | Určuje rychlost přechodu, která se použije při přechodu z aktuálního snímku na další. |
| [setSpeed(int value)](#setSpeed-int-) | Určuje rychlost přechodu, která se použije při přechodu z aktuálního snímku na další. |
| [getValue()](#getValue--) | Hodnota přechodu prezentace. |
| [getType()](#getType--) | Typ přechodu. |
| [setType(int value)](#setType-int-) | Typ přechodu. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Určuje, zda je tento zvuk vestavěný, nebo ne. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Určuje, zda je tento zvuk vestavěný, nebo ne. |
| [getSoundName()](#getSoundName--) | Určuje čitelné jméno pro zvuk přechodu. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Určuje čitelné jméno pro zvuk přechodu. |
| [getDuration()](#getDuration--) | Vrací nebo nastavuje dobu trvání efektu přechodu snímku v milisekundách. |
| [setDuration(int value)](#setDuration-int-) | Vrací nebo nastavuje dobu trvání efektu přechodu snímku v milisekundách. |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Vrací nebo nastavuje vložená audio data. Čtení/Zápis [IAudio](../../com.aspose.slides/iaudio).

**Vrací:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Vrací nebo nastavuje vložená audio data. Čtení/Zápis [IAudio](../../com.aspose.slides/iaudio).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

Nastaví nebo vrátí režim zvuku pro přechod snímku. Čtení/Zápis [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Vrací:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

Nastaví nebo vrátí režim zvuku pro přechod snímku. Čtení/Zápis [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

Tento atribut určuje, zda se zvuk bude opakovat, dokud nenastane další zvuková událost v prezentaci. Čtení/Zápis boolean.

**Vrací:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

Tento atribut určuje, zda se zvuk bude opakovat, dokud nenastane další zvuková událost v prezentaci. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

Určuje, zda kliknutí myší posune snímek vpřed, nebo ne. Pokud není tento atribut specifikován, předpokládá se hodnota true. Čtení/Zápis boolean.

**Vrací:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

Určuje, zda kliknutí myší posune snímek vpřed, nebo ne. Pokud není tento atribut specifikován, předpokládá se hodnota true. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

Tento atribut určuje, zda se prezentace přesune na další snímek po určité době. Čtení/Zápis boolean.

**Vrací:**
boolean

--------------------

> ``` 
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Získá první přechod snímku
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Zkontroluje, zda je zaškrtnut příznak Advance Slide After
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Získá hodnotu času posunu snímku po uplynutí
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

Tento atribut určuje, zda se prezentace přesune na další snímek po určité době. Čtení/Zápis boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Získá první přechod snímku
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Zkontroluje, zda je zaškrtnut příznak Advance Slide After
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Získá hodnotu času posunu snímku po uplynutí
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

Určuje čas v milisekundách, po kterém má přechod začít. Toto nastavení může být použito ve spojení s atributem advClick. Pokud není tento atribut specifikován, předpokládá se, že nedojde k automatickému posunu. Čtení/Zápis long.

**Vrací:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

Určuje čas v milisekundách, po kterém má přechod začít. Toto nastavení může být použito ve spojení s atributem advClick. Pokud není tento atribut specifikován, předpokládá se, že nedojde k automatickému posunu. Čtení/Zápis long.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

Určuje rychlost přechodu, která se použije při přechodu z aktuálního snímku na další. Čtení/Zápis [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Vrací:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

Určuje rychlost přechodu, která se použije při přechodu z aktuálního snímku na další. Čtení/Zápis [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

Hodnota přechodu prezentace. Pouze pro čtení [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Vrací:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public abstract int getType()
```

Typ přechodu. Čtení/Zápis [TransitionType](../../com.aspose.slides/transitiontype).

**Vrací:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Typ přechodu. Čtení/Zápis [TransitionType](../../com.aspose.slides/transitiontype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

Určuje, zda je tento zvuk vestavěný, nebo ne. Pokud je tento atribut nastaven na true, generující aplikace je upozorněna, aby zkontrolovala atribut name určený pro tento zvuk v jejím seznamu vestavěných zvuků a může poté zobrazit vlastní název nebo uživatelské rozhraní podle potřeby. Čtení/Zápis boolean.

**Vrací:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

Určuje, zda je tento zvuk vestavěný, nebo ne. Pokud je tento atribut nastaven na true, generující aplikace je upozorněna, aby zkontrolovala atribut name určený pro tento zvuk v jejím seznamu vestavěných zvuků a může poté zobrazit vlastní název nebo uživatelské rozhraní podle potřeby. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

Určuje čitelné jméno pro zvuk přechodu. Vlastnost (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) musí být přiřazena pro získání nebo nastavení názvu zvuku. Čtení/Zápis String.

**Vrací:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

Určuje čitelné jméno pro zvuk přechodu. Vlastnost \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) musí být přiřazena pro získání nebo nastavení názvu zvuku. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

Vrací nebo nastavuje dobu trvání efektu přechodu snímku v milisekundách. Čtení/Zápis int.

--------------------

Odpovídá atributu p14:dur elementu p:transition v schématu PresentationML. Pokud není nastaveno, doba trvání je určena automaticky na základě vlastnosti \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) a typu přechodu.

**Vrací:**
int

### setDuration(int value) {#setDuration-int-}
``` 
public abstract void setDuration(int value)
```

Vrací nebo nastavuje dobu trvání efektu přechodu snímku v milisekundách. Čtení/Zápis int.

--------------------

Odpovídá atributu p14:dur elementu p:transition v schématu PresentationML. Pokud není nastaveno, doba trvání je určena automaticky na základě vlastnosti \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) a typu přechodu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |