---
title: ISlideShowTransition
second_title: Aspose.Slides for Java API Reference
description: Ábrázolja a diavetítés átmenetet.
type: docs
url: /hu/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

Ábrázolja a diavetítés átmenetet.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getSound()](#getSound--) | Returns or sets the embedded audio data. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Returns or sets the embedded audio data. |
| [getSoundMode()](#getSoundMode--) | Set or returns sound mode for slide transition. |
| [setSoundMode(int value)](#setSoundMode-int-) | Set or returns sound mode for slide transition. |
| [getSoundLoop()](#getSoundLoop--) | This attribute specifies if the sound will loop until the next sound event occurs in slideshow. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | This attribute specifies if the sound will loop until the next sound event occurs in slideshow. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Specifies whether a mouse click will advance the slide or not. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Specifies whether a mouse click will advance the slide or not. |
| [getAdvanceAfter()](#getAdvanceAfter--) | This attribute specifies if the slideshow will move to the next slide after a certain time. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | This attribute specifies if the slideshow will move to the next slide after a certain time. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Specifies the time, in milliseconds, after which the transition should start. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Specifies the time, in milliseconds, after which the transition should start. |
| [getSpeed()](#getSpeed--) | Specifies the transition speed that is to be used when transitioning from the current slide to the next. |
| [setSpeed(int value)](#setSpeed-int-) | Specifies the transition speed that is to be used when transitioning from the current slide to the next. |
| [getValue()](#getValue--) | Slide show transition value. |
| [getType()](#getType--) | Type of transition. |
| [setType(int value)](#setType-int-) | Type of transition. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Specifies whether or not this sound is a built-in sound. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Specifies whether or not this sound is a built-in sound. |
| [getSoundName()](#getSoundName--) | Specifies a human readable name for the sound of the transition. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Specifies a human readable name for the sound of the transition. |
| [getDuration()](#getDuration--) | Gets or sets the duration of the slide transition effect in milliseconds. |
| [setDuration(int value)](#setDuration-int-) | Gets or sets the duration of the slide transition effect in milliseconds. |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Visszaadja vagy beállítja a beágyazott hangadatokat. Olvasás-írás [IAudio](../../com.aspose.slides/iaudio).

**Returns:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Visszaadja vagy beállítja a beágyazott hangadatokat. Olvasás-írás [IAudio](../../com.aspose.slides/iaudio).

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

Set or returns sound mode for slide transition. Olvasás-írás [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Returns:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

Set or returns sound mode for slide transition. Olvasás-írás [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

Ez a tulajdonság meghatározza, hogy a hang a következő hangeseményig ismétlődik-e a diavetítésben. Olvasás-írás boolean.

**Returns:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

Ez a tulajdonság meghatározza, hogy a hang a következő hangeseményig ismétlődik-e a diavetítésben. Olvasás-írás boolean.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

Meghatározza, hogy egy egérkattintás előreviszi-e a diát vagy sem. Ha ez a tulajdonság nincs megadva, akkor igaz értéket feltételezünk. Olvasás-írás boolean.

**Returns:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

Meghatározza, hogy egy egérkattintás előreviszi-e a diát vagy sem. Ha ez a tulajdonság nincs megadva, akkor igaz értéket feltételezünk. Olvasás-írás boolean.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

Ez a tulajdonság meghatározza, hogy a diavetítés egy bizonyos idő elteltével átmenjen a következő diára. Olvasás/írás boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Lekérdezi az első dia átmenetét
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Ellenőrizze, hogy a Advance Slide After jelző be van-e jelölve
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Lekérdezi az Advance Slide After Time értékét
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```

Ez a tulajdonság meghatározza, hogy a diavetítés egy bizonyos idő elteltével átmenjen a következő diára. Olvasás/írás boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dia átmenetét
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Ellenőrizze, hogy a Advance Slide After jelző be van-e jelölve
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Lekéri az Advance Slide After Time értékét
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```

Meghatározza azt az időt (ezredmásodpercben), amely után az átmenetnek el kell indulnia. Ez a beállítás a advClick attribútummal együtt használható. Ha ez az attribútum nincs megadva, akkor feltételezzük, hogy automatikus előrehaladás nem történik. Olvasás-írás long.

**Returns:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

Meghatározza azt az időt (ezredmásodpercben), amely után az átmenetnek el kell indulnia. Ez a beállítás a advClick attribútummal együtt használható. Ha ez az attribútum nincs megadva, akkor feltételezzük, hogy automatikus előrehaladás nem történik. Olvasás-írás long.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

Meghatározza a sebességet, amely a jelenlegi diáról a következőre történő átmenetkor használatos. Olvasás-írás [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Returns:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

Meghatározza a sebességet, amely a jelenlegi diáról a következőre történő átmenetkor használatos. Olvasás-írás [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

Slide show transition value. Csak olvasható [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Returns:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```

Transition típusa. Olvasás-írás [TransitionType](../../com.aspose.slides/transitiontype).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Transition típusa. Olvasás-írás [TransitionType](../../com.aspose.slides/transitiontype).

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

Meghatározza, hogy a hang beépített hang-e. Ha ez a tulajdonság igaz, akkor a generáló alkalmazás ellenőrzi a hang névattribútumát a beépített hangok listájában, és ennek megfelelően testreszabott nevet vagy felhasználói felületet jelenít meg. Olvasás-írás boolean.

**Returns:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

Meghatározza, hogy a hang beépített hang-e. Ha ez a tulajdonság igaz, akkor a generáló alkalmazás ellenőrzi a hang névattribútumát a beépített hangok listájában, és ennek megfelelően testreszabott nevet vagy felhasználói felületet jelenít meg. Olvasás-írás boolean.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

Meghatározza a hang ember által olvasható nevét az átmenethez. A (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) tulajdonságot kell használni a hang nevének beolvasásához vagy beállításához. Olvasás-írás String.

**Returns:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

Meghatározza a hang ember által olvasható nevét az átmenethez. A \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) tulajdonságot kell használni a hang nevének beolvasásához vagy beállításához. Olvasás-írás String.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

Az átmeneti hatás időtartamát millimásodpercben adja vissza vagy állítja be. Olvasás/írás int.

--------------------

A p14:dur attribútumnak felel meg a p:transition elemben a PresentationML sémában. Ha nincs beállítva, az időtartamot automatikusan a \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) tulajdonság és az átmenet típusa határozza meg.

**Returns:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

Az átmeneti hatás időtartamát millimásodpercben adja vissza vagy állítja be. Olvasás/írás int.

--------------------

A p14:dur attribútumnak felel meg a p:transition elemben a PresentationML sémában. Ha nincs beállítva, az időtartamot automatikusan a \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) tulajdonság és az átmenet típusa határozza meg.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |