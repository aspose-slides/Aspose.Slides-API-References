---
title: ICameraEffectiveData class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/icameraeffectivedata/
---
## ICameraEffectiveData classe

Oggetto immutabile che contiene le proprietà effettive della fotocamera.

Il tipo ICameraEffectiveData espone i seguenti membri:

## Properties

| Proprietà | Descrizione |
| :- | :- |
| [`camera_type`](/slides/python-net/it/aspose.slides/icameraeffectivedata/camera_type/) | Tipo di fotocamera.<br/>            Solo lettura [`CameraPresetType`](/slides/python-net/it/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/it/aspose.slides/icameraeffectivedata/field_of_view_angle/) | Campo visivo della fotocamera (0-180°, campo di visualizzazione).<br/>            Solo lettura **float**. |
| [`zoom`](/slides/python-net/it/aspose.slides/icameraeffectivedata/zoom/) | Zoom della fotocamera (valore positivo in percentuale).<br/>            Solo lettura **float**. |

## Methods

| Metodo | Descrizione |
| :- | :- |
| [`get_rotation(self)`](/slides/python-net/it/aspose.slides/icameraeffectivedata/get_rotation/#) | Una rotazione è definita tramite l'uso di una coordinata di latitudine<br/>            una coordinata di longitudine e una rivoluzione attorno all'asse <br/>            come le coordinate di latitudine e longitudine.<br/>            primo elemento nell'array restituito - latitudine, secondo - longitudine, terzo - rivoluzione.<br/>            Restituisce None se non è definita alcuna rotazione. |

### Osservazioni

Questa interfaccia è usata come parte di [`IThreeDFormatEffectiveData`](/slides/python-net/it/aspose.slides/ithreedformateffectivedata).

### Vedi anche
* classe [`IThreeDFormatEffectiveData`](/slides/python-net/it/aspose.slides/ithreedformateffectivedata)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)