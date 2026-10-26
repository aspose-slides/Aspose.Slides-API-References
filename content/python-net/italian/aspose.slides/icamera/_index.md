---
title: ICamera class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/icamera/
---
## classe ICamera

Rappresenta Camera.

Il tipo ICamera espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`camera_type`](/slides/python-net/it/aspose.slides/icamera/camera_type/) | Tipo di camera<br/>            Lettura/scrittura [`CameraPresetType`](/slides/python-net/it/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/it/aspose.slides/icamera/field_of_view_angle/) | Campo visivo della camera (0-180 deg, field of View)<br/>            Lettura/scrittura **float**. |
| [`zoom`](/slides/python-net/it/aspose.slides/icamera/zoom/) | Zoom della camera (valore positivo in percentuale)<br/>            Lettura/scrittura **float**. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/it/aspose.slides/icamera/set_rotation/#float-float-float) | Una rotazione è definita mediante l'uso di una coordinata di latitudine<br/>            , una coordinata di longitudine e una rivoluzione attorno all'asse <br/>            come le coordinate di latitudine e longitudine.<br/>            Se qualche valore della coordinata è float.NaN, tutta la rotazione è indefinita. |
| [`get_rotation(self)`](/slides/python-net/it/aspose.slides/icamera/get_rotation/#) | Una rotazione è definita mediante l'uso di una coordinata di latitudine<br/>            , una coordinata di longitudine e una rivoluzione attorno all'asse <br/>            come le coordinate di latitudine e longitudine.<br/>            primo elemento nell'array restituito - latitudine, secondo - longitudine, terzo - rivoluzione.<br/>            Restituisce None se nessuna rotazione è definita. |

### Vedi anche
* module [`aspose.slides`](/slides/python-net/it/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)