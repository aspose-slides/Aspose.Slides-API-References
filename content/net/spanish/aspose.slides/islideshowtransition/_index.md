---
title: ISlideShowTransition
second_title: Referencia API de Aspose.Slides para .NET
description: Representa la transición de la presentación de diapositivas.
type: docs
weight: 6860
url: /es/aspose.slides/islideshowtransition/
---

## Interfaz ISlideShowTransition

Representa la transición de la presentación de diapositivas.

```csharp
public interface ISlideShowTransition
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AdvanceAfter](../../aspose.slides/islideshowtransition/advanceafter) { get; set; } | Este atributo especifica si la presentación de diapositivas se moverá a la siguiente diapositiva después de un cierto tiempo. Booleano de lectura/escritura. |
| [AdvanceAfterTime](../../aspose.slides/islideshowtransition/advanceaftertime) { get; set; } | Especifica el tiempo, en milisegundos, después del cual debe comenzar la transición. Esta configuración puede usarse junto con el atributo advClick. Si este atributo no se especifica, se asume que no ocurrirá un avance automático. UInt32 de lectura/escritura. |
| [AdvanceOnClick](../../aspose.slides/islideshowtransition/advanceonclick) { get; set; } | Especifica si un clic del mouse avanzará la diapositiva o no. Si este atributo no se especifica, se asume un valor de verdadero. Booleano de lectura/escritura. |
| [Sound](../../aspose.slides/islideshowtransition/sound) { get; set; } | Devuelve o establece los datos de audio incrustados. Lectura/escritura [`IAudio`](../iaudio). |
| [SoundIsBuiltIn](../../aspose.slides/islideshowtransition/soundisbuiltin) { get; set; } | Especifica si este sonido es un sonido integrado o no. Si este atributo se establece en verdadero, la aplicación generadora se alerta para verificar el atributo de nombre especificado para este sonido en su lista de sonidos integrados y luego puede mostrar un nombre o interfaz de usuario personalizada según sea necesario. Booleano de lectura/escritura. |
| [SoundLoop](../../aspose.slides/islideshowtransition/soundloop) { get; set; } | Este atributo especifica si el sonido se repetirá hasta que ocurra el siguiente evento de sonido en la presentación de diapositivas. Booleano de lectura/escritura. |
| [SoundMode](../../aspose.slides/islideshowtransition/soundmode) { get; set; } | Establece o devuelve el modo de sonido para la transición de diapositivas. Lectura/escritura [`TransitionSoundMode`](../../aspose.slides.slideshow/transitionsoundmode). |
| [SoundName](../../aspose.slides/islideshowtransition/soundname) { get; set; } | Especifica un nombre legible para humanos para el sonido de la transición. La propiedad [`Sound`](./sound) debe ser asignada para obtener o establecer el nombre del sonido. String de lectura/escritura. |
| [Speed](../../aspose.slides/islideshowtransition/speed) { get; set; } | Especifica la velocidad de transición que se utilizará al cambiar de la diapositiva actual a la siguiente. Lectura/escritura [`TransitionSpeed`](../../aspose.slides.slideshow/transitionspeed). |
| [Type](../../aspose.slides/islideshowtransition/type) { get; set; } | Tipo de transición. Lectura/escritura [`TransitionType`](../../aspose.slides.slideshow/transitiontype). |
| [Value](../../aspose.slides/islideshowtransition/value) { get; } | Valor de la transición de la presentación de diapositivas. Solo de lectura [`ITransitionValueBase`](../../aspose.slides.slideshow/itransitionvaluebase). |

### Vea También

* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->