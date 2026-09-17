---
title: SlideShowTransition class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition clase

Representa la transición de la presentación.

El tipo SlideShowTransition expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`sound`](/slides/python-net/es/aspose.slides.slideshow/slideshowtransition/sound/) | Devuelve o establece los datos de audio incrustados.<br/>            Lectura/escritura [`IAudio`](/slides/python-net/es/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/es/aspose.slides.slideshow/slideshowtransition/sound_mode/) | Establece o devuelve el modo de sonido para la transición de diapositiva.<br/>            Lectura/escritura [`TransitionSoundMode`](/slides/python-net/es/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/es/aspose.slides.slideshow/slideshowtransition/sound_loop/) | Este atributo especifica si el sonido se repetirá hasta que ocurra el próximo evento de sonido en<br/>            la presentación.<br/>            Lectura/escritura **bool**. |
| [`advance_on_click`](/slides/python-net/es/aspose.slides.slideshow/slideshowtransition/advance_on_click/) | Especifica si un clic del ratón avanzará la diapositiva o no. Si este atributo no<br/>            se especifica, se asume un valor verdadero.<br/>            Lectura/escritura **bool**. |
| [`advance_after`](/slides/python-net/es/aspose.slides.slideshow/slideshowtransition/advance_after/) | Este atributo especifica si la presentación avanzará a la siguiente diapositiva después de un tiempo determinado.<br/>            Lectura/escritura **bool**. |
| [`advance_after_time`](/slides/python-net/es/aspose.slides.slideshow/slideshowtransition/advance_after_time/) | Especifica el tiempo, en milisegundos, después del cual debe iniciarse la transición. Esta configuración<br/>            puede usarse junto con el atributo advClick. Si este atributo no se especifica<br/>            se asume que no habrá avance automático.<br/>            Lectura/escritura **int**. |
| [`speed`](/slides/python-net/es/aspose.slides.slideshow/slideshowtransition/speed/) | Especifica la velocidad de transición que se utilizará al pasar de la diapositiva actual<br/>            a la siguiente.<br/>            Lectura/escritura [`TransitionSpeed`](/slides/python-net/es/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/es/aspose.slides.slideshow/slideshowtransition/value/) | Valor de la transición de la presentación.<br/>            Solo lectura [`ITransitionValueBase`](/slides/python-net/es/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/es/aspose.slides.slideshow/slideshowtransition/type/) | Tipo de transición.<br/>            Lectura/escritura [`TransitionType`](/slides/python-net/es/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/es/aspose.slides.slideshow/slideshowtransition/sound_is_built_in/) | Especifica si este sonido es un sonido incorporado o no. Si este atributo se establece en verdadero, la aplicación generadora será notificada para comprobar el atributo name especificado para este sonido<br/>            en su lista de sonidos incorporados y podrá mostrar un nombre personalizado o una interfaz según sea necesario.<br/>            Lectura/escritura **bool**. |
| [`sound_name`](/slides/python-net/es/aspose.slides.slideshow/slideshowtransition/sound_name/) | Especifica un nombre legible por humanos para el sonido de la transición. La propiedad [`SlideShowTransition.sound`](/slides/python-net/es/aspose.slides.slideshow/slideshowtransition/sound) debe asignarse para obtener o establecer el nombre del sonido.<br/>            Lectura/escritura **str**. |
| [`duration`](/slides/python-net/es/aspose.slides.slideshow/slideshowtransition/duration/) | Obtiene o establece la duración del efecto de transición de diapositiva en milisegundos.<br/>            Lectura/escritura **int**. |


### Ver también
* módulo [`aspose.slides.slideshow`](/slides/python-net/es/aspose.slides.slideshow)
* biblioteca [`Aspose.Slides`](/slides/python-net)