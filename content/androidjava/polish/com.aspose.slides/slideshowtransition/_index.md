---
title: SlideShowTransition
second_title: Aspose.Slides dla Androida – odwołanie do API Java
description: Reprezentuje przejście pokazu slajdów.
type: docs
url: /pl/com.aspose.slides/slideshowtransition/
---
**Dziedziczenie:**  
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**  
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)  
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
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
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Określa, czy kliknięcie myszy przejdzie do następnego slajdu. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Określa, czy kliknięcie myszy przejdzie do następnego slajdu. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Ten atrybut określa, czy pokaz slajdów przejdzie do następnego slajdu po określonym czasie. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Ten atrybut określa, czy pokaz slajdów przejdzie do następnego slajdu po określonym czasie. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Określa czas w milisekundach, po którym ma rozpocząć się przejście. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Określa czas w milisekundach, po którym ma rozpocząć się przejście. |
| [getSpeed()](#getSpeed--) | Określa prędkość przejścia, jaka ma być użyta przy przejściu z bieżącego slajdu do następnego. |
| [setSpeed(int value)](#setSpeed-int-) | Określa prędkość przejścia, jaka ma być użyta przy przejściu z bieżącego slajdu do następnego. |
| [getValue()](#getValue--) | Wartość przejścia pokazu slajdów. |
| [getType()](#getType--) | Typ przejścia. |
| [setType(int value)](#setType-int-) | Typ przejścia. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Określa, czy ten dźwięk jest wbudowany. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Określa, czy ten dźwięk jest wbudowany. |
| [getSoundName()](#getSoundName--) | Określa czytelną nazwę dźwięku przejścia. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Określa czytelną nazwę dźwięku przejścia. |
| [getDuration()](#getDuration--) | Pobiera lub ustawia czas trwania efektu przejścia slajdu w milisekundach. |
| [setDuration(int value)](#setDuration-int-) | Pobiera lub ustawia czas trwania efektu przejścia slajdu w milisekundach. |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy dwie instancje SlideShowTransition są równe. |
| [hashCode()](#hashCode--) | Służy jako funkcja skrótu dla określonego typu, odpowiednia do zastosowań w algorytmach haszowania i strukturach danych, takich jak tabela hash. |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Zwraca lub ustawia osadzone dane audio. Odczyt/zapis [IAudio](../../com.aspose.slides/iaudio).

**Zwraca:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Zwraca lub ustawia osadzone dane audio. Odczyt/zapis [IAudio](../../com.aspose.slides/iaudio).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

Ustawia lub zwraca tryb dźwięku dla przejścia slajdu. Odczyt/zapis [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Zwraca:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

Ustawia lub zwraca tryb dźwięku dla przejścia slajdu. Odczyt/zapis [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

Ten atrybut określa, czy dźwięk będzie się powtarzał, aż do wystąpienia następnego zdarzenia dźwiękowego w pokazie slajdów. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Ten atrybut określa, czy dźwięk będzie się powtarzał, aż do wystąpienia następnego zdarzenia dźwiękowego w pokazie slajdów. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Określa, czy kliknięcie myszy przejdzie do następnego slajdu. Jeśli atrybut nie jest podany, przyjmowana jest wartość true. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Określa, czy kliknięcie myszy przejdzie do następnego slajdu. Jeśli atrybut nie jest podany, przyjmowana jest wartość true. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
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
>          // Pobierz wartość czasu Advance Slide After Time
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
public final void setAdvanceAfter(boolean value)
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
>          // Pobierz wartość czasu Advance Slide After Time
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public final long getAdvanceAfterTime()
```

Określa czas w milisekundach, po którym ma rozpocząć się przejście. To ustawienie może być użyte razem z atrybutem advClick. Jeśli atrybut nie jest podany, przyjmowane jest, że nie nastąpi automatyczne przejście. Odczyt/zapis long.

**Zwraca:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Określa czas w milisekundach, po którym ma rozpocząć się przejście. To ustawienie może być użyte razem z atrybutem advClick. Jeśli atrybut nie jest podany, przyjmowane jest, że nie nastąpi automatyczne przejście. Odczyt/zapis long.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Określa prędkość przejścia, jaka ma być użyta przy przejściu z bieżącego slajdu do następnego. Odczyt/zapis [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Zwraca:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Określa prędkość przejścia, jaka ma być użyta przy przejściu z bieżącego slajdu do następnego. Odczyt/zapis [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

Wartość przejścia pokazu slajdów. Tylko do odczytu [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Zwraca:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public final int getType()
```

Typ przejścia. Odczyt/zapis [TransitionType](../../com.aspose.slides/transitiontype).

**Zwraca:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Typ przejścia. Odczyt/zapis [TransitionType](../../com.aspose.slides/transitiontype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

Określa, czy ten dźwięk jest wbudowany. Jeśli atrybut ma wartość true, aplikacja generująca jest proszona o sprawdzenie atrybutu name określonego dla tego dźwięku na liście wbudowanych dźwięków i może wtedy wyświetlić niestandardową nazwę lub interfejs użytkownika. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Określa, czy ten dźwięk jest wbudowany. Jeśli atrybut ma wartość true, aplikacja generująca jest proszona o sprawdzenie atrybutu name określonego dla tego dźwięku na liście wbudowanych dźwięków i może wtedy wyświetlić niestandardową nazwę lub interfejs użytkownika. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Określa czytelną nazwę dźwięku przejścia. Właściwość Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) musi być przypisana, aby pobrać lub ustawić nazwę dźwięku. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Określa czytelną nazwę dźwięku przejścia. Właściwość Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) musi być przypisana, aby pobrać lub ustawić nazwę dźwięku. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

Pobiera lub ustawia czas trwania efektu przejścia slajdu w milisekundach. Odczyt/zapis int.

--------------------

Odpowiada atrybutowi p14:dur elementu p:transition w schemacie PresentationML. Jeśli nie jest ustawiony, czas trwania jest określany automatycznie na podstawie właściwości \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) oraz typu przejścia.

**Zwraca:**
int

### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Pobiera lub ustawia czas trwania efektu przejścia slajdu w milisekundach. Odczyt/zapis int.

--------------------

Odpowiada atrybutowi p14:dur elementu p:transition w schemacie PresentationML. Jeśli nie jest ustawiony, czas trwania jest określany automatycznie na podstawie właściwości \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) oraz typu przejścia.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Określa, czy dwie instancje SlideShowTransition są równe. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | SlideShowTransition, z którym porównywana jest bieżąca instancja. |

**Zwraca:**
boolean - **true** jeśli podany SlideShowTransition jest równy bieżącemu SlideShowTransition; w przeciwnym razie **false**.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Służy jako funkcja skrótu dla określonego typu, odpowiednia do zastosowań w algorytmach haszowania i strukturach danych, takich jak tabela hash.

**Zwraca:**
int - 23454

--------------------

Zastąpiono, aby kompilator był zadowolony. Zawsze zwraca stałą, ponieważ obiekt jest zmienny.