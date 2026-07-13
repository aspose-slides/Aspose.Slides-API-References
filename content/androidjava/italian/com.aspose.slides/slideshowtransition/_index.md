---
title: SlideShowTransition
second_title: Riferimento API di Aspose.Slides per Android via Java
description: Rappresenta la transizione della presentazione.
type: docs
url: /it/com.aspose.slides/slideshowtransition/
---
**Ereditarietà:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

Rappresenta la transizione della presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSound()](#getSound--) | Restituisce o imposta i dati audio incorporati. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Restituisce o imposta i dati audio incorporati. |
| [getSoundMode()](#getSoundMode--) | Imposta o restituisce la modalità del suono per la transizione della diapositiva. |
| [setSoundMode(int value)](#setSoundMode-int-) | Imposta o restituisce la modalità del suono per la transizione della diapositiva. |
| [getSoundLoop()](#getSoundLoop--) | Questo attributo specifica se il suono verrà ripetuto fino al verificarsi del prossimo evento sonoro nella presentazione. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Questo attributo specifica se il suono verrà ripetuto fino al verificarsi del prossimo evento sonoro nella presentazione. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Specifica se un clic del mouse farà avanzare la diapositiva o meno. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Specifica se un clic del mouse farà avanzare la diapositiva o meno. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Questo attributo specifica se la presentazione passerà alla diapositiva successiva dopo un certo intervallo di tempo. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Questo attributo specifica se la presentazione passerà alla diapositiva successiva dopo un certo intervallo di tempo. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Specifica il tempo, in millisecondi, dopo il quale la transizione dovrebbe iniziare. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Specifica il tempo, in millisecondi, dopo il quale la transizione dovrebbe iniziare. |
| [getSpeed()](#getSpeed--) | Specifica la velocità di transizione da utilizzare quando si passa dalla diapositiva corrente a quella successiva. |
| [setSpeed(int value)](#setSpeed-int-) | Specifica la velocità di transizione da utilizzare quando si passa dalla diapositiva corrente a quella successiva. |
| [getValue()](#getValue--) | Valore della transizione della presentazione. |
| [getType()](#getType--) | Tipo di transizione. |
| [setType(int value)](#setType-int-) | Tipo di transizione. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Specifica se questo suono è integrato o meno. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Specifica se questo suono è integrato o meno. |
| [getSoundName()](#getSoundName--) | Specifica un nome leggibile per l'uomo per il suono della transizione. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Specifica un nome leggibile per l'uomo per il suono della transizione. |
| [getDuration()](#getDuration--) | Ottiene o imposta la durata dell'effetto di transizione della diapositiva in millisecondi. |
| [setDuration(int value)](#setDuration-int-) | Ottiene o imposta la durata dell'effetto di transizione della diapositiva in millisecondi. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se le due istanze SlideShowTransition sono uguali. |
| [hashCode()](#hashCode--) | Funziona come funzione di hash per un determinato tipo, adatta all'uso in algoritmi di hashing e strutture dati come una tabella hash. |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Restituisce o imposta i dati audio incorporati. Lettura/scrittura [IAudio](../../com.aspose.slides/iaudio).

**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Restituisce o imposta i dati audio incorporati. Lettura/scrittura [IAudio](../../com.aspose.slides/iaudio).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

Imposta o restituisce la modalità del suono per la transizione della diapositiva. Lettura/scrittura [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Restituisce:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

Imposta o restituisce la modalità del suono per la transizione della diapositiva. Lettura/scrittura [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

Questo attributo specifica se il suono verrà ripetuto fino al verificarsi del prossimo evento sonoro nella presentazione. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Questo attributo specifica se il suono verrà ripetuto fino al verificarsi del prossimo evento sonoro nella presentazione. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Specifica se un clic del mouse farà avanzare la diapositiva o meno. Se questo attributo non è specificato, si assume un valore true. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Specifica se un clic del mouse farà avanzare la diapositiva o meno. Se questo attributo non è specificato, si assume un valore true. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

Questo attributo specifica se la presentazione passerà alla diapositiva successiva dopo un certo intervallo di tempo. Lettura/scrittura boolean.

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

**Restituisce:**
boolean

### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public final void setAdvanceAfter(boolean value)
```

Questo attributo specifica se la presentazione passerà alla diapositiva successiva dopo un certo intervallo di tempo. Lettura/scrittura boolean.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public final long getAdvanceAfterTime()
```

Specifica il tempo, in millisecondi, dopo il quale la transizione dovrebbe iniziare. Questa impostazione può essere usata insieme all'attributo advClick. Se questo attributo non è specificato, si assume che non avverrà alcun avanzamento automatico. Lettura/scrittura long.

**Restituisce:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Specifica il tempo, in millisecondi, dopo il quale la transizione dovrebbe iniziare. Questa impostazione può essere usata insieme all'attributo advClick. Se questo attributo non è specificato, si assume che non avverrà alcun avanzamento automatico. Lettura/scrittura long.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Specifica la velocità di transizione da utilizzare quando si passa dalla diapositiva corrente a quella successiva. Lettura/scrittura [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Restituisce:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Specifica la velocità di transizione da utilizzare quando si passa dalla diapositiva corrente a quella successiva. Lettura/scrittura [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

Valore della transizione della presentazione. Solo lettura [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Restituisce:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public final int getType()
```

Tipo di transizione. Lettura/scrittura [TransitionType](../../com.aspose.slides/transitiontype).

**Restituisce:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Tipo di transizione. Lettura/scrittura [TransitionType](../../com.aspose.slides/transitiontype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

Specifica se questo suono è integrato o meno. Se questo attributo è impostato a true, l'applicazione generatrice verrà avvisata di controllare l'attributo name specificato per questo suono nella sua lista di suoni integrati e potrà quindi mostrare un nome personalizzato o un'interfaccia utente secondo necessità. Lettura-scrittura boolean.

**Restituisce:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Specifica se questo suono è integrato o meno. Se questo attributo è impostato a true, l'applicazione generatrice verrà avvisata di controllare l'attributo name specificato per questo suono nella sua lista di suoni integrati e potrà quindi mostrare un nome personalizzato o un'interfaccia utente secondo necessità. Lettura-scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Specifica un nome leggibile per l'uomo per il suono della transizione. La proprietà Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) deve essere assegnata per ottenere o impostare il nome del suono. Lettura-scrittura String.

**Restituisce:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Specifica un nome leggibile per l'uomo per il suono della transizione. La proprietà Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) deve essere assegnata per ottenere o impostare il nome del suono. Lettura-scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

Ottiene o imposta la durata dell'effetto di transizione della diapositiva in millisecondi. Lettura/scrittura int.

--------------------

Corrisponde all'attributo p14:dur dell'elemento p:transition nello schema PresentationML. Se non impostato, la durata è determinata automaticamente in base alla proprietà \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) e al tipo di transizione.

**Restituisce:**
int

### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Ottiene o imposta la durata dell'effetto di transizione della diapositiva in millisecondi. Lettura/scrittura int.

--------------------

Corrisponde all'attributo p14:dur dell'elemento p:transition nello schema PresentationML. Se non impostato, la durata è determinata automaticamente in base alla proprietà \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) e al tipo di transizione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina se le due istanze SlideShowTransition sono uguali. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Lo SlideShowTransition da confrontare con lo SlideShowTransition corrente. |

**Restituisce:**
boolean -  **true**  se lo SlideShowTransition specificato è uguale allo SlideShowTransition corrente; altrimenti,  **false** .

### hashCode() {#hashCode--}
```
public int hashCode()
```

Funziona come funzione di hash per un determinato tipo, adatta all'uso in algoritmi di hashing e strutture dati come una tabella hash.

**Restituisce:**
int - 23454

--------------------

Sovrascritto per rendere felice il compilatore. Restituisce sempre una costante perché l'oggetto è mutabile.