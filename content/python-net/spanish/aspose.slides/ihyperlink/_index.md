---
title: IHyperlink class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/ihyperlink/
---
## IHyperlink clase

Representa un hipervínculo.

El tipo IHyperlink expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`action_type`](/slides/python-net/es/aspose.slides/ihyperlink/action_type/) | Devuelve el tipo de acción de HyperLinkEx.<br/>            Solo lectura [`HyperlinkActionType`](/slides/python-net/es/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/es/aspose.slides/ihyperlink/external_url/) | Especifica la URL externa<br/>            Si esta propiedad no es None, entonces la propiedad TargetSlide será None.<br/>            Solo lectura **str**. |
| [`external_url_original`](/slides/python-net/es/aspose.slides/ihyperlink/external_url_original/) | Representa un hipervínculo que se establece para esta porción sin tener en cuenta el contenido real de la porción.<br/>            <br/>            PowerPoint se comporta de manera específica con los enlaces y su texto correspondiente en una porción. Permite crear texto para el hipervínculo en<br/>            forma de una URL válida, diferente de la dirección real del enlace. En este caso, cuando ves el enlace en la ventana de edición, será<br/>            cambiado para coincidir con la porción de texto. Esta propiedad representa el valor original del hipervínculo. |
| [`target_slide`](/slides/python-net/es/aspose.slides/ihyperlink/target_slide/) | Si HyperlinkEx apunta a una diapositiva específica, devuelve esa diapositiva.<br/>            Si la propiedad no es None, entonces la propiedad ExternalUrl será None.<br/>            Solo lectura [`ISlide`](/slides/python-net/es/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/es/aspose.slides/ihyperlink/target_frame/) | Devuelve el marco dentro del conjunto de marcos HTML padre para el objetivo<br/>            del hipervínculo padre cuando exista.<br/>            Lectura/escritura **str**. |
| [`tooltip`](/slides/python-net/es/aspose.slides/ihyperlink/tooltip/) | Devuelve la cadena que puede mostrarse en una interfaz de usuario<br/>            asociada con el hipervínculo padre.<br/>            Lectura/escritura **str**. |
| [`history`](/slides/python-net/es/aspose.slides/ihyperlink/history/) | Determina si el objetivo del hipervínculo padre debe ser añadido<br/>            a una lista de hipervínculos vistos cuando se invoca.<br/>            Lectura/escritura **bool**. |
| [`highlight_click`](/slides/python-net/es/aspose.slides/ihyperlink/highlight_click/) | Determina si el hipervínculo debe resaltarse al hacer clic.<br/>            Lectura/escritura **bool**. |
| [`stop_sound_on_click`](/slides/python-net/es/aspose.slides/ihyperlink/stop_sound_on_click/) | Determina si el sonido debe detenerse al hacer clic en el hipervínculo.<br/>            Lectura/escritura **bool**. |
| [`sound`](/slides/python-net/es/aspose.slides/ihyperlink/sound/) | Representa el sonido en reproducción del hipervínculo.<br/>            Lectura/escritura [`IAudio`](/slides/python-net/es/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/es/aspose.slides/ihyperlink/color_source/) | Representa la fuente del color del hipervínculo - ya sea estilos o formato de la porción.<br/>            Lectura/escritura [`HyperlinkColorSource`](/slides/python-net/es/aspose.slides/hyperlinkcolorsource). |

## Métodos

| Método | Descripción |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/es/aspose.slides/ihyperlink/equals/#ihyperlink) | Determina si las dos instancias de Hyperlink son iguales. |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)