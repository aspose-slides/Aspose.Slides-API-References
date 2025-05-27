---
title: Cámara
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa Cámara.
type: docs
weight: 1010
url: /es/aspose.slides/camera/
---

## Clase Cámara

Representa Cámara.

```csharp
public sealed class Camera : PVIObject, ICamera
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPresentationComponent. Solo lectura [`IPresentationComponent`](../ipresentationcomponent). |
| [CameraType](../../aspose.slides/camera/cameratype) { get; set; } | Tipo de cámara. Lectura/escritura [`CameraPresetType`](../camerapresettype). |
| [FieldOfViewAngle](../../aspose.slides/camera/fieldofviewangle) { get; set; } | FOV de la cámara (0-180 grados, campo de visión). Lectura/escritura Single. |
| [Zoom](../../aspose.slides/camera/zoom) { get; set; } | Zoom de la cámara (valor positivo en porcentaje). Lectura/escritura Single. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara con el objeto especificado. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Devuelve el código hash. |
| [GetRotation](../../aspose.slides/camera/getrotation)() | Una rotación se define a través del uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como las coordenadas de latitud y longitud. primer elemento en el array de retorno - latitud, segundo - longitud, tercero - revolución. Devuelve nulo si no se define ninguna rotación. |
| [SetRotation](../../aspose.slides/camera/setrotation)(float, float, float) | Una rotación se define a través del uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como las coordenadas de latitud y longitud. Si algún valor de coordenada es float.NaN, toda la rotación está indefinida. |

### Véase También

* clase [PVIObject](../pviobject)
* interfaz [ICamera](../icamera)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->