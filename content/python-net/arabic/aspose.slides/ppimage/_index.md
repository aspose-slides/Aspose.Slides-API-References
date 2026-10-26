---
title: PPImage class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/ppimage/
---
## PPImage فئة

يمثل صورةً في عرض تقديمي.

يعرض نوع PPImage الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`binary_data`](/slides/python-net/ar/aspose.slides/ppimage/binary_data/) | يُرجع نسخة من بيانات الصورة.<br/>            للقراءة فقط **int**[]. |
| [`image`](/slides/python-net/ar/aspose.slides/ppimage/image/) | يُرجع نسخة من الصورة.<br/>            للقراءة فقط [`IImage`](/slides/python-net/ar/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/ar/aspose.slides/ppimage/svg_image/) | يُرجع أو يضبط كائن ISvgImage [`ISvgImage`](/slides/python-net/ar/aspose.slides/isvgimage) |
| [`content_type`](/slides/python-net/ar/aspose.slides/ppimage/content_type/) | يُرجع نوع MIME للصورة، مُشفَّر في [`PPImage.binary_data`](/slides/python-net/ar/aspose.slides/ppimage/binary_data).<br/>            للقراءة فقط **str**. |
| [`width`](/slides/python-net/ar/aspose.slides/ppimage/width/) | يُرجع عرض الصورة.<br/>            للقراءة فقط **int**. |
| [`height`](/slides/python-net/ar/aspose.slides/ppimage/height/) | يُرجع ارتفاع الصورة.<br/>            للقراءة فقط **int**. |
| [`x`](/slides/python-net/ar/aspose.slides/ppimage/x/) | يُرجع إزاحة X للصورة.<br/>            للقراءة فقط **int**. |
| [`y`](/slides/python-net/ar/aspose.slides/ppimage/y/) | يُرجع إزاحة Y للصورة.<br/>            للقراءة فقط **int**. |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/ar/aspose.slides/ppimage/replace_image/#bytes) | يستبدل بيانات الصورة.<br/>            بيانات الصورة الجديدة. عندما يكون معامل newImageData هو None. |
| [`replace_image(self, new_image)`](/slides/python-net/ar/aspose.slides/ppimage/replace_image/#iimage) | يستبدل بيانات الصورة. ملاحظة: عندما تكون Image ملف ميتافايل - سيتم تحويلها إلى نقطية. استخدم ReplaceImage(byte[]) بدلاً من ذلك<br/>            الصورة الجديدة. عندما يكون معامل newImage هو None. |
| [`replace_image(self, new_image)`](/slides/python-net/ar/aspose.slides/ppimage/replace_image/#ippimage) | يستبدل بيانات الصورة.<br/>            IPPImage الجديد. عندما يكون معامل newImage هو None. |

### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)