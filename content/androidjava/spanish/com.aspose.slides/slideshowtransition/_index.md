---
title: SlideShowTransition
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa la transición de la presentación de diapositivas.
type: docs
url: /es/com.aspose.slides/slideshowtransition/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

Representa la transición de la presentación de diapositivas.
## Métodos

| Método | Descripción |
| --- | --- |
| [getSound()](#getSound--) | Devuelve o establece los datos de audio incrustados. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Devuelve o establece los datos de audio incrustados. |
| [getSoundMode()](#getSoundMode--) | Establece o devuelve el modo de sonido para la transición de diapositivas. |
| [setSoundMode(int value)](#setSoundMode-int-) | Establece o devuelve el modo de sonido para la transición de diapositivas. |
| [getSoundLoop()](#getSoundLoop--) | Este atributo especifica si el sonido se reproducirá en bucle hasta que ocurra el siguiente evento de sonido en la presentación. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Este atributo especifica si el sonido se reproducirá en bucle hasta que ocurra el siguiente evento de sonido en la presentación. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Especifica si un clic del ratón avanzará la diapositiva o no. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Especifica si un clic del ratón avanzará la diapositiva o no. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Este atributo especifica si la presentación avanzará a la siguiente diapositiva después de un tiempo determinado. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Este atributo especifica si la presentación avanzará a la siguiente diapositiva después de un tiempo determinado. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Especifica el tiempo, en milisegundos, después del cual la transición debe comenzar. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Especifica el tiempo, en milisegundos, después del cual la transición debe comenzar. |
| [getSpeed()](#getSpeed--) | Especifica la velocidad de transición que se debe usar al pasar de la diapositiva actual a la siguiente. |
| [setSpeed(int value)](#setSpeed-int-) | Especifica la velocidad de transición que se debe usar al pasar de la diapositiva actual a la siguiente. |
| [getValue()](#getValue--) | Valor de transición de la presentación de diapositivas. |
| [getType()](#getType--) | Tipo de transición. |
| [setType(int value)](#setType-int-) | Tipo de transición. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Especifica si este sonido es un sonido incorporado o no. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Especifica si este sonido es un sonido incorporado o no. |
| [getSoundName()](#getSoundName--) | Especifica un nombre legible para el sonido de la transición. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Especifica un nombre legible para el sonido de la transición. |
| [getDuration()](#getDuration--) | Obtiene o establece la duración del efecto de transición de diapositivas en milisegundos. |
| [setDuration(int value)](#setDuration-int-) | Obtiene o establece la duración del efecto de transición de diapositivas en milisegundos. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si dos instancias de SlideShowTransition son iguales. |
| [hashCode()](#hashCode--) | Sirve como función hash para un tipo particular, adecuada para su uso en algoritmos de hash y estructuras de datos como una tabla hash. |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Devuelve o establece los datos de audio incrustados. Lectura/escritura [IAudio](../../com.aspose.slides/iaudio).

**Devuelve:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Devuelve o establece los datos de audio incrustados. Lectura/escritura [IAudio](../../com.aspose.slides/iaudio).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

Establece o devuelve el modo de sonido para la transición de diapositivas. Lectura/escritura [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Devuelve:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

Establece o devuelve el modo de sonido para la transición de diapositivas. Lectura/escritura [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

Este atributo especifica si el sonido se reproducirá en bucle hasta que ocurra el siguiente evento de sonido en la presentación. Lectura/escritura boolean.

**Devuelve:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Este atributo especifica si el sonido se reproducirá en bucle hasta que ocurra el siguiente evento de sonido en la presentación. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Especifica si un clic del ratón avanzará la diapositiva o no. Si este atributo no se especifica, se asume un valor verdadero. Lectura/escritura boolean.

**Devuelve:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Especifica si un clic del ratón avanzará la diapositiva o no. Si este atributo no se especifica, se asume un valor verdadero. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

Este atributo especifica si la presentación avanzará a la siguiente diapositiva después de un tiempo determinado. Lectura/escritura boolean.

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
>          // Obtiene el valor del tiempo de avanzar diapositiva después
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
public final void setAdvanceAfter(boolean value)
```

Este atributo especifica si la presentación avanzará a la siguiente diapositiva después de un tiempo determinado. Lectura/escritura boolean.

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
>          // Obtiene el valor del tiempo de avanzar diapositiva después
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
public final long getAdvanceAfterTime()
```

Especifica el tiempo, en milisegundos, después del cual la transición debe comenzar. Esta configuración puede usarse junto con el atributo advClick. Si este atributo no se especifica, se asume que no ocurrirá avance automático. Lectura/escritura long.

**Devuelve:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Especifica el tiempo, en milisegundos, después del cual la transición debe comenzar. Esta configuración puede usarse junto con el atributo advClick. Si este atributo no se especifica, se asume que no ocurrirá avance automático. Lectura/escritura long.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Especifica la velocidad de transición que se debe usar al pasar de la diapositiva actual a la siguiente. Lectura/escritura [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Devuelve:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Especifica la velocidad de transición que se debe usar al pasar de la diapositiva actual a la siguiente. Lectura/escritura [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

Valor de transición de la presentación de diapositivas. Solo lectura [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Devuelve:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public final int getType()
```

Tipo de transición. Lectura/escritura [TransitionType](../../com.aspose.slides/transitiontype).

**Devuelve:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Tipo de transición. Lectura/escritura [TransitionType](../../com.aspose.slides/transitiontype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

Especifica si este sonido es un sonido incorporado o no. Si este atributo se establece en true, la aplicación generadora se avisa para comprobar el atributo name especificado para este sonido en su lista de sonidos incorporados y puede entonces mostrar un nombre personalizado o una UI según sea necesario. Lectura-escritura boolean.

**Devuelve:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Especifica si este sonido es un sonido incorporado o no. Si este atributo se establece en true, la aplicación generadora se avisa para comprobar el atributo name especificado para este sonido en su lista de sonidos incorporados y puede entonces mostrar un nombre personalizado o una UI según sea necesario. Lectura-escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Especifica un nombre legible para el sonido de la transición. La propiedad Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) debe asignarse para obtener o establecer el nombre del sonido. Lectura-escritura String.

**Devuelve:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Especifica un nombre legible para el sonido de la transición. La propiedad Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) debe asignarse para obtener o establecer el nombre del sonido. Lectura-escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

Obtiene o establece la duración del efecto de transición de diapositivas en milisegundos. Lectura/escritura int.

--------------------

Corresponde al atributo p14:dur del elemento p:transition en el esquema PresentationML. Si no se establece, la duración se determina automáticamente en función de la propiedad \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) y el tipo de transición.

**Devuelve:**
int
### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Obtiene o establece la duración del efecto de transición de diapositivas en milisegundos. Lectura/escritura int.

--------------------

Corresponde al atributo p14:dur del elemento p:transition en el esquema PresentationML. Si no se establece, la duración se determina automáticamente en función de la propiedad \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) y el tipo de transición.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina si las dos instancias de SlideShowTransition son iguales. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | The SlideShowTransition to compare with the current SlideShowTransition. |

**Devuelve:**
boolean -  **true**  if the specified SlideShowTransition is equal to the current SlideShowTransition; otherwise,  **false** .
### hashCode() {#hashCode--}
```
public int hashCode()
```

Sirve como función hash para un tipo particular, adecuada para su uso en algoritmos de hash y estructuras de datos como una tabla hash.

**Devuelve:**
int - 23454

--------------------

Sobrescrito para que el compilador esté contento. Siempre devuelve una constante porque el objeto es mutable.