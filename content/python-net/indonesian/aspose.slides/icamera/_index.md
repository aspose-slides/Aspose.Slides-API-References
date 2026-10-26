---
title: ICamera class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/icamera/
---
## ICamera kelas

Mewakili Kamera.

Tipe ICamera mengekspos anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`camera_type`](/slides/python-net/id/aspose.slides/icamera/camera_type/) | Tipe Kamera<br/>            Baca/tulis [`CameraPresetType`](/slides/python-net/id/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/id/aspose.slides/icamera/field_of_view_angle/) | FOV Kamera (0-180 derajat, bidang pandang)<br/>            Baca/tulis **float**. |
| [`zoom`](/slides/python-net/id/aspose.slides/icamera/zoom/) | Zoom Kamera (nilai positif dalam persentase)<br/>            Baca/tulis **float**. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/id/aspose.slides/icamera/set_rotation/#float-float-float) | Rotasi didefinisikan melalui penggunaan lintang<br/>            koordinat, koordinat bujur, dan revolusi sekitar sumbu <br/>            sebagai koordinat lintang dan bujur.<br/>            Jika nilai koordinat mana pun adalah float.NaN, semua rotasi tidak terdefinisi. |
| [`get_rotation(self)`](/slides/python-net/id/aspose.slides/icamera/get_rotation/#) | Rotasi didefinisikan melalui penggunaan lintang<br/>            koordinat, koordinat bujur, dan revolusi sekitar sumbu <br/>            sebagai koordinat lintang dan bujur.<br/>            elemen pertama dalam array hasil - lintang, kedua - bujur, ketiga - revolusi.<br/>            Mengembalikan None jika tidak ada rotasi yang didefinisikan. |


### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)