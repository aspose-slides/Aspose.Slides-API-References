---
title: ICamera class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/icamera/
---
## ICamera Klasse

Stellt die Kamera dar.

Der ICamera-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`camera_type`](/slides/python-net/de/aspose.slides/icamera/camera_type/) | Kameratyp<br/>            Lesen/Schreiben [`CameraPresetType`](/slides/python-net/de/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/de/aspose.slides/icamera/field_of_view_angle/) | Kamera-FOV (0-180 Grad, Sichtfeld)<br/>            Lesen/Schreiben **float**. |
| [`zoom`](/slides/python-net/de/aspose.slides/icamera/zoom/) | Kamera-Zoom (positiver Wert in Prozent)<br/>            Lesen/Schreiben **float**. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/de/aspose.slides/icamera/set_rotation/#float-float-float) | Eine Rotation wird definiert durch die Verwendung einer Breitengrad<br/>            Koordinate, einer Längengrad Koordinate und einer Drehung um die Achse <br/>            gemäß den Breitengrad- und Längengrad Koordinaten.<br/>            Wenn irgendein Koordinatenwert float.NaN ist, ist die gesamte Rotation undefiniert. |
| [`get_rotation(self)`](/slides/python-net/de/aspose.slides/icamera/get_rotation/#) | Eine Rotation wird definiert durch die Verwendung einer Breitengrad<br/>            Koordinate, einer Längengrad Koordinate und einer Drehung um die Achse <br/>            gemäß den Breitengrad- und Längengrad Koordinaten.<br/>            erstes Element im Rückgabe-Array – Breitengrad, zweites – Längengrad, drittes – Drehung.<br/>            Gibt None zurück, wenn keine Rotation definiert ist. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)