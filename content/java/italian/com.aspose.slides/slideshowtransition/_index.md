---
title: SlideShowTransition
second_title: Riferimento API di Aspose.Slides per Java
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
| [getSoundMode()](#getSoundMode--) | Imposta o restituisce la modalità sonoro per la transizione della diapositiva. |
| [setSoundMode(int value)](#setSoundMode-int-) | Imposta o restituisce la modalità sonoro per la transizione della diapositiva. |
| [getSoundLoop()](#getSoundLoop--) | Questo attributo specifica se il suono verrà ripetuto fino a quando non si verifica il prossimo evento sonoro nella presentazione. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Questo attributo specifica se il suono verrà ripetuto fino a quando non si verifica il prossimo evento sonoro nella presentazione. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Specifica se un clic del mouse avanzerà la diapositiva o meno. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Specifica se un clic del mouse avanzerà la diapositiva o meno. |
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
| [getSoundName()](#getSoundName--) | Specifica un nome leggibile dall'uomo per il suono della transizione. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Specifica un nome leggibile dall'uomo per il suono della transizione. |
| [getDuration()](#getDuration--) | Ottiene o imposta la durata dell'effetto di transizione della diapositiva in millisecondi. |
| [setDuration(int value)](#setDuration-int-) | Ottiene o imposta la durata dell'effetto di transizione della diapositiva in millisecondi. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se le due istanze di SlideShowTransition sono uguali. |
| [hashCode()](#hashCode--) | Funge da funzione hash per un tipo particolare, adatta all'uso in algoritmi di hashing e strutture dati come una tabella hash. |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Restituisce o imposta i dati audio incorporati. Lettura/Scrittura [IAudio](../../com.aspose.slides/iaudio).

**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Restituisce o imposta i dati audio incorporati. Lettura/Scrittura [IAudio](../../com.aspose.slides/iaudio).

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

Imposta o restituisce la modalità sonoro per la transizione della diapositiva. Lettura/Scrittura [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Restituisce:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

Imposta o restituisce la modalità sonoro per la transizione della diapositiva. Lettura/Scrittura [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

Questo attributo specifica se il suono verrà ripetuto fino a quando non si verifica il prossimo evento sonoro nella presentazione. Lettura/Scrittura booleano.

**Restituisce:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Questo attributo specifica se il suono verrà ripetuto fino a quando non si verifica il prossimo evento sonoro nella presentazione. Lettura/Scrittura booleano.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Specifica se un clic del mouse avanzerà la diapositiva o meno. Se questo attributo non è specificato, si assume il valore vero. Lettura/Scrittura booleano.

**Restituisce:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Specifica se un clic del mouse avanzerà la diapositiva o meno. Se questo attributo non è specificato, si assume il valore vero. Lettura/Scrittura booleano.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

Questo attributo specifica se la presentazione passerà alla diapositiva successiva dopo un certo intervallo di tempo. Lettura/Scrittura booleano.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Ottieni la prima transizione della diapositiva
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Verifica se il flag Avanzamento diapositiva dopo è selezionato
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Ottieni il valore del tempo di avanzamento della diapositiva dopo
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

Questo attributo specifica se la presentazione passerà alla diapositiva successiva dopo un certo intervallo di tempo. Lettura/Scrittura booleano.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Ottieni la prima transizione della diapositiva
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Verifica se il flag Avanzamento diapositiva dopo è selezionato
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Ottieni il valore del tempo di avanzamento della diapositiva dopo
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public final long getAdvanceAfterTime()
```

Specific

a il tempo, in millisecondi, dopo il quale la transizione dovrebbe iniziare. Questa impostazione può essere usata in combinazione con l'attributo advClick. Se questo attributo non è specificato, si assume che non avverrà alcun avanzamento automatico. Lettura/Scrittura long.

**Restituisce:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Specific

a il tempo, in millisecondi, dopo il quale la transizione dovrebbe iniziare. Questa impostazione può essere usata in combinazione con l'attributo advClick. Se questo attributo non è specificato, si assume che non avverrà alcun avanzamento automatico. Lettura/Scrittura long.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Specific

a la velocità di transizione da utilizzare quando si passa dalla diapositiva corrente a quella successiva. Lettura/Scrittura [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Restituisce:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Specific

a la velocità di transizione da utilizzare quando si passa dalla diapositiva corrente a quella successiva. Lettura/Scrittura [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parametri:**
| Parameter | Type | Description |
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

Tipo di transizione. Lettura/Scrittura [TransitionType](../../com.aspose.slides/transitiontype).

**Restituisce:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Tipo di transizione. Lettura/Scrittura [TransitionType](../../com.aspose.slides/transitiontype).

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

Specific

a se questo suono è integrato o meno. Se questo attributo è impostato su true, l'applicazione generatrice viene avvisata di controllare l'attributo name specificato per questo suono nella sua lista di suoni integrati e può quindi mostrare un nome personalizzato o un'interfaccia utente secondo necessità. Lettura/Scrittura booleano.

**Restituisce:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Specific

a se questo suono è integrato o meno. Se questo attributo è impostato su true, l'applicazione generatrice viene avvisata di controllare l'attributo name specificato per questo suono nella sua lista di suoni integrati e può quindi mostrare un nome personalizzato o un'interfaccia utente secondo necessità. Lettura/Scrittura booleano.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Specific

a un nome leggibile dall'uomo per il suono della transizione. La proprietà Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) deve essere assegnata per ottenere o impostare il nome del suono. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Specific

a un nome leggibile dall'uomo per il suono della transizione. La proprietà Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) deve essere assegnata per ottenere o impostare il nome del suono. Lettura/Scrittura String.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

Ottiene o imposta la durata dell'effetto di transizione della diapositiva in millisecondi. Lettura/Scrittura int.

--------------------

Corrisponde all'attributo p14:dur dell'elemento p:transition nello schema PresentationML. Se non impostato, la durata viene determinata automaticamente in base alla proprietà \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) e al tipo di transizione.

**Restituisce:**
int

### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Ottiene o imposta la durata dell'effetto di transizione della diapositiva in millisecondi. Lettura/Scrittura int.

--------------------

Corrisponde all'attributo p14:dur dell'elemento p:transition nello schema PresentationML. Se non impostato, la durata viene determinata automaticamente in base alla proprietà \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) e al tipo di transizione.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina se le due istanze di SlideShowTransition sono uguali. Lettura/Scrittura booleano.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Lo SlideShowTransition da confrontare con l'attuale SlideShowTransition. |

**Restituisce:**
boolean - **true** se lo SlideShowTransition specificato è uguale allo SlideShowTransition corrente; altrimenti, **false**.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Funge da funzione hash per un tipo particolare, adatta all'uso in algoritmi di hashing e strutture dati come una tabella hash.

**Restituisce:**
int - 23454

--------------------

La sovrascrittura per soddisfare il compilatore. Restituisce sempre una costante perché l'oggetto è mutabile.