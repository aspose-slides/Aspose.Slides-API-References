---
title: ISlideShowTransition
second_title: Aspose.Slides for Android via Java API Reference
description: Representa la transición de la presentación.
type: docs
url: /es/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

Representa la transición de la presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getSound()](#getSound--) | Devuelve o establece los datos de audio incrustados. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Devuelve o establece los datos de audio incrustados. |
| [getSoundMode()](#getSoundMode--) | Establece o devuelve el modo de sonido para la transición de diapositiva. |
| [setSoundMode(int value)](#setSoundMode-int-) | Establece o devuelve el modo de sonido para la transición de diapositiva. |
| [getSoundLoop()](#getSoundLoop--) | Este atributo especifica si el sonido se reproducirá en bucle hasta que ocurra el siguiente evento de sonido en la presentación. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Este atributo especifica si el sonido se reproducirá en bucle hasta que ocurra el siguiente evento de sonido en la presentación. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Especifica si un clic del ratón avanzará la diapositiva o no. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Especifica si un clic del ratón avanzará la diapositiva o no. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Este atributo especifica si la presentación avanzará a la siguiente diapositiva después de un tiempo determinado. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Este atributo especifica si la presentación avanzará a la siguiente diapositiva después de un tiempo determinado. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Especifica el tiempo, en milisegundos, después del cual debe iniciarse la transición. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Especifica el tiempo, en milisegundos, después del cual debe iniciarse la transición. |
| [getSpeed()](#getSpeed--) | Especifica la velocidad de transición que se utilizará al pasar de la diapositiva actual a la siguiente. |
| [setSpeed(int value)](#setSpeed-int-) | Especifica la velocidad de transición que se utilizará al pasar de la diapositiva actual a la siguiente. |
| [getValue()](#getValue--) | Valor de transición de la presentación. |
| [getType()](#getType--) | Tipo de transición. |
| [setType(int value)](#setType-int-) | Tipo de transición. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Especifica si este sonido es un sonido incorporado o no. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Especifica si este sonido es un sonido incorporado o no. |
| [getSoundName()](#getSoundName--) | Especifica un nombre legible para el sonido de la transición. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Especifica un nombre legible para el sonido de la transición. |
| [getDuration()](#getDuration--) | Obtiene o establece la duración del efecto de transición de diapositiva en milisegundos. |
| [setDuration(int value)](#setDuration-int-) | Obtiene o establece la duración del efecto de transición de diapositiva en milisegundos. |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Devuelve o establece los datos de audio incrustados. Lectura-escritura [IAudio](../../com.aspose.slides/iaudio).

**Devuelve:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Devuelve o establece los datos de audio incrustados. Lectura-escritura [IAudio](../../com.aspose.slides/iaudio).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

Establece o devuelve el modo de sonido para la transición de diapositiva. Lectura-escritura [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Devuelve:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

Establece o devuelve el modo de sonido para la transición de diapositiva. Lectura-escritura [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

Este atributo especifica si el sonido se reproducirá en bucle hasta que ocurra el siguiente evento de sonido en la presentación. Lectura-escritura boolean.

**Devuelve:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

Este atributo especifica si el sonido se reproducirá en bucle hasta que ocurra el siguiente evento de sonido en la presentación. Lectura-escritura boolean.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

Especifica si un clic del ratón avanzará la diapositiva o no. Si este atributo no se especifica, se asume un valor true. Lectura-escritura boolean.

**Devuelve:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

Especifica si un clic del ratón avanzará la diapositiva o no. Si este atributo no se especifica, se asume un valor true. Lectura-escritura boolean.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

Este atributo especifica si la presentación avanzará a la siguiente diapositiva después de un tiempo determinado. Lectura/escritura boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Obtener la primera transición de diapositiva
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Verificar si la bandera Avanzar diapositiva después está marcada
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Obtener el valor del tiempo de avance de diapositiva después
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```

Este atributo especifica si la presentación avanzará a la siguiente diapositiva después de un tiempo determinado. Lectura/escritura boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Obtener la primera transición de diapositiva
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Verificar si la bandera Avanzar diapositiva después está marcada
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Obtener el valor del tiempo de avance de diapositiva después
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```

Especifica el tiempo, en milisegundos, después del cual debe iniciarse la transición. Esta configuración puede usarse en conjunto con el atributo advClick. Si este atributo no se especifica, se asume que no ocurrirá avance automático. Lectura-escritura long.

**Devuelve:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

Especifica el tiempo, en milisegundos, después del cual debe iniciarse la transición. Esta configuración puede usarse en conjunto con el atributo advClick. Si este atributo no se especifica, se asume que no ocurrirá avance automático. Lectura-escritura long.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |
### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

Especifica la velocidad de transición que se utilizará al pasar de la diapositiva actual a la siguiente. Lectura-escritura [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Devuelve:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

Especifica la velocidad de transición que se utilizará al pasar de la diapositiva actual a la siguiente. Lectura-escritura [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

Valor de transición de la presentación. Solo lectura [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Devuelve:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```

Tipo de transición. Lectura-escritura [TransitionType](../../com.aspose.slides/transitiontype).

**Devuelve:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Tipo de transición. Lectura-escritura [TransitionType](../../com.aspose.slides/transitiontype).

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

Especifica si este sonido es un sonido incorporado o no. Si este atributo se establece en true, la aplicación generadora debe comprobar el atributo name especificado para este sonido en su lista de sonidos incorporados y puede presentar un nombre personalizado o UI según sea necesario. Lectura-escritura boolean.

**Devuelve:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

Especifica si este sonido es un sonido incorporado o no. Si este atributo se establece en true, la aplicación generadora debe comprobar el atributo name especificado para este sonido en su lista de sonidos incorporados y puede presentar un nombre personalizado o UI según sea necesario. Lectura-escritura boolean.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

Especifica un nombre legible para el sonido de la transición. La propiedad (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) debe asignarse para obtener o establecer el nombre del sonido. Lectura-escritura String.

**Devuelve:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

Especifica un nombre legible para el sonido de la transición. La propiedad (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) debe asignarse para obtener o establecer el nombre del sonido. Lectura-escritura String.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

Obtiene o establece la duración del efecto de transición de diapositiva en milisegundos. Lectura/escritura int.

--------------------

Corresponde al atributo p14:dur del elemento p:transition en el esquema PresentationML. Si no se establece, la duración se determina automáticamente en función de la propiedad \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) y del tipo de transición.

**Devuelve:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

Obtiene o establece la duración del efecto de transición de diapositiva en milisegundos. Lectura/escritura int.

--------------------

Corresponde al atributo p14:dur del elemento p:transition en el esquema PresentationML. Si no se establece, la duración se determina automáticamente en función de la propiedad \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) y del tipo de transición.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |