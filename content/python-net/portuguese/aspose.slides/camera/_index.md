---
title: Camera class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/camera/
---
## Camera classe

Representa Camera.

**Inheritance:**[`Camera`](/slides/python-net/pt/aspose.slides/camera) → [`PVIObject`](/slides/python-net/pt/aspose.slides/pviobject)

O tipo Camera expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`camera_type`](/slides/python-net/pt/aspose.slides/camera/camera_type/) | Tipo de Camera.<br/>            Leitura/gravação [`CameraPresetType`](/slides/python-net/pt/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/pt/aspose.slides/camera/field_of_view_angle/) | Camera FOV (0-180 deg, campo de Visão).<br/>            Leitura/gravação **float**. |
| [`zoom`](/slides/python-net/pt/aspose.slides/camera/zoom/) | Zoom da Camera (valor positivo em porcentagem).<br/>            Leitura/gravação **float**. |
| [`slide`](/slides/python-net/pt/aspose.slides/camera/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides/camera/presentation/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/pt/aspose.slides/camera/set_rotation/#float-float-float) | Uma rotação é definida através do uso de uma latitude<br/>            coordenada, uma coordenada de longitude e uma revolução em torno do eixo <br/>            como as coordenadas de latitude e longitude.<br/>            Se algum valor da coordenada for float.NaN, toda a rotação é indefinida. |
| [`get_rotation(self)`](/slides/python-net/pt/aspose.slides/camera/get_rotation/#) | Uma rotação é definida através do uso de uma latitude<br/>            coordenada, uma coordenada de longitude e uma revolução em torno do eixo <br/>            como as coordenadas de latitude e longitude.<br/>            primeiro elemento no array de retorno - latitude, segundo - longitude, terceiro - revolução.<br/>            Retorna None se nenhuma rotação estiver definida. |


### Ver também
* classe [`Camera`](/slides/python-net/pt/aspose.slides/camera)
* classe [`PVIObject`](/slides/python-net/pt/aspose.slides/pviobject)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)