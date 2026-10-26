---
title: ICamera class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/icamera/
---
## ICamera sınıfı

Kamerayı temsil eder.

ICamera türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`camera_type`](/slides/python-net/tr/aspose.slides/icamera/camera_type/) | Kamera tipi<br/>            Okuma/yazma [`CameraPresetType`](/slides/python-net/tr/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/tr/aspose.slides/icamera/field_of_view_angle/) | Kamera FOV (0-180 derece, görüş alanı)<br/>            Okuma/yazma **float**. |
| [`zoom`](/slides/python-net/tr/aspose.slides/icamera/zoom/) | Kamera yakınlaştırması (yüzdelik pozitif değer)<br/>            Okuma/yazma **float**. |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/tr/aspose.slides/icamera/set_rotation/#float-float-float) | Dönüş, enlem<br/>            koordinatı, boylam koordinatı ve eksen etrafında bir devrim<br/>            olarak enlem ve boylam koordinatları kullanılarak tanımlanır.<br/>            Eğer herhangi bir koordinat değeri float.NaN ise, tüm dönüş tanımsızdır. |
| [`get_rotation(self)`](/slides/python-net/tr/aspose.slides/icamera/get_rotation/#) | Dönüş, enlem<br/>            koordinatı, boylam koordinatı ve eksen etrafında bir devrim<br/>            olarak enlem ve boylam koordinatları kullanılarak tanımlanır.<br/>            dönüşüm dizisindeki ilk eleman - enlem, ikinci - boylam, üçüncü - devrim.<br/>            Tanımlı dönüş yoksa None döndürür. |

### Diğer Bağlantılar
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)