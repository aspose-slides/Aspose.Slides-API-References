---
title: ISlideShowTransition
second_title: Aspose.Slides for Java API Reference
description: Represents slide show transition.
type: docs
url: /pl/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

Reprezentuje przejście pokazu slajdów.
## Metody

| Metoda | Opis |
| --- | --- |
| [getSound()](#getSound--) | Zwraca lub ustawia osadzone dane audio. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Zwraca lub ustawia osadzone dane audio. |
| [getSoundMode()](#getSoundMode--) | Ustawia lub zwraca tryb dźwięku dla przejścia slajdu. |
| [setSoundMode(int value)](#setSoundMode-int-) | Ustawia lub zwraca tryb dźwięku dla przejścia slajdu. |
| [getSoundLoop()](#getSoundLoop--) | Ten atrybut określa, czy dźwięk będzie się powtarzał, aż do wystąpienia następnego zdarzenia dźwiękowego w pokazie slajdów. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Ten atrybut określa, czy dźwięk będzie się powtarzał, aż do wystąpienia następnego zdarzenia dźwiękowego w pokazie slajdów. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Określa, czy kliknięcie myszy przejdzie do następnego slajdu, czy nie. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Określa, czy kliknięcie myszy przejdzie do następnego slajdu, czy nie. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Ten atrybut określa, czy pokaz slajdów przejdzie do następnego slajdu po określonym czasie. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Ten atrybut określa, czy pokaz slajdów przejdzie do następnego slajdu po określonym czasie. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Określa czas w milisekundach, po którym powinno rozpocząć się przejście. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Określa czas w milisekundach, po którym powinno rozpocząć się przejście. |
| [getSpeed()](#getSpeed--) | Określa prędkość przejścia używaną przy przechodzeniu z bieżącego slajdu do następnego. |
| [setSpeed(int value)](#setSpeed-int-) | Określa prędkość przejścia używaną przy przechodzeniu z bieżącego slajdu do następnego. |
| [getValue()](#getValue--) | Wartość przejścia pokazu slajdów. |
| [getType()](#getType--) | Typ przejścia. |
| [setType(int value)](#setType-int-) | Typ przejścia. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Określa, czy dźwięk jest wbudowany. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Określa, czy dźwięk jest wbudowany. |
| [getSoundName()](#getSoundName--) | Określa czytelną nazwę dźwięku przejścia. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Określa czytelną nazwę dźwięku przejścia. |
| [getDuration()](#getDuration--) | Zwraca lub ustawia czas trwania efektu przejścia slajdu w milisekundach. |
| [setDuration(int value)](#setDuration-int-) | Zwraca lub ustawia czas trwania efektu przejścia slajdu w milisekundach. |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Zwraca lub ustawia osadzone dane audio. Odczyt/zapis [IAudio](../../com.aspose.slides/iaudio).

**Zwraca:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Zwraca lub ustawia osadzone dane audio. Odczyt/zapis [IAudio](../../com.aspose.slides/iaudio).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

Ustawia lub zwraca tryb dźwięku dla przejścia slajdu. Odczyt/zapis [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Zwraca:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

Ustawia lub zwraca tryb dźwięku dla przejścia slajdu. Odczyt/zapis [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

Ten atrybut określa, czy dźwięk będzie się powtarzał, aż do wystąpienia następnego zdarzenia dźwiękowego w pokazie slajdów. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

Ten atrybut określa, czy dźwięk będzie się powtarzał, aż do wystąpienia następnego zdarzenia dźwiękowego w pokazie slajdów. Odczyt/zapis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

Określa, czy kliknięcie myszy przejdzie do następnego slajdu, czy nie. Jeśli atrybut nie zostanie określony, przyjmowana jest wartość true. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

Określa, czy kliknięcie myszy przejdzie do następnego slajdu, czy nie. Jeśli atrybut nie zostanie określony, przyjmowana jest wartość true. Odczyt/zapis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

Ten atrybut określa, czy pokaz slajdów przejdzie do następnego slajdu po określonym czasie. Odczyt/zapis boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Pobierz pierwsze przejście slajdu
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Sprawdź, czy flaga Advance Slide After jest zaznaczona
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Pobierz wartość czasu automatycznego przejścia slajdu
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```

Ten atrybut określa, czy pokaz slajdów przejdzie do następnego slajdu po określonym czasie. Odczyt/zapis boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Pobierz pierwsze przejście slajdu
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Sprawdź, czy flaga Advance Slide After jest zaznaczona
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Pobierz wartość czasu automatycznego przejścia slajdu
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```

Określa czas w milisekundach, po którym powinno rozpocząć się przejście. To ustawienie może być użyte wraz z atrybutem advClick. Jeśli atrybut nie zostanie określony, zakłada się, że nie będzie automatycznego przejścia. Odczyt/zapis long.

**Zwraca:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

Określa czas w milisekundach, po którym powinno rozpocząć się przejście. To ustawienie może być użyte wraz z atrybutem advClick. Jeśli atrybut nie zostanie określony, zakłada się, że nie będzie automatycznego przejścia. Odczyt/zapis long.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

Określa prędkość przejścia używaną przy przechodzeniu z bieżącego slajdu do następnego. Odczyt/zapis [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Zwraca:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

Określa prędkość przejścia używaną przy przechodzeniu z bieżącego slajdu do następnego. Odczyt/zapis [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

Wartość przejścia pokazu slajdów. Tylko do odczytu [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Zwraca:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```

Typ przejścia. Odczyt/zapis [TransitionType](../../com.aspose.slides/transitiontype).

**Zwraca:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Typ przejścia. Odczyt/zapis [TransitionType](../../com.aspose.slides/transitiontype).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

Określa, czy dźwięk jest wbudowany. Jeśli atrybut jest ustawiony na true, aplikacja generująca jest informowana o sprawdzeniu atrybutu name określonego dla tego dźwięku w swojej liście wbudowanych dźwięków i może wtedy wyświetlić niestandardową nazwę lub interfejs użytkownika w razie potrzeby. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

Określa, czy dźwięk jest wbudowany. Jeśli atrybut jest ustawiony na true, aplikacja generująca jest informowana o sprawdzeniu atrybutu name określonego dla tego dźwięku w swojej liście wbudowanych dźwięków i może wtedy wyświetlić niestandardową nazwę lub interfejs użytkownika w razie potrzeby. Odczyt/zapis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

Określa czytelną nazwę dźwięku przejścia. Właściwość \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) musi być przypisana, aby uzyskać lub ustawić nazwę dźwięku. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

Określa czytelną nazwę dźwięku przejścia. Właściwość \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) musi być przypisana, aby uzyskać lub ustawić nazwę dźwięku. Odczyt/zapis String.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

Zwraca lub ustawia czas trwania efektu przejścia slajdu w milisekundach. Odczyt/zapis int.

--------------------

Odpowiada atrybutowi p14:dur elementu p:transition w schemacie PresentationML. Jeśli nie zostanie ustawiony, czas trwania jest ustalany automatycznie na podstawie właściwości \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) oraz typu przejścia.

**Zwraca:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

Zwraca lub ustawia czas trwania efektu przejścia slajdu w milisekundach. Odczyt/zapis int.

--------------------

Odpowiada atrybutowi p14:dur elementu p:transition w schemacie PresentationML. Jeśli nie zostanie ustawiony, czas trwania jest ustalany automatycznie na podstawie właściwości \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) oraz typu przejścia.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |