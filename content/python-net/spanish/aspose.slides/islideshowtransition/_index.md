---
title: ISlideShowTransition class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/islideshowtransition/
---
## ISlideShowTransition clase

Representa la transición de la presentación de diapositivas.

El tipo ISlideShowTransition expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`sound`](/slides/python-net/es/aspose.slides/islideshowtransition/sound/) | Devuelve o establece los datos de audio incrustados.<br/>            Lectura-escritura [`IAudio`](/slides/python-net/es/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/es/aspose.slides/islideshowtransition/sound_mode/) | Establece o devuelve el modo de sonido para la transición de diapositiva.<br/>            Lectura-escritura [`TransitionSoundMode`](/slides/python-net/es/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/es/aspose.slides/islideshowtransition/sound_loop/) | Este atributo especifica si el sonido se reproducirá en bucle hasta que se produzca el siguiente evento de sonido en<br/>            la presentación.<br/>            Lectura-escritura **bool**. |
| [`advance_on_click`](/slides/python-net/es/aspose.slides/islideshowtransition/advance_on_click/) | Especifica si un clic del ratón avanzará la diapositiva o no. Si este atributo no está<br/>            especificado, se asume un valor verdadero.<br/>            Lectura-escritura **bool**. |
| [`advance_after`](/slides/python-net/es/aspose.slides/islideshowtransition/advance_after/) | Este atributo especifica si la presentación avanzará a la siguiente diapositiva después de cierto tiempo.<br/>            Lectura/escritura **bool**. |
| [`advance_after_time`](/slides/python-net/es/aspose.slides/islideshowtransition/advance_after_time/) | Especifica el tiempo, en milisegundos, después del cual debe iniciar la transición. Esta configuración<br/>            puede usarse junto con el atributo advClick. Si este atributo no está especificado<br/>            se asume que no habrá avance automático.<br/>            Lectura-escritura **int**. |
| [`speed`](/slides/python-net/es/aspose.slides/islideshowtransition/speed/) | Especifica la velocidad de transición que se debe usar al pasar de la diapositiva actual<br/>            a la siguiente.<br/>            Lectura-escritura [`TransitionSpeed`](/slides/python-net/es/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/es/aspose.slides/islideshowtransition/value/) | Valor de la transición de la presentación.<br/>            Solo lectura [`ITransitionValueBase`](/slides/python-net/es/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/es/aspose.slides/islideshowtransition/type/) | Tipo de transición.<br/>            Lectura-escritura [`TransitionType`](/slides/python-net/es/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/es/aspose.slides/islideshowtransition/sound_is_built_in/) | Especifica si este sonido es o no un sonido incorporado. Si este atributo está establecido en verdadero, entonces<br/>            la aplicación generadora se avisa para comprobar el atributo name especificado para este sonido<br/>            en su lista de sonidos incorporados y puede entonces mostrar un nombre personalizado o una interfaz según sea necesario.<br/>            Lectura-escritura **bool**. |
| [`sound_name`](/slides/python-net/es/aspose.slides/islideshowtransition/sound_name/) | Especifica un nombre legible por humanos para el sonido de la transición. La propiedad [`ISlideShowTransition.sound`](/slides/python-net/es/aspose.slides/islideshowtransition/sound) debe asignarse para obtener o establecer el nombre del sonido.<br/>            Lectura-escritura **str**. |
| [`duration`](/slides/python-net/es/aspose.slides/islideshowtransition/duration/) | Obtiene o establece la duración del efecto de transición de diapositiva en milisegundos.<br/>            Lectura/escritura **int**. |


### Véase también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)