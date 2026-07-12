---
title: SlideShowTransition
second_title: Aspose.Slides Android számára Java API hivatkozás
description: A diavetítés átmenetet képviseli.
type: docs
url: /hu/com.aspose.slides/slideshowtransition/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

A diavetítés átmenetet képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSound()](#getSound--) | Visszaadja vagy beállítja a beágyazott hangadatot. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Visszaadja vagy beállítja a beágyazott hangadatot. |
| [getSoundMode()](#getSoundMode--) | Beállítja vagy visszaadja a hangmódot a diavetítés átmenethez. |
| [setSoundMode(int value)](#setSoundMode-int-) | Beállítja vagy visszaadja a hangmódot a diavetítés átmenethez. |
| [getSoundLoop()](#getSoundLoop--) | Ez az attribútum meghatározza, hogy a hang ismétlődik-e a következő hangeseményig a diavetítésben. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Ez az attribútum meghatározza, hogy a hang ismétlődik-e a következő hangeseményig a diavetítésben. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Megadja, hogy egy egérkattintás előreviszi-e a diát vagy sem. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Megadja, hogy egy egérkattintás előreviszi-e a diát vagy sem. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Ez az attribútum meghatározza, hogy a diavetítés egy bizonyos idő után a következő diára lép-e. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Ez az attribútum meghatározza, hogy a diavetítés egy bizonyos idő után a következő diára lép-e. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Megadja azt az időt (ezredmásodpercben), amely után az átmenetnek el kell indulnia. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Megadja azt az időt (ezredmásodpercben), amely után az átmenetnek el kell indulnia. |
| [getSpeed()](#getSpeed--) | Meghatározza az átmenet sebességét, amelyet a jelenlegi dia és a következő közötti átmenethez használ. |
| [setSpeed(int value)](#setSpeed-int-) | Meghatározza az átmenet sebességét, amelyet a jelenlegi dia és a következő közötti átmenethez használ. |
| [getValue()](#getValue--) | Diavetítés átmenet érték. |
| [getType()](#getType--) | Az átmenet típusa. |
| [setType(int value)](#setType-int-) | Az átmenet típusa. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Megadja, hogy a hang beépített hang-e vagy sem. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Megadja, hogy a hang beépített hang-e vagy sem. |
| [getSoundName()](#getSoundName--) | Megad egy ember által olvasható nevet az átmenet hangjának. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Megad egy ember által olvasható nevet az átmenet hangjának. |
| [getDuration()](#getDuration--) | Visszaadja vagy beállítja a diák közötti átmenet hatás időtartamát ezredmásodpercben. |
| [setDuration(int value)](#setDuration-int-) | Visszaadja vagy beállítja a diák közötti átmenet hatás időtartamát ezredmásodpercben. |
| [equals(Object obj)](#equals-java.lang.Object-) | Meghatározza, hogy a két SlideShowTransition példány egyenlő-e. |
| [hashCode()](#hashCode--) | Hash-funkcióként szolgál egy adott típushoz, amely alkalmas hash algoritmusokban és adatstruktúrákban, például hash tábla használatára. |
### getSound() {#getSound--}
```
public final IAudio getSound()
```

Visszaadja vagy beállítja a beágyazott hangadatot. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

**Visszatér:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Visszaadja vagy beállítja a beágyazott hangadatot. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

Beállítja vagy visszaadja a hangmódot a diavetítés átmenethez. Olvasás/írás [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Visszatér:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

Beállítja vagy visszaadja a hangmódot a diavetítés átmenethez. Olvasás/írás [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

Ez az attribútum meghatározza, hogy a hang ismétlődik-e a következő hangeseményig a diavetítésben. Olvasás/írás boolean.

**Visszatér:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Ez az attribútum meghatározza, hogy a hang ismétlődik-e a következő hangeseményig a diavetítésben. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Megadja, hogy egy egérkattintás előreviszi-e a diát vagy sem. Ha ez az attribútum nincs megadva, akkor a true érték feltételezhető. Olvasás/írás boolean.

**Visszatér:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Megadja, hogy egy egérkattintás előreviszi-e a diát vagy sem. Ha ez az attribútum nincs megadva, akkor a true érték feltételezhető. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

Ez az attribútum meghatározza, hogy a diavetítés egy bizonyos idő után a következő diára lép-e. Olvasás/írás boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Az első slide Transition lekérése
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Ellenőrizze, hogy az Advance Slide After jelölő be van-e jelölve
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Az Advance Slide After Time érték lekérése
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
public final void setAdvanceAfter(boolean value)
```

Ez az attribútum meghatározza, hogy a diavetítés egy bizonyos idő után a következő diára lép-e. Olvasás/írás boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Az első slide Transition lekérése
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Ellenőrizze, hogy az Advance Slide After jelölő be van-e jelölve
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Az Advance Slide After Time érték lekérése
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
public final long getAdvanceAfterTime()
```

Megadja azt az időt (ezredmásodpercben), amely után az átmenetnek el kell indulnia. Ez a beállítás a advClick attribútummal együtt is használható. Ha ez az attribútum nincs megadva, akkor feltételezhető, hogy nem történik automatikus előrehaladás. Olvasás/írás long.

**Visszatér:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Megadja azt az időt (ezredmásodpercben), amely után az átmenetnek el kell indulnia. Ez a beállítás a advClick attribútummal együtt is használható. Ha ez az attribútum nincs megadva, akkor feltételezhető, hogy nem történik automatikus előrehaladás. Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |
### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Meghatározza az átmenet sebességét, amelyet a jelenlegi dia és a következő közötti átmenethez használ. Olvasás/írás [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Visszatér:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Meghatározza az átmenet sebességét, amelyet a jelenlegi dia és a következő közötti átmenethez használ. Olvasás/írás [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

Diavetítés átmenet érték. Csak olvasható [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Visszatér:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public final int getType()
```

Az átmenet típusa. Olvasás/írás [TransitionType](../../com.aspose.slides/transitiontype).

**Visszatér:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Az átmenet típusa. Olvasás/írás [TransitionType](../../com.aspose.slides/transitiontype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

Megadja, hogy a hang beépített hang-e vagy sem. Ha ez az attribútum true értékre van állítva, akkor a generáló alkalmazás figyelmeztetve van, hogy ellenőrizze a hanghoz megadott name attribútumot a beépített hangok listájában, és szükség esetén egy egyedi nevet vagy felületet jeleníthet meg. Olvasás/írás boolean.

**Visszatér:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Megadja, hogy a hang beépített hang-e vagy sem. Ha ez az attribútum true értékre van állítva, akkor a generáló alkalmazás figyelmeztetve van, hogy ellenőrizze a hanghoz megadott name attribútumot a beépített hangok listájában, és szükség esetén egy egyedi nevet vagy felületet jeleníthet meg. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Megad egy ember által olvasható nevet az átmenet hangjának. A Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) tulajdonságot kell hozzárendelni a hang név lekérdezéséhez vagy beállításához. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Megad egy ember által olvasható nevet az átmenet hangjának. A Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) tulajdonságot kell hozzárendelni a hang név lekérdezéséhez vagy beállításához. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getDuration() {#getDuration--}
```
public final int getDuration()
```

Visszaadja vagy beállítja a diák közötti átmenet hatás időtartamát ezredmásodpercben. Olvasás/írás int.

--------------------

Az p14:dur attribútumnak felel meg a p:transition elemben a PresentationML séma szerint. Ha nincs beállítva, az időtartamot automatikusan határozza meg a \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) tulajdonság és az átmenet típusa alapján.

**Visszatér:**
int
### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Visszaadja vagy beállítja a diák közötti átmenet hatás időtartamát ezredmásodpercben. Olvasás/írás int.

--------------------

Az p14:dur attribútumnak felel meg a p:transition elemben a PresentationML séma szerint. Ha nincs beállítva, az időtartamot automatikusan határozza meg a \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) tulajdonság és az átmenet típusa alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Megállapítja, hogy a két SlideShowTransition példány egyenlő-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A SlideShowTransition, amellyel a jelenlegi SlideShowTransition összehasonlítandó. |

**Visszatér:**
boolean -  **true**  ha a megadott SlideShowTransition egyenlő a jelenlegi SlideShowTransitiontel; egyébként  **false** .
### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash-funkcióként szolgál egy adott típushoz, amely alkalmas hash algoritmusokban és adatstruktúrákban, például hash tábla használatára.

**Visszatér:**
int - 23454

--------------------

Felülírva, hogy a fordító elégedett legyen. Mindig egy állandó értéket ad vissza, mivel az objektum módosítható.