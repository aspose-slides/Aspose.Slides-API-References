---
title: SlideShowTransition
second_title: Aspose.Slides Java API-referencia
description: A diavetítés átmenetet reprezentálja.
type: docs
url: /hu/com.aspose.slides/slideshowtransition/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

Represents slide show transition.
## Metódusok

| Method | Leírás |
| --- | --- |
| [getSound()](#getSound--) | Visszaadja vagy beállítja a beágyazott audio adatot. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Visszaadja vagy beállítja a beágyazott audio adatot. |
| [getSoundMode()](#getSoundMode--) | Beállítja vagy visszaadja a hang módot a diavetítés átmenetéhez. |
| [setSoundMode(int value)](#setSoundMode-int-) | Beállítja vagy visszaadja a hang módot a diavetítés átmenetéhez. |
| [getSoundLoop()](#getSoundLoop--) | Ez a tulajdonság meghatározza, hogy a hang addig ismétlődik-e, amíg a következő hangesemény elő nem jön a diavetítésben. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Ez a tulajdonság meghatározza, hogy a hang addig ismétlődik-e, amíg a következő hangesemény elő nem jön a diavetítésben. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Megadja, hogy egy egérkattintás előrelép-e a dián vagy sem. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Megadja, hogy egy egérkattintás előrelép-e a dián vagy sem. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Ez a tulajdonság meghatározza, hogy a diavetítés egy bizonyos idő után átmenjen-e a következő diára. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Ez a tulajdonság meghatározza, hogy a diavetítés egy bizonyos idő után átmenjen-e a következő diára. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Megadja az időt (ezredmásodpercben), amely után az átmenetet el kell indítani. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Megadja az időt (ezredmásodpercben), amely után az átmenetet el kell indítani. |
| [getSpeed()](#getSpeed--) | Megadja az átmenet sebességét, amely a jelenlegi dia és a következő közötti átmenethez használatos. |
| [setSpeed(int value)](#setSpeed-int-) | Megadja az átmenet sebességét, amely a jelenlegi dia és a következő közötti átmenethez használatos. |
| [getValue()](#getValue--) | Diavetítés átmenet értéke. |
| [getType()](#getType--) | Az átmenet típusa. |
| [setType(int value)](#setType-int-) | Az átmenet típusa. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Megadja, hogy ez a hang beépített hang-e vagy sem. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Megadja, hogy ez a hang beépített hang-e vagy sem. |
| [getSoundName()](#getSoundName--) | Megad egy ember által olvasható nevet az átmenet hangjának. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Megad egy ember által olvasható nevet az átmenet hangjának. |
| [getDuration()](#getDuration--) | Visszaadja vagy beállítja a diaátmenet hatás időtartamát ezredmásodpercben. |
| [setDuration(int value)](#setDuration-int-) | Visszaadja vagy beállítja a diaátmenet hatás időtartamát ezredmásodpercben. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a két SlideShowTransition példány egyenlő-e. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz, amely alkalmas hash algoritmusokban és hash tábla típusú adatstruktúrákban való használatra. |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Visszaadja vagy beállítja a beágyazott audio adatot. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

**Visszatér:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Visszaadja vagy beállítja a beágyazott audio adatot. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

Beállítja vagy visszaadja a hang módot a diavetítés átmenetéhez. Olvasás/írás [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Visszatér:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

Beállítja vagy visszaadja a hang módot a diavetítés átmenetéhez. Olvasás/írás [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

Ez a tulajdonság meghatározza, hogy a hang addig ismétlődik-e, amíg a következő hangesemény elő nem jön a diavetítésben. Olvasás/írás boolean.

**Visszatér:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Ez a tulajdonság meghatározza, hogy a hang addig ismétlődik-e, amíg a következő hangesemény elő nem jön a diavetítésben. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Megadja, hogy egy egérkattintás előrelép-e a dián vagy sem. Ha ez a tulajdonság nincs megadva, akkor a true érték feltételezett. Olvasás/írás boolean.

**Visszatér:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Megadja, hogy egy egérkattintás előrelép-e a dián vagy sem. Ha ez a tulajdonság nincs megadva, akkor a true érték feltételezett. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

Ez a tulajdonság meghatározza, hogy a diavetítés egy bizonyos idő után átmenjen-e a következő diára. Olvasás/írás boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Szerezze meg az első diaátmenetet
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Ellenőrizze, hogy az 'Advance Slide After' jelző be van-e állítva
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Szerezze meg az 'Advance Slide After Time' értékét
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

Ez a tulajdonság meghatározza, hogy a diavetítés egy bizonyos idő után átmenjen-e a következő diára. Olvasás/írás boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Szerezze meg az első diaátmenetet
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Ellenőrizze, hogy az 'Advance Slide After' jelző be van-e állítva
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Szerezze meg az 'Advance Slide After Time' értékét
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

Megadja az időt (ezredmásodpercben), amely után az átmenetet el kell indítani. Ez a beállítás a advClick attribútummal együtt használható. Ha ez az attribútum nincs megadva, akkor úgy tekinthető, hogy nincs automatikus előrehaladás. Olvasás/írás long.

**Visszatér:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Megadja az időt (ezredmásodpercben), amely után az átmenetet el kell indítani. Ez a beállítás a advClick attribútummal együtt használható. Ha ez az attribútum nincs megadva, akkor úgy tekinthető, hogy nincs automatikus előrehaladás. Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Megadja az átmenet sebességét, amely a jelenlegi dia és a következő közötti átmenethez használatos. Olvasás/írás [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Visszatér:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Megadja az átmenet sebességét, amely a jelenlegi dia és a következő közötti átmenethez használatos. Olvasás/írás [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionBase getValue()
```

Diavetítés átmenet értéke. Csak olvasható [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

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

Megadja, hogy ez a hang beépített hang-e vagy sem. Ha ez az attribútum true értékre van állítva, akkor a generáló alkalmazás értesítve van, hogy ellenőrizze a hanghoz megadott name attribútumot a beépített hangok listájában, és ennek megfelelően megjeleníthet egy egyéni nevet vagy UI-t. Olvasás/írás boolean.

**Visszatér:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Megadja, hogy ez a hang beépített hang-e vagy sem. Ha ez az attribútum true értékre van állítva, akkor a generáló alkalmazás értesítve van, hogy ellenőrizze a hanghoz megadott name attribútumot a beépített hangok listájában, és ennek megfelelően megjeleníthet egy egyéni nevet vagy UI-t. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Megad egy ember által olvasható nevet az átmenet hangjának. A Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) tulajdonságnak kell értéket kapnia a hang név lekéréséhez vagy beállításához. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Megad egy ember által olvasható nevet az átmenet hangjának. A Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) tulajdonságnak kell értéket kapnia a hang név lekéréséhez vagy beállításához. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

Visszaadja vagy beállítja a diaátmenet hatás időtartamát ezredmásodpercben. Olvasás/írás int.

Corresponds to the p14:dur attribute of the p:transition element in the PresentationML schema. If not set, the duration is determined automatically based on the \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) property and the transition type.

**Visszatér:**
int
### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Visszaadja vagy beállítja a diaátmenet hatás időtartamát ezredmásodpercben. Olvasás/írás int.

Corresponds to the p14:dur attribute of the p:transition element in the PresentationML schema. If not set, the duration is determined automatically based on the \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) property and the transition type.

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
| obj | java.lang.Object | A SlideShowTransition, amelyet az aktuális SlideShowTransitiontel összehasonlít. |

**Visszatér:**
boolean – **true** ha a megadott SlideShowTransition egyenlő a jelenlegi SlideShowTransitiontel; egyébként **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típushoz, amely alkalmas hash algoritmusokban és hash tábla típusú adatstruktúrákban való használatra.

**Visszatér:**
int – 23454

Overriden to make compiler happy. Always returns constant because object is mutable.