---
title: Hyperlink class
second_title: Aspose.Slides para Python vía .NET Referencia de API
description:
type: docs
url: /es/aspose.slides/hyperlink/
---
## Clase Hyperlink

Representa un hipervínculo.

**Herencia:**[`Hyperlink`](/slides/python-net/es/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/es/aspose.slides/pviobject)

El tipo Hyperlink expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/es/aspose.slides/hyperlink/__init__/#str) | Crea una instancia de un hipervínculo. |
| [`__init__(self, slide)`](/slides/python-net/es/aspose.slides/hyperlink/__init__/#islide) | Crea una instancia de un hipervínculo que apunta a una diapositiva específica.<br/>            Nota: el hipervínculo creado debe asignarse a algún objeto de la misma presentación, de lo contrario el enlace se guardará como NoAction. |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/es/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | Crea una instancia de un hipervínculo usando otro hipervínculo como origen, sobrescribiendo propiedades secundarias. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`no_action`](/slides/python-net/es/aspose.slides/hyperlink/no_action/) | Devuelve un hipervínculo especial “no hacer nada”.<br/>            Solo lectura [`Hyperlink`](/slides/python-net/es/aspose.slides/hyperlink). |
| [`media`](/slides/python-net/es/aspose.slides/hyperlink/media/) | Devuelve un hipervínculo especial “reproducir archivo multimedia”. Se utiliza en AudioFrame y VideoFrame.<br/>            Solo lectura [`Hyperlink`](/slides/python-net/es/aspose.slides/hyperlink). |
| [`next_slide`](/slides/python-net/es/aspose.slides/hyperlink/next_slide/) | Devuelve un hipervínculo a la diapositiva siguiente.<br/>            Solo lectura [`Hyperlink`](/slides/python-net/es/aspose.slides/hyperlink). |
| [`previous_slide`](/slides/python-net/es/aspose.slides/hyperlink/previous_slide/) | Devuelve un hipervínculo a la diapositiva anterior.<br/>            Solo lectura [`Hyperlink`](/slides/python-net/es/aspose.slides/hyperlink). |
| [`first_slide`](/slides/python-net/es/aspose.slides/hyperlink/first_slide/) | Devuelve un hipervínculo a la primera diapositiva de la presentación.<br/>            Solo lectura [`Hyperlink`](/slides/python-net/es/aspose.slides/hyperlink). |
| [`last_slide`](/slides/python-net/es/aspose.slides/hyperlink/last_slide/) | Devuelve un hipervínculo a la última diapositiva de la presentación.<br/>            Solo lectura [`Hyperlink`](/slides/python-net/es/aspose.slides/hyperlink). |
| [`last_vieved_slide`](/slides/python-net/es/aspose.slides/hyperlink/last_vieved_slide/) | Devuelve un hipervínculo a la última diapositiva vista.<br/>            Solo lectura [`Hyperlink`](/slides/python-net/es/aspose.slides/hyperlink). |
| [`end_show`](/slides/python-net/es/aspose.slides/hyperlink/end_show/) | Devuelve un hipervínculo que finaliza la presentación.<br/>            Solo lectura [`Hyperlink`](/slides/python-net/es/aspose.slides/hyperlink). |
| [`action_type`](/slides/python-net/es/aspose.slides/hyperlink/action_type/) | Devuelve el tipo de acción del Hyperlink.<br/>            Solo lectura [`HyperlinkActionType`](/slides/python-net/es/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/es/aspose.slides/hyperlink/external_url/) | Especifica la URL externa.<br/>            Solo lectura **str**. |
| [`target_slide`](/slides/python-net/es/aspose.slides/hyperlink/target_slide/) | Si el Hyperlink apunta a una diapositiva específica, devuelve esa diapositiva.<br/>            Solo lectura [`ISlide`](/slides/python-net/es/aspose.slides/islide). |
| [`external_url_original`](/slides/python-net/es/aspose.slides/hyperlink/external_url_original/) | Representa un hipervínculo asignado a esta porción sin considerar el contenido real de la porción.<br/>            <br/>            PowerPoint se comporta de forma específica para los enlaces y su texto correspondiente en una porción. Permite crear texto para el hipervínculo en la forma de una URL válida, distinta de la dirección real del enlace. En este caso, al ver el enlace en la ventana de edición, se modificará para que coincida con la porción de texto. Esta propiedad representa el valor original del hipervínculo. |
| [`target_frame`](/slides/python-net/es/aspose.slides/hyperlink/target_frame/) | Devuelve el marco dentro del conjunto de marcos HTML padre para el objetivo del hipervínculo padre cuando existe.<br/>            Lectura/escritura **str**. |
| [`tooltip`](/slides/python-net/es/aspose.slides/hyperlink/tooltip/) | Devuelve la cadena que puede mostrarse en una interfaz de usuario asociada al hipervínculo padre.<br/>            Lectura/escritura **str**. |
| [`history`](/slides/python-net/es/aspose.slides/hyperlink/history/) | Determina si el objetivo del hipervínculo padre debe añadirse a una lista de hipervínculos vistos cuando se invoca.<br/>            Lectura/escritura **bool**. |
| [`highlight_click`](/slides/python-net/es/aspose.slides/hyperlink/highlight_click/) | Determina si el hipervínculo debe resaltarse al hacer clic.<br/>            Lectura/escritura **bool**. |
| [`stop_sound_on_click`](/slides/python-net/es/aspose.slides/hyperlink/stop_sound_on_click/) | Determina si el sonido debe detenerse al hacer clic en el hipervínculo.<br/>            Lectura/escritura **bool**. |
| [`sound`](/slides/python-net/es/aspose.slides/hyperlink/sound/) | Representa el sonido en reproducción del hipervínculo.<br/>            Lectura/escritura [`IAudio`](/slides/python-net/es/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/es/aspose.slides/hyperlink/color_source/) | Representa la fuente del color del hipervínculo: estilos o formato de la porción.<br/>            Lectura/escritura [`HyperlinkColorSource`](/slides/python-net/es/aspose.slides/hyperlinkcolorsource). |
| [`slide`](/slides/python-net/es/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides/hyperlink/presentation/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/es/aspose.slides/hyperlink/equals/#ihyperlink) | Determina si dos instancias de Hyperlink son iguales. |

### Ver también
* clase [`Hyperlink`](/slides/python-net/es/aspose.slides/hyperlink)
* clase [`PVIObject`](/slides/python-net/es/aspose.slides/pviobject)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)