---
title: ICamera
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa la cámara.
type: docs
weight: 5210
url: /es/aspose.slides/icamera/
---

## Interfaz ICamera

Representa la cámara.

```csharp
public interface ICamera
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CameraType](../../aspose.slides/icamera/cameratype) { get; set; } | Tipo de cámara Lectura/escritura [`CameraPresetType`](../camerapresettype). |
| [FieldOfViewAngle](../../aspose.slides/icamera/fieldofviewangle) { get; set; } | Campo de visión de la cámara (0-180 grados, campo de visión) Lectura/escritura Single. |
| [Zoom](../../aspose.slides/icamera/zoom) { get; set; } | Zoom de la cámara (valor positivo en porcentaje) Lectura/escritura Single. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetRotation](../../aspose.slides/icamera/getrotation)() | Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como las coordenadas de latitud y longitud. Primer elemento en el array de retorno - latitud, segundo - longitud, tercero - revolución. Devuelve null si no se define ninguna rotación. |
| [SetRotation](../../aspose.slides/icamera/setrotation)(float, float, float) | Una rotación se define mediante el uso de una coordenada de latitud, una coordenada de longitud y una revolución alrededor del eje como las coordenadas de latitud y longitud. Si alguno de los valores de las coordenadas es float.NaN, toda la rotación está indefinida. |

### Véase también

* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->