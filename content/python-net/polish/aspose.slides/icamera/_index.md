---
title: ICamera class
second_title: Aspose.Slides dla Pythona przez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/icamera/
---
## ICamera klasa

Reprezentuje Camera.

Typ ICamera udostępnia następujące członki:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`camera_type`](/slides/python-net/pl/aspose.slides/icamera/camera_type/) | typ Camera<br/>            Odczyt/zapis [`CameraPresetType`](/slides/python-net/pl/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/pl/aspose.slides/icamera/field_of_view_angle/) | Camera FOV (0-180 deg, pole widzenia)<br/>            Odczyt/zapis **float**. |
| [`zoom`](/slides/python-net/pl/aspose.slides/icamera/zoom/) | Camera zoom (wartość dodatnia w procentach)<br/>            Odczyt/zapis **float**. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/pl/aspose.slides/icamera/set_rotation/#float-float-float) | Obrót jest definiowany przy użyciu szerokości geograficznej<br/>            współrzędna, współrzędna długości geograficznej oraz obrót wokół osi <br/>            jako współrzędne szerokości i długości geograficznej.<br/>            Jeśli którakolwiek wartość współrzędnej jest float.NaN, cały obrót jest niezdefiniowany. |
| [`get_rotation(self)`](/slides/python-net/pl/aspose.slides/icamera/get_rotation/#) | Obrót jest definiowany przy użyciu szerokości geograficznej<br/>            współrzędna, współrzędna długości geograficznej oraz obrót wokół osi <br/>            jako współrzędne szerokości i długości geograficznej.<br/>            pierwszy element w zwracanej tablicy - szerokość, drugi - długość, trzeci - obrót.<br/>            Zwraca None, jeśli nie zdefiniowano obrotu. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)