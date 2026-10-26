---
title: ISlideShowTransition
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta la transizione della presentazione.
type: docs
url: /it/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

Rappresenta la transizione della presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSound()](#getSound--) | Restituisce o imposta i dati audio incorporati. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Restituisce o imposta i dati audio incorporati. |
| [getSoundMode()](#getSoundMode--) | Imposta o restituisce la modalità audio per la transizione della diapositiva. |
| [setSoundMode(int value)](#setSoundMode-int-) | Imposta o restituisce la modalità audio per la transizione della diapositiva. |
| [getSoundLoop()](#getSoundLoop--) | Questo attributo specifica se l'audio verrà ripetuto fino a quando non si verifica il prossimo evento audio nella presentazione. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Questo attributo specifica se l'audio verrà ripetuto fino a quando non si verifica il prossimo evento audio nella presentazione. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Specifica se un clic del mouse avanzerà la diapositiva o meno. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Specifica se un clic del mouse avanzerà la diapositiva o meno. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Questo attributo specifica se la presentazione passerà alla diapositiva successiva dopo un determinato intervallo di tempo. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Questo attributo specifica se la presentazione passerà alla diapositiva successiva dopo un determinato intervallo di tempo. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Specifica il tempo, in millisecondi, dopo il quale la transizione deve avviarsi. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Specifica il tempo, in millisecondi, dopo il quale la transizione deve avviarsi. |
| [getSpeed()](#getSpeed--) | Specifica la velocità di transizione da utilizzare quando si passa dalla diapositiva corrente a quella successiva. |
| [setSpeed(int value)](#setSpeed-int-) | Specifica la velocità di transizione da utilizzare quando si passa dalla diapositiva corrente a quella successiva. |
| [getValue()](#getValue--) | Valore della transizione della presentazione. |
| [getType()](#getType--) | Tipo di transizione. |
| [setType(int value)](#setType-int-) | Tipo di transizione. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Specifica se questo audio è un suono incorporato o meno. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Specifica se questo audio è un suono incorporato o meno. |
| [getSoundName()](#getSoundName--) | Specifica un nome leggibile per l'audio della transizione. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Specifica un nome leggibile per l'audio della transizione. |
| [getDuration()](#getDuration--) | Ottiene o imposta la durata dell'effetto di transizione della diapositiva in millisecondi. |
| [setDuration(int value)](#setDuration-int-) | Ottiene o imposta la durata dell'effetto di transizione della diapositiva in millisecondi. |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Restituisce o imposta i dati audio incorporati. Lettura-scrittura [IAudio](../../com.aspose.slides/iaudio).

**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Restituisce o imposta i dati audio incorporati. Lettura-scrittura [IAudio](../../com.aspose.slides/iaudio).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

Imposta o restituisce la modalità audio per la transizione della diapositiva. Lettura-scrittura [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Restituisce:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

Imposta o restituisce la modalità audio per la transizione della diapositiva. Lettura-scrittura [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

Questo attributo specifica se l'audio verrà ripetuto fino a quando non si verifica il prossimo evento audio nella presentazione. Lettura-scrittura boolean.

**Restituisce:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

Questo attributo specifica se l'audio verrà ripetuto fino a quando non si verifica il prossimo evento audio nella presentazione. Lettura-scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

Specifică se un clic del mouse avanzerà la diapositiva o meno. Se questo attributo non è specificato, si assume il valore true. Lettura-scrittura boolean.

**Restituisce:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

Specifică se un clic del mouse avanzerà la diapositiva o meno. Se questo attributo non è specificato, si assume il valore true. Lettura-scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

Questo attributo specifica se la presentazione passerà alla diapositiva successiva dopo un determinato intervallo di tempo. Lettura/scrittura boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Ottieni la prima transizione della diapositiva
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Verifica se il flag Avanzamento diapositiva dopo è impostato
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Ottieni il valore del tempo di avanzamento della diapositiva
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
public abstract void setAdvanceAfter(boolean value)
```

Questo attributo specifica se la presentazione passerà alla diapositiva successiva dopo un determinato intervallo di tempo. Lettura/scrittura boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Ottieni la prima transizione della diapositiva
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Verifica se il flag Avanzamento diapositiva dopo è impostato
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Ottieni il valore del tempo di avanzamento della diapositiva
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
public abstract long getAdvanceAfterTime()
```

Specifică il tempo, in millisecondi, dopo il quale la transizione deve avviarsi. Questa impostazione può essere usata in combinazione con l'attributo advClick. Se questo attributo non è specificato, si assume che non avverrà alcun avanzamento automatico. Lettura-scrittura long.

**Restituisce:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

Specifică il tempo, in millisecondi, dopo il quale la transizione deve avviarsi. Questa impostazione può essere usata in combinazione con l'attributo advClick. Se questo attributo non è specificato, si assume che non avverrà alcun avanzamento automatico. Lettura-scrittura long.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |
### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

Specifică la velocità di transizione da utilizzare quando si passa dalla diapositiva corrente a quella successiva. Lettura-scrittura [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Restituisce:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

Specifică la velocità di transizione da utilizzare quando si passa dalla diapositiva corrente a quella successiva. Lettura-scrittura [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

Valore della transizione della presentazione. Solo lettura [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Restituisce:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```

Tipo di transizione. Lettura-scrittura [TransitionType](../../com.aspose.slides/transitiontype).

**Restituisce:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Tipo di transizione. Lettura-scrittura [TransitionType](../../com.aspose.slides/transitiontype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

Specifică se questo audio è un suono incorporato o meno. Se questo attributo è impostato a true, l'applicazione generatrice viene avvisata di controllare l'attributo name specificato per questo audio nella sua lista di suoni incorporati e può quindi visualizzare un nome personalizzato o un'interfaccia utente secondo necessità. Lettura-scrittura boolean.

**Restituisce:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

Specifică se questo audio è un suono incorporato o meno. Se questo attributo è impostato a true, l'applicazione generatrice viene avvisata di controllare l'attributo name specificato per questo audio nella sua lista di suoni incorporati e può quindi visualizzare un nome personalizzato o un'interfaccia utente secondo necessità. Lettura-scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

Specifică un nome leggibile per l'audio della transizione. La proprietà (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) deve essere assegnata per ottenere o impostare il nome dell'audio. Lettura-scrittura String.

**Restituisce:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

Specifică un nome leggibile per l'audio della transizione. La proprietà \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) deve essere assegnata per ottenere o impostare il nome dell'audio. Lettura-scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

Ottiene o imposta la durata dell'effetto di transizione della diapositiva in millisecondi. Lettura/scrittura int.

--------------------

Corrisponde all'attributo p14:dur dell'elemento p:transition nello schema PresentationML. Se non impostato, la durata viene determinata automaticamente in base alla proprietà \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) e al tipo di transizione.

**Restituisce:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

Ottiene o imposta la durata dell'effetto di transizione della diapositiva in millisecondi. Lettura/scrittura int.

--------------------

Corrisponde all'attributo p14:dur dell'elemento p:transition nello schema PresentationML. Se non impostato, la durata viene determinata automaticamente in base alla proprietà \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) e al tipo di transizione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |