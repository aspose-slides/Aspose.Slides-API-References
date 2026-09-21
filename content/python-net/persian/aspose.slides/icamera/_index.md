---
title: ICamera class
second_title: Aspose.Slides برای پایتون از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/icamera/
---
## ICamera کلاس

دوربین را نمایانگر است.

نوع ICamera اعضای زیر را در دسترس می‌گذارد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`camera_type`](/slides/python-net/fa/aspose.slides/icamera/camera_type/) | Camera type<br/>            خواندنی/نوشتنی [`CameraPresetType`](/slides/python-net/fa/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/fa/aspose.slides/icamera/field_of_view_angle/) | Camera FOV (0-180 deg, field of View)<br/>            خواندنی/نوشتنی **float**. |
| [`zoom`](/slides/python-net/fa/aspose.slides/icamera/zoom/) | Camera zoom (positive value in percentage)<br/>            خواندنی/نوشتنی **float**. |

## متدها

| متد | توضیح |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/fa/aspose.slides/icamera/set_rotation/#float-float-float) | A rotation is defined through the use of a latitude<br/>            coordinate, a longitude coordinate, and a revolution about the axis <br/>            as the latitude and longitude coordinates.<br/>            اگر هر یک از مقادیر مختصات برابر float.NaN باشد، تمام چرخش تعریف‌نشده است. |
| [`get_rotation(self)`](/slides/python-net/fa/aspose.slides/icamera/get_rotation/#) | A rotation is defined through the use of a latitude<br/>            coordinate, a longitude coordinate, and a revolution about the axis <br/>            as the latitude and longitude coordinates.<br/>            اولین عنصر در آرایهٔ بازگشتی - عرض جغرافیایی، دومین - طول جغرافیایی، سومین - دور.<br/>            اگر چرخشی تعریف نشده باشد، None برگردانده می‌شود. |

### موارد مرتبط
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)