---
title: IBulletFormat class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/ibulletformat/
---
## IBulletFormat الفئة

يمثل خصائص تنسيق رصاص الفقرة.

يعرض نوع IBulletFormat الأعضاء التالية:

## الخصائص

| خاصية | الوصف |
| :- | :- |
| [`type`](/slides/python-net/ar/aspose.slides/ibulletformat/type/) | إرجاع أو تعيين نوع الرصاصة لفقرة دون وراثة.<br/>            قراءة/كتابة [`BulletType`](/slides/python-net/ar/aspose.slides/bullettype). |
| [`char`](/slides/python-net/ar/aspose.slides/ibulletformat/char/) | إرجاع أو تعيين حرف الرصاصة لفقرة دون وراثة.<br/>            قراءة/كتابة **System.Char**. |
| [`font`](/slides/python-net/ar/aspose.slides/ibulletformat/font/) | إرجاع أو تعيين خط الرصاصة لفقرة دون وراثة.<br/>            قراءة/كتابة [`IFontData`](/slides/python-net/ar/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/ar/aspose.slides/ibulletformat/height/) | إرجاع أو تعيين ارتفاع الرصاصة لفقرة دون وراثة.<br/>            القيمة float.NaN تحدد أن الرصاصة ترث الارتفاع من الجزء الأول في الفقرة.<br/>            قراءة/كتابة **float**. |
| [`color`](/slides/python-net/ar/aspose.slides/ibulletformat/color/) | إرجاع تنسيق اللون لرصاصة فقرة دون وراثة.<br/>            قراءة فقط [`IColorFormat`](/slides/python-net/ar/aspose.slides/icolorformat). |
| [`picture`](/slides/python-net/ar/aspose.slides/ibulletformat/picture/) | إرجاع الصورة المستخدمة كرصاصة في فقرة دون وراثة.<br/>            قراءة فقط [`ISlidesPicture`](/slides/python-net/ar/aspose.slides/islidespicture). |
| [`numbered_bullet_start_with`](/slides/python-net/ar/aspose.slides/ibulletformat/numbered_bullet_start_with/) | إرجاع أو تعيين الرقم الأول الذي يُستخدم لمجموعة من الرصاصات المرقَّمة دون وراثة.<br/>            قراءة/كتابة **int**. |
| [`numbered_bullet_style`](/slides/python-net/ar/aspose.slides/ibulletformat/numbered_bullet_style/) | إرجاع أو تعيين نمط الرصاصة المرقَّمة دون وراثة.<br/>            قراءة/كتابة [`IBulletFormat.numbered_bullet_style`](/slides/python-net/ar/aspose.slides/ibulletformat/numbered_bullet_style). |
| [`is_bullet_hard_color`](/slides/python-net/ar/aspose.slides/ibulletformat/is_bullet_hard_color/) | يحدد ما إذا كانت الرصاصة لها لون خاص أم أنها ترثه من الجزء الأول في الفقرة.<br/>            **NullableBool.True** إذا كانت الرصاصة لها لون خاص و **NullableBool.False** إذا كانت الرصاصة<br/>            ترث اللون من الجزء الأول في الفقرة.<br/>            قراءة/كتابة [`NullableBool`](/slides/python-net/ar/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/ar/aspose.slides/ibulletformat/is_bullet_hard_font/) | يحدد ما إذا كانت الرصاصة لها خط خاص أم أنها ترثه من الجزء الأول في الفقرة.<br/>            **NullableBool.True** إذا كانت الرصاصة لها خط خاص و **NullableBool.False** إذا كانت الرصاحة<br/>            ترث الخط من الجزء الأول في الفقرة.<br/>            قراءة/كتابة [`NullableBool`](/slides/python-net/ar/aspose.slides/nullablebool). |

## الأساليب

| طريقة | الوصف |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/ar/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | يضبط الإزاحات غير الصفرية الافتراضية للمسافة البادئة (Indent) والهوامش اليسرى (MarginLeft) الفعّالة للفقرة عندما تكون الرصاصات مفعّلة (كما يفعل PowerPoint عند تفعيل رصاصات/ترقيم الفقرات). إذا تم تعطيل الرصاصات، يتم فقط إعادة تعيين المسافة البادئة والهوامش اليسرى للفقرة (كما يفعل PowerPoint عند تعطيل رصاصات/ترقيم الفقرات). تُطبّق إزاحات البادئة فيما يتعلق بسياق الرصاصة الحالي - IBulletFormat.Type، .NumberedBulletStyle و FontHeight للجزء الأول. تُطبّق الإزاحات غير الصفرية على المسافة البادئة والهوامش اليسرى الفعّالة للفقرة الحالية (جعل القيم الناتجة قيمًا محلية). |
| [`get_effective(self)`](/slides/python-net/ar/aspose.slides/ibulletformat/get_effective/#) | يجلب بيانات تنسيق الرصاصة الفعّالة مع تطبيق الوراثة. |

### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)