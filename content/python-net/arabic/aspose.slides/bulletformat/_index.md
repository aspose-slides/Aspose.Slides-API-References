---
title: BulletFormat class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/bulletformat/
---
## فئة BulletFormat

Represents paragraph bullet formatting properties.

**Inheritance:**[`BulletFormat`](/slides/python-net/ar/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/ar/aspose.slides/pviobject)

The BulletFormat type exposes the following members:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`type`](/slides/python-net/ar/aspose.slides/bulletformat/type/) | إرجاع أو تعيين نوع النقطة لفقرة دون وراثة.<br/>            قراءة/كتابة [`BulletType`](/slides/python-net/ar/aspose.slides/bullettype). |
| [`char`](/slides/python-net/ar/aspose.slides/bulletformat/char/) | إرجاع أو تعيين حرف النقطة لفقرة دون وراثة.<br/>            قراءة/كتابة **System.Char**. |
| [`font`](/slides/python-net/ar/aspose.slides/bulletformat/font/) | إرجاع أو تعيين خط النقطة لفقرة دون وراثة.<br/>            قراءة/كتابة [`IFontData`](/slides/python-net/ar/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/ar/aspose.slides/bulletformat/height/) | إرجاع أو تعيين ارتفاع النقطة لفقرة دون وراثة.<br/>            القيمة float.NaN تحدد أن النقطة تورث الارتفاع من الجزء الأول في الفقرة.<br/>            قراءة/كتابة **float**. |
| [`color`](/slides/python-net/ar/aspose.slides/bulletformat/color/) | إرجاع تنسيق لون النقطة لفقرة دون وراثة.<br/>            قراءة فقط [`IColorFormat`](/slides/python-net/ar/aspose.slides/icolorformat). |
| [`numbered_bullet_start_with`](/slides/python-net/ar/aspose.slides/bulletformat/numbered_bullet_start_with/) | إرجاع أو تعيين الرقم الأول المستخدم لمجموعة نقاط مرقمة دون وراثة.<br/>            قراءة/كتابة **int**. |
| [`numbered_bullet_style`](/slides/python-net/ar/aspose.slides/bulletformat/numbered_bullet_style/) | إرجاع أو تعيين نمط النقطة المرقمة دون وراثة.<br/>            قراءة/كتابة [`NumberedBulletStyle`](/slides/python-net/ar/aspose.slides/numberedbulletstyle). |
| [`is_bullet_hard_color`](/slides/python-net/ar/aspose.slides/bulletformat/is_bullet_hard_color/) | يحدد ما إذا كانت النقطة لها لون خاص أو تورثه من الجزء الأول في الفقرة.<br/>            **NullableBool.True** إذا كانت النقطة لها لون خاص و **NullableBool.False** إذا كانت النقطة<br/>            تورث اللون من الجزء الأول في الفقرة.<br/>            قراءة/كتابة [`NullableBool`](/slides/python-net/ar/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/ar/aspose.slides/bulletformat/is_bullet_hard_font/) | يحدد ما إذا كانت النقطة لها خط خاص أو تورثه من الجزء الأول في الفقرة.<br/>            **NullableBool.True** إذا كانت النقطة لها خط خاص و **NullableBool.False** إذا كانت النقطة<br/>            تورث الخط من الجزء الأول في الفقرة.<br/>            قراءة/كتابة [`NullableBool`](/slides/python-net/ar/aspose.slides/nullablebool). |
| [`picture`](/slides/python-net/ar/aspose.slides/bulletformat/picture/) | إرجاع الصورة المستخدمة كنقطة في فقرة دون وراثة.<br/>            قراءة فقط [`ISlidesPicture`](/slides/python-net/ar/aspose.slides/islidespicture). |
| [`slide`](/slides/python-net/ar/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides/bulletformat/presentation/) |  |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/ar/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | يضبط الإزاحات غير الصفرية الافتراضية للمسافة البادئة الفعالة للفقرة (Indent) والمسافة اليسرى (MarginLeft) عندما تكون النقاط مفعلة (كما يفعل PowerPoint عند تمكين نقاط/ترقيم الفقرات). إذا تم إلغاء تفعيل النقاط يتم فقط إعادة ضبط Indent وMarginLeft للفقرة (كما يفعل PowerPoint عند إلغاء تفعيل نقاط/ترقيم الفقرات). تُطبق إزاحات البادئة بالنسبة لسياق النقطة الحالي - IBulletFormat.Type، .NumberedBulletStyle وFontHeight للجزء الأول. تُطبق إزاحات البادئة غير الصفرية على Indent وMarginLeft الفعليين للفقرة الحالية (لتصبح القيم ناتجة محلية). |
| [`get_effective(self)`](/slides/python-net/ar/aspose.slides/bulletformat/get_effective/#) | يحصل على بيانات تنسيق النقطة الفعّالة مع تطبيق الوراثة. |


### انظر أيضًا
* class [`BulletFormat`](/slides/python-net/ar/aspose.slides/bulletformat)
* class [`PVIObject`](/slides/python-net/ar/aspose.slides/pviobject)
* module [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)