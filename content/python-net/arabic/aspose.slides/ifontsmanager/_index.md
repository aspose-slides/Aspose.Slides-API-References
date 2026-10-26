---
title: IFontsManager class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/ifontsmanager/
---
## IFontsManager class

يدير الخطوط عبر العرض التقديمي.

نوع IFontsManager يعرّف الأعضاء التالية:

## الخصائص

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/ar/aspose.slides/ifontsmanager/font_subst_rule_list/) | استبدالات الخط لاستخدامها عند العرض<br/>            قراءة/كتابة [`IFontSubstRuleCollection`](/slides/python-net/ar/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/ar/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | يمثل مجموعة المستخدم من قواعد FontFallBack لإدارة مجموعات الخطوط لاستبدالات صحيحة بواسطة وظيفة fallback<br/>            قراءة/كتابة [`IFontFallBackRulesCollection`](/slides/python-net/ar/aspose.slides/ifontfallbackrulescollection). |

## الطرق

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/ar/aspose.slides/ifontsmanager/get_substitutions/#) | يحصل على المعلومات حول الخطوط التي سيتم استبدالها أثناء عرض العرض التقديمي. |
| [`get_substitutions(self, slides)`](/slides/python-net/ar/aspose.slides/ifontsmanager/get_substitutions/#listint) | يحصل على المعلومات حول الخطوط التي سيتم استبدالها أثناء عرض الشرائح المحددة. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/ar/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | يضيف الخط المضمّن.<br/>            ضع في الاعتبار عند نسخ أي خطوط أن معظم الخطوط محمية بحقوق النشر. أولاً ابحث عن ترخيص الخط <br/>            قبل ذلك وتحقق من إمكانية نقلها بحرية إلى جهاز آخر. يمكن رمي ArgumentException إذا كانت بيانات الخط None أو إذا كان هذا الخط مضمّنًا بالفعل |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/ar/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | يضيف الخط المضمّن<br/>            ضع في الاعتبار عند إضافة أي خطوط أن معظم الخطوط محمية بحقوق النشر. أولاً ابحث عن ترخيص الخط <br/>            قبل ذلك وتحقق من إمكانية نقلها بحرية إلى جهاز آخر. يمكن رمي ArgumentException إذا كانت بيانات الخط None أو إذا كان هذا الخط مضمّنًا بالفعل |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/ar/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | استبدال الخط في العرض التقديمي |
| [`replace_font(self, subst_rule)`](/slides/python-net/ar/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | استبدال الخط في العرض التقديمي باستخدام المعلومات المقدمة في [`IFontSubstRule`](/slides/python-net/ar/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/ar/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | استبدال الخط في العرض التقديمي باستخدام المعلومات المقدمة في مجموعة من [`IFontSubstRule`](/slides/python-net/ar/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/ar/aspose.slides/ifontsmanager/get_fonts/#) | يعيد الخطوط المستخدمة في العرض التقديمي |
| [`get_embedded_fonts(self)`](/slides/python-net/ar/aspose.slides/ifontsmanager/get_embedded_fonts/#) | يعيد الخطوط المضمّنة في العرض التقديمي |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/ar/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | يزيل الخط المضمّن |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/ar/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | يسترجع مصفوفة البايت التي تمثل بيانات الخط لنمط خط محدد وبيانات الخط. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/ar/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | يحدد مستوى تضمين الخط من مصفوفة البايت المعطاة واسم الخط. |


### راجع أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)