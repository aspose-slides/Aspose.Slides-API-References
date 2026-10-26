---
title: ICamera class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/icamera/
---
## ICamera clase

Representa Camera.

El tipo ICamera expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`camera_type`](/slides/python-net/es/aspose.slides/icamera/camera_type/) | Tipo de cámara<br/>            Lectura/escritura [`CameraPresetType`](/slides/python-net/es/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/es/aspose.slides/icamera/field_of_view_angle/) | Campo de visión de la cámara (0-180 grados, campo de visión)<br/>            Lectura/escritura **float**. |
| [`zoom`](/slides/python-net/es/aspose.slides/icamera/zoom/) | Zoom de la cámara (valor positivo en porcentaje)<br/>            Lectura/escritura **float**. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/es/aspose.slides/icamera/set_rotation/#float-float-float) | Una rotación se define mediante el uso de una latitud<br/>            coordenada, una longitud coordenada y una revolución alrededor del eje <br/>            como las coordenadas de latitud y longitud.<br/>            Si algún valor de coordenada es float.NaN, toda la rotación es indefinida. |
| [`get_rotation(self)`](/slides/python-net/es/aspose.slides/icamera/get_rotation/#) | Una rotación se define mediante el uso de una latitud<br/>            coordenada, una longitud coordenada y una revolución alrededor del eje <br/>            como las coordenadas de latitud y longitud.<br/>            primer elemento en el array devuelto - latitud, segundo - longitud, tercero - revolución.<br/>            Devuelve None si no hay rotación definida. |

### Véase también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)