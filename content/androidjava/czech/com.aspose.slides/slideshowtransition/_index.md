---
title: SlideShowTransition
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje přechod prezentace.
type: docs
url: /cs/com.aspose.slides/slideshowtransition/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
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
| [getSpeed()](#getSpeed--) | Určuje rychlost přechodu, která se použije při přechodu z aktuálního snímku na další. |
| [setSpeed(int value)](#setSpeed-int-) | Určuje rychlost přechodu, která se použije při přechodu z aktuálního snímku na další. |
| [getValue()](#getValue--) | Hodnota přechodu prezentace. |
| [getType()](#getType--) | Typ přechodu. |
| [setType(int value)](#setType-int-) | Typ přechodu. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Určuje, zda je tento zvuk vestavěný. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Určuje, zda je tento zvuk vestavěný. |
| [getSoundName()](#getSoundName--) | Určuje čitelný název zvuku přechodu. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Určuje čitelný název zvuku přechodu. |
| [getDuration()](#getDuration--) | Vrací nebo nastavuje dobu trvání efektu přechodu snímku v milisekundách. |
| [setDuration(int value)](#setDuration-int-) | Vrací nebo nastavuje dobu trvání efektu přechodu snímku v milisekundách. |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda jsou dvě instance SlideShowTransition stejné. |
| [hashCode()](#hashCode--) | Slouží jako hash funkce pro daný typ, vhodná pro použití v hashovacích algoritmech a datových strukturách, jako je hash tabulka. |
### getSound() {#getSound--}
```
public final IAudio getSound()
```

Vrací nebo nastavuje vložená audio data. Číst/Zapisovat [IAudio](../../com.aspose.slides/iaudio).

**Návratová hodnota:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Vrací nebo nastavuje vložená audio data. Číst/Zapisovat [IAudio](../../com.aspose.slides/iaudio).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

Nastavuje nebo vrací režim zvuku pro přechod snímku. Číst/Zapisovat [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Návratová hodnota:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

Nastavuje nebo vrací režim zvuku pro přechod snímku. Číst/Zapisovat [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

Tento atribut určuje, zda se zvuk bude opakovat, dokud nenastane další zvuková událost v prezentaci. Číst/Zapisovat boolean.

**Návratová hodnota:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Tento atribut určuje, zda se zvuk bude opakovat, dokud nenastane další zvuková událost v prezentaci. Číst/Zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Určuje, zda kliknutí myší posune snímek dál, nebo ne. Pokud není tento atribut specifikován, předpokládá se hodnota true. Číst/Zapisovat boolean.

**Návratová hodnota:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Určuje, zda kliknutí myší posune snímek dál, nebo ne. Pokud není tento atribut specifikován, předpokládá se hodnota true. Číst/Zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

Tento atribut určuje, zda se prezentace přesune na další snímek po určité době. Číst/Zapisovat boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Získat první přechod snímku
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Zkontrolovat, zda je zaškrtnut příznak Advance Slide After
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Získat hodnotu Advance Slide After Time
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Návratová hodnota:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public final void setAdvanceAfter(boolean value)
```

Tento atribut určuje, zda se prezentace přesune na další snímek po určité době. Číst/Zapisovat boolean.

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
public final long getAdvanceAfterTime()
```

Určuje čas v milisekundách, po kterém by měl přechod začít. Toto nastavení lze použít společně s atributem advClick. Pokud tento atribut není specifikován, předpokládá se, že se automatické přecházení neuskuteční. Číst/Zapisovat long.

**Návratová hodnota:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Určuje čas v milisekundách, po kterém by měl přechod začít. Toto nastavení lze použít společně s atributem advClick. Pokud tento atribut není specifikován, předpokládá se, že se automatické přecházení neuskuteční. Číst/Zapisovat long.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |
### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Určuje rychlost přechodu, která se použije při přechodu z aktuálního snímku na další. Číst/Zapisovat [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Návratová hodnota:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Určuje rychlost přechodu, která se použije při přechodu z aktuálního snímku na další. Číst/Zapisovat [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

Hodnota přechodu prezentace. Pouze pro čtení [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Návratová hodnota:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public final int getType()
```

Typ přechodu. Číst/Zapisovat [TransitionType](../../com.aspose.slides/transitiontype).

**Návratová hodnota:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Typ přechodu. Číst/Zapisovat [TransitionType](../../com.aspose.slides/transitiontype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

Určuje, zda je tento zvuk vestavěný. Pokud je tento atribut nastaven na true, generující aplikace je upozorněna, aby zkontrolovala atribut name specifikovaný pro tento zvuk v seznamu vestavěných zvuků a může pak zobrazit vlastní název nebo uživatelské rozhraní podle potřeby. Číst/Zapisovat boolean.

**Návratová hodnota:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Určuje, zda je tento zvuk vestavěný. Pokud je tento atribut nastaven na true, generující aplikace je upozorněna, aby zkontrolovala atribut name specifikovaný pro tento zvuk v seznamu vestavěných zvuků a může pak zobrazit vlastní název nebo uživatelské rozhraní podle potřeby. Číst/Zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Určuje čitelný název zvuku přechodu. Vlastnost Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) musí být přiřazena k získání nebo nastavení názvu zvuku. Číst/Zapisovat String.

**Návratová hodnota:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Určuje čitelný název zvuku přechodu. Vlastnost Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) musí být přiřazena k získání nebo nastavení názvu zvuku. Číst/Zapisovat String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getDuration() {#getDuration--}
```
public final int getDuration()
```

Vrací nebo nastavuje dobu trvání efektu přechodu snímku v milisekundách. Číst/Zapisovat int.

--------------------

Odpovídá atributu p14:dur elementu p:transition ve schématu PresentationML. Pokud není nastaven, doba trvání je určena automaticky na základě vlastnosti \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) a typu přechodu.

**Návratová hodnota:**
int
### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Vrací nebo nastavuje dobu trvání efektu přechodu snímku v milisekundách. Číst/Zapisovat int.

--------------------

Odpovídá atributu p14:dur elementu p:transition ve schématu PresentationML. Pokud není nastaven, doba trvání je určena automaticky na základě vlastnosti \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) a typu přechodu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Určuje, zda jsou dvě instance SlideShowTransition stejné. Číst/Zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Instance SlideShowTransition, se kterou se porovnává aktuální SlideShowTransition. |

**Návratová hodnota:**
boolean - **true** pokud je specifikovaný SlideShowTransition roven aktuálnímu SlideShowTransition; jinak **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Slouží jako hash funkce pro daný typ, vhodná pro použití v hashovacích algoritmech a datových strukturách, jako je hash tabulka.

**Návratová hodnota:**
int - 23454

--------------------

Přepsáno, aby byl kompilátor spokojen. Vždy vrací konstantu, protože objekt je mutabilní.