---
title: ICamera class
second_title: Aspose.Slides para Python via .NET – Referência de API
description: 
type: docs
url: /pt/aspose.slides/icamera/
---
## ICamera classe

Representa Câmera.

The ICamera type exposes the following members:

## Propriedades

| Property | Description |
| :- | :- |
| [`camera_type`](/slides/python-net/pt/aspose.slides/icamera/camera_type/) | Tipo da câmera<br/>            Read/write [`CameraPresetType`](/slides/python-net/pt/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/pt/aspose.slides/icamera/field_of_view_angle/) | FOV da câmera (0-180 deg, campo de visão)<br/>            Read/write **float**. |
| [`zoom`](/slides/python-net/pt/aspose.slides/icamera/zoom/) | Zoom da câmera (valor positivo em porcentagem)<br/>            Read/write **float**. |

## Métodos

| Method | Description |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/pt/aspose.slides/icamera/set_rotation/#float-float-float) | Uma rotação é definida pelo uso de uma latitude<br/>            coordenada, uma coordenada de longitude e uma revolução ao redor do eixo <br/>            como as coordenadas de latitude e longitude.<br/>            Se algum valor da coordenada for float.NaN, toda a rotação é indefinida. |
| [`get_rotation(self)`](/slides/python-net/pt/aspose.slides/icamera/get_rotation/#) | Uma rotação é definida pelo uso de uma latitude<br/>            coordenada, uma coordenada de longitude e uma revolução ao redor do eixo <br/>            como as coordenadas de latitude e longitude.<br/>            primeiro elemento na matriz retornada - latitude, segundo - longitude, terceiro - revolução.<br/>            Retorna None se nenhuma rotação for definida. |


### Ver também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)