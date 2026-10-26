---
title: ICamera class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/icamera/
---
## ICamera فئة

يمثل الكاميرا.

يُظهر نوع ICamera الأعضاء التالية:

## الخصائص

| خاصية | الوصف |
| :- | :- |
| [`camera_type`](/slides/python-net/ar/aspose.slides/icamera/camera_type/) | نوع الكاميرا<br/>            قراءة/كتابة [`CameraPresetType`](/slides/python-net/ar/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/ar/aspose.slides/icamera/field_of_view_angle/) | مجال رؤية الكاميرا (0-180 درجة، مجال الرؤية)<br/>            قراءة/كتابة **float**. |
| [`zoom`](/slides/python-net/ar/aspose.slides/icamera/zoom/) | تكبير الكاميرا (قيمة موجبة بالنسبة المئوية)<br/>            قراءة/كتابة **float**. |

## الطرق

| طريقة | الوصف |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/ar/aspose.slides/icamera/set_rotation/#float-float-float) | يُعرّف الدوران باستخدام دائرة عرض<br/>            الإحداثي، وإحداثي خط طول، وثورة حول المحور <br/>            كإحداثيات دائرة العرض وخط الطول.<br/>            إذا كان أي قيمة إحداثية هي float.NaN، يكون جميع الدوران غير معرّف. |
| [`get_rotation(self)`](/slides/python-net/ar/aspose.slides/icamera/get_rotation/#) | يُعرّف الدوران باستخدام دائرة عرض<br/>            الإحداثي، وإحداثي خط طول، وثورة حول المحور <br/>            كإحداثيات دائرة العرض وخط الطول.<br/>            العنصر الأول في مصفوفة الإرجاع - دائرة العرض، الثاني - خط الطول، الثالث - الثورة.<br/>            يرجع None إذا لم يُحدد أي دوران. |

### انظر أيضًا
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)