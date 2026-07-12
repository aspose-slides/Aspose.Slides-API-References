---
title: ISlideShowTransition
second_title: Aspose.Slides for Android via Java API Reference
description: Represents slide show transition.
type: docs
url: /hu/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

A diavetítés átmenetét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getSound()](#getSound--) | Visszaadja vagy beállítja a beágyazott audio adatot. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Visszaadja vagy beállítja a beágyazott audio adatot. |
| [getSoundMode()](#getSoundMode--) | Beállítja vagy visszaadja a hangmódot a diaátmenethez. |
| [setSoundMode(int value)](#setSoundMode-int-) | Beállítja vagy visszaadja a hangmódot a diaátmenethez. |
| [getSoundLoop()](#getSoundLoop--) | Ez az attribútum meghatározza, hogy a hang újraindul-e a következő hangesemény megjelenéséig a diavetítésben. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Ez az attribútum meghatározza, hogy a hang újraindul-e a következő hangesemény megjelenéséig a diavetítésben. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Megadja, hogy egy egérkattintás előrehozza-e a diát vagy sem. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Megadja, hogy egy egérkattintás előrehozza-e a diát vagy sem. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Ez az attribútum meghatározza, hogy a diavetítés egy bizonyos idő után a következő diára lép-e. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Ez az attribútum meghatározza, hogy a diavetítés egy bizonyos idő után a következő diára lép-e. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Megadja azt az időt milliszekundumban, amely után az átmenetnek el kell indulnia. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Megadja azt az időt milliszekundumban, amely után az átmenetnek el kell indulnia. |
| [getSpeed()](#getSpeed--) | Megadja az átmenet sebességét, amelyet az aktuális dia követő dia felé történő átmenet során kell használni. |
| [setSpeed(int value)](#setSpeed-int-) | Megadja az átmenet sebességét, amelyet az aktuális dia követő dia felé történő átmenet során kell használni. |
| [getValue()](#getValue--) | Diavetítés átmeneti érték. |
| [getType()](#getType--) | Az átmenet típusa. |
| [setType(int value)](#setType-int-) | Az átmenet típusa. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Megadja, hogy ez a hang beépített hang-e vagy sem. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Megadja, hogy ez a hang beépített hang-e vagy sem. |
| [getSoundName()](#getSoundName--) | Megad egy ember által olvasható nevet az átmenet hangjának. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Megad egy ember által olvasható nevet az átmenet hangjának. |
| [getDuration()](#getDuration--) | Visszaadja vagy beállítja a diaátmeneti effektus időtartamát milliszekundumban. |
| [setDuration(int value)](#setDuration-int-) | Visszaadja vagy beállítja a diaátmeneti effektus időtartamát milliszekundumban. |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Visszaadja vagy beállítja a beágyazott audio adatot. Olvasás-írás [IAudio](../../com.aspose.slides/iaudio).

**Visszatér:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Visszaadja vagy beállítja a beágyazott audio adatot. Olvasás-írás [IAudio](../../com.aspose.slides/iaudio).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

Beállítja vagy visszaadja a hangmódot a diaátmenethez. Olvasás-írás [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Visszatér:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

Beállítja vagy visszaadja a hangmódot a diaátmenethez. Olvasás-írás [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

Ez az attribútum meghatározza, hogy a hang újraindul-e a következő hangesemény megjelenéséig a diavetítésben. Olvasás-írás boolean.

**Visszatér:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

Ez az attribútum meghatározza, hogy a hang újraindul-e a következő hangesemény megjelenéséig a diavetítésben. Olvasás-írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

Megadja, hogy egy egérkattintás előrehozza-e a diát vagy sem. Ha ez az attribútum nincs megadva, akkor az igaz érték feltételezhető. Olvasás-írás boolean.

**Visszatér:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

Megadja, hogy egy egérkattintás előrehozza-e a diát vagy sem. Ha ez az attribútum nincs megadva, akkor az igaz érték feltételezhető. Olvasás-írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

Ez az attribútum meghatározza, hogy a diavetítés egy bizonyos idő után a következő diára lép-e. Olvasás/írás boolean.
--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Get the first slide Transition
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Check if the Advance Slide After flag is checked
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Get the Advance Slide After Time value
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```

Ez az attribútum meghatározza, hogy a diavetítés egy bizonyos idő után a következő diára lép-e. Olvasás/írás boolean.
--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Az első diaátmenet lekérése
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Ellenőrizze, hogy az Advance Slide After jel be van-e jelölve
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Az Advance Slide After időértékének lekérése
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```

Megadja azt az időt milliszekundumban, amely után az átmenetnek el kell indulnia. Ez a beállítás a advClick attribútummal együtt használható. Ha ez az attribútum nincs megadva, akkor úgy feltételezhető, hogy nem történik automatikus előrehaladás. Olvasás-írás long.

**Visszatér:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

Megadja azt az időt milliszekundumban, amely után az átmenetnek el kell indulnia. Ez a beállítás a advClick attribútummal együtt használható. Ha ez az attribútum nincs megadva, akkor úgy feltételezhető, hogy nem történik automatikus előrehaladás. Olvasás-írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |
### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

Megadja az átmenet sebességét, amelyet az aktuális dia követő dia felé történő átmenet során kell használni. Olvasás-írás [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Visszatér:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

Megadja az átmenet sebességét, amelyet az aktuális dia követő dia felé történő átmenet során kell használni. Olvasás-írás [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

Diavetítés átmeneti érték. Csak olvasható [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Visszatér:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```

Az átmenet típusa. Olvasás-írás [TransitionType](../../com.aspose.slides/transitiontype).

**Visszatér:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Az átmenet típusa. Olvasás-írás [TransitionType](../../com.aspose.slides/transitiontype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

Megadja, hogy ez a hang beépített hang-e vagy sem. Ha ez az attribútum igazra van állítva, akkor a generáló alkalmazás értesítést kap, hogy ellenőrizze a hanghoz megadott name attribútumot a beépített hangok listájában, és szükség esetén megjeleníthet egy egyedi nevet vagy felhasználói felületet. Olvasás-írás boolean.

**Visszatér:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

Megadja, hogy ez a hang beépített hang-e vagy sem. Ha ez az attribútum igazra van állítva, akkor a generáló alkalmazás értesítést kap, hogy ellenőrizze a hanghoz megadott name attribútumot a beépített hangok listájában, és szükség esetén megjeleníthet egy egyedi nevet vagy felhasználói felületet. Olvasás-írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

Megad egy ember által olvasható nevet az átmenet hangjának. A (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) tulajdonságnak kell hozzárendelve a hang nevének lekéréséhez vagy beállításához. Olvasás-írás String.

**Visszatér:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

Megad egy ember által olvasható nevet az átmenet hangjának. A \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) tulajdonságnak kell hozzárendelve a hang nevének lekéréséhez vagy beállításához. Olvasás-írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

Visszaadja vagy beállítja a diaátmeneti effektus időtartamát milliszekundumban. Olvasás/írás int.

--------------------

A p:transition elem p14:dur attribútumának felel meg a PresentationML sémában. Ha nincs beállítva, az időtartam automatikusan kerül meghatározásra a \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) tulajdonság és az átmenet típusa alapján.

**Visszatér:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

Visszaadja vagy beállítja a diaátmeneti effektus időtartamát milliszekundumban. Olvasás/írás int.

--------------------

A p:transition elem p14:dur attribútumának felel meg a PresentationML sémában. Ha nincs beállítva, az időtartam automatikusan kerül meghatározásra a \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) tulajdonság és az átmenet típusa alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |