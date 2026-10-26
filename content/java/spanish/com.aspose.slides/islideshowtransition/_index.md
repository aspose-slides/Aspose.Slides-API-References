---
title: ISlideShowTransition
second_title: Aspose.Slides for Java API Reference
description: Represents slide show transition.
type: docs
url: /es/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

Represents slide show transition.
## Métodos

| Método | Descripción |
| --- | --- |
| [getSound()](#getSound--) | Obtiene o establece los datos de audio incrustados. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Obtiene o establece los datos de audio incrustados. |
| [getSoundMode()](#getSoundMode--) | Establece o devuelve el modo de sonido para la transición de diapositiva. |
| [setSoundMode(int value)](#setSoundMode-int-) | Establece o devuelve el modo de sonido para la transición de diapositiva. |
| [getSoundLoop()](#getSoundLoop--) | Este atributo especifica si el sonido se repetirá hasta que ocurra el siguiente evento de sonido en la presentación. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Este atributo especifica si el sonido se repetirá hasta que ocurra el siguiente evento de sonido en la presentación. |
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
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Especifica si este sonido es interno o no. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Especifica si este sonido es interno o no. |
| [getSoundName()](#getSoundName--) | Especifica un nombre legible para el sonido de la transición. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Especifica un nombre legible para el sonido de la transición. |
| [getDuration()](#getDuration--) | Obtiene o establece la duración del efecto de transición de la diapositiva en milisegundos. |
| [setDuration(int value)](#setDuration-int-) | Obtiene o establece la duración del efecto de transición de la diapositiva en milisegundos. |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


Obtiene o establece los datos de audio incrustados. Lectura-escritura [IAudio](../../com.aspose.slides/iaudio).

**Devuelve:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```


Obtiene o establece los datos de audio incrustados. Lectura-escritura [IAudio](../../com.aspose.slides/iaudio).

**Parámetros:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```


Este atributo especifica si el sonido se repetirá hasta que ocurra el siguiente evento de sonido en la presentación. Lectura-escritura booleano.

**Devuelve:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```


Este atributo especifica si el sonido se repetirá hasta que ocurra el siguiente evento de sonido en la presentación. Lectura-escritura booleano.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```


Especifica si un clic del ratón avanzará la diapositiva o no. Si este atributo no se especifica, se asume un valor verdadero. Lectura-escritura booleano.

**Devuelve:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```


Especifica si un clic del ratón avanzará la diapositiva o no. Si este atributo no se especifica, se asume un valor verdadero. Lectura-escritura booleano.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```


Este atributo especifica si la presentación avanzará a la siguiente diapositiva después de un tiempo determinado. Lectura/escritura booleano.

--------------------

> ```markdown
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Obtiene la primera transición de diapositiva
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Verifica si la bandera Avanzar diapositiva después está marcada
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Obtiene el valor del tiempo de avance de la diapositiva
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


Este atributo especifica si la presentación avanzará a la siguiente diapositiva después de un tiempo determinado. Lectura/escritura booleano.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Obtiene la primera transición de diapositiva
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Verifica si la bandera Avanzar diapositiva después está marcada
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Obtiene el valor del tiempo de avance de la diapositiva
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```


Especifica el tiempo, en milisegundos, después del cual debe iniciarse la transición. Esta configuración puede usarse junto con el atributo advClick. Si este atributo no se especifica, se asume que no ocurrirá avance automático. Lectura-escritura largo.

**Devuelve:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```


Especifica el tiempo, en milisegundos, después del cual debe iniciarse la transición. Esta configuración puede usarse junto con el atributo advClick. Si este atributo no se especifica, se asume que no ocurrirá avance automático. Lectura-escritura largo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```


Especifica si este sonido es interno o no. Si este atributo se establece a verdadero, la aplicación generadora se alerta para comprobar el atributo name especificado para este sonido en su lista de sonidos internos y puede entonces mostrar un nombre personalizado o una UI según sea necesario. Lectura-escritura booleano.

**Devuelve:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```


Especifica si este sonido es interno o no. Si este atributo se establece a verdadero, la aplicación generadora se alerta para comprobar el atributo name especificado para este sonido en su lista de sonidos internos y puede entonces mostrar un nombre personalizado o una UI según sea necesario. Lectura-escritura booleano.

**Parámetros:**
| Parámetro | Tipo | Descripción |
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


Especifica un nombre legible para el sonido de la transición. La propiedad \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) debe asignarse para obtener o establecer el nombre del sonido. Lectura-escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```


Obtiene o establece la duración del efecto de transición de la diapositiva en milisegundos. Lectura/escritura int.

--------------------

Corresponde al atributo p14:dur del elemento p:transition en el esquema PresentationML. Si no se establece, la duración se determina automáticamente basándose en la propiedad \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) y el tipo de transición.

**Devuelve:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```


Obtiene o establece la duración del efecto de transición de la diapositiva en milisegundos. Lectura/escritura int.

--------------------

Corresponde al atributo p14:dur del elemento p:transition en el esquema PresentationML. Si no se establece, la duración se determina automáticamente basándose en la propiedad \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) y el tipo de transición.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |