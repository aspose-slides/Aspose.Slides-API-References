---
title: Camera class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/camera/
---
## Clase Camera

Representa Camera.

**Herencia:**[`Camera`](/slides/python-net/es/aspose.slides/camera) → [`PVIObject`](/slides/python-net/es/aspose.slides/pviobject)

El tipo Camera expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`camera_type`](/slides/python-net/es/aspose.slides/camera/camera_type/) | Tipo de Camera.<br/>            Lectura/escritura [`CameraPresetType`](/slides/python-net/es/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/es/aspose.slides/camera/field_of_view_angle/) | Camera FOV (0-180 deg, campo de visión).<br/>            Lectura/escritura **float**. |
| [`zoom`](/slides/python-net/es/aspose.slides/camera/zoom/) | Zoom de la Camera (valor positivo en porcentaje).<br/>            Lectura/escritura **float**. |
| [`slide`](/slides/python-net/es/aspose.slides/camera/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides/camera/presentation/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/es/aspose.slides/camera/set_rotation/#float-float-float) | Una rotación se define mediante el uso de una latitud<br/>            coordenada, una coordenada de longitud y una revolución alrededor del eje <br/>            como las coordenadas de latitud y longitud.<br/>            Si algún valor de coordenada es float.NaN, toda la rotación es indefinida. |
| [`get_rotation(self)`](/slides/python-net/es/aspose.slides/camera/get_rotation/#) | Una rotación se define mediante el uso de una latitud<br/>            coordenada, una coordenada de longitud y una revolución alrededor del eje <br/>            como las coordenadas de latitud y longitud.<br/>            primer elemento en el arreglo de retorno - latitud, segundo - longitud, tercero - revolución.<br/>            Devuelve None si no se define ninguna rotación. |

### Ver también
* clase [`Camera`](/slides/python-net/es/aspose.slides/camera)
* clase [`PVIObject`](/slides/python-net/es/aspose.slides/pviobject)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)