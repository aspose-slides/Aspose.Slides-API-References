---
title: IFontsManager class
second_title: Aspose.Slides للـ Python عبر مرجع API لـ .NET
description: 
type: docs
url: /ar/aspose.slides/ifontsmanager/
---
## IFontsManager فئة

يدير الخطوط عبر العرض التقديمي.

نوع IFontsManager يكشف عن الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/ar/aspose.slides/ifontsmanager/font_subst_rule_list/) | بدائل الخطوط المستخدمة عند العرض<br/>            قراءة/كتابة [`IFontSubstRuleCollection`](/slides/python-net/ar/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/ar/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | يمثل مجموعة المستخدم من قواعد FontFallBack لإدارة مجموعات الخطوط لبدائل صحيحة عبر وظيفة الرجوع الاحتياطي<br/>            قراءة/كتابة [`IFontFallBackRulesCollection`](/slides/python-net/ar/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/ar/aspose.slides/ifontsmanager/prefer_registered_fonts_over_embedded/) | يحدد ما إذا كان يجب تفضيل الخطوط المسجلة على الخطوط المضمنة التي تحمل نفس اسم الخط والنمط.<br/>            عند التفعيل، يتم استبدال الخطوط المضمنة المطابقة مؤقتًا بالخطوط المسجلة المقابلة أثناء التصدير. |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/ar/aspose.slides/ifontsmanager/get_substitutions/#) | يحصل على المعلومات حول الخطوط التي سيتم استبدالها عند عرض العرض التقديمي. |
| [`get_substitutions(self, slides)`](/slides/python-net/ar/aspose.slides/ifontsmanager/get_substitutions/#listint) | يحصل على المعلومات حول الخطوط التي سيتم استبدالها أثناء عرض الشرائح المحددة. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/ar/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | يضيف الخط المضمن.<br/>            ضع في اعتبارك عند نسخ أي خطوط أن معظم الخطوط محمية بحقوق النشر. أولاً حدد رخصة <br/>            الخط مسبقًا وتأكد من أنه يمكن نقلها بحرية إلى جهاز آخر. يمكن أن يتم رمي استثناء ArgumentException إذا كانت بيانات الخط None أو أن هذا الخط مضمّن مسبقًا |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/ar/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | يضيف الخط المضمن.<br/>            ضع في اعتبارك عند إضافة أي خطوط أن معظم الخطوط محمية بحقوق النشر. أولاً حدد رخصة <br/>            الخط مسبقًا وتأكد من أنه يمكن نقلها بحرية إلى جهاز آخر. يمكن أن يتم رمي استثناء ArgumentException إذا كانت بيانات الخط None أو أن هذا الخط مضمّن مسبقًا |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/ar/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | استبدال الخط في العرض التقديمي |
| [`replace_font(self, subst_rule)`](/slides/python-net/ar/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | استبدال الخط في العرض التقديمي باستخدام المعلومات المقدمة في [`IFontSubstRule`](/slides/python-net/ar/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/ar/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | استبدال الخط في العرض التقديمي باستخدام المعلومات المقدمة في مجموعة من [`IFontSubstRule`](/slides/python-net/ar/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/ar/aspose.slides/ifontsmanager/get_fonts/#) | يعيد الخطوط المستخدمة في العرض التقديمي |
| [`get_embedded_fonts(self)`](/slides/python-net/ar/aspose.slides/ifontsmanager/get_embedded_fonts/#) | يعيد الخطوط المضمنة في العرض التقديمي |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/ar/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | يزيل الخط المضمن |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/ar/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | يقوم باسترجاع مصفوفة البايت التي تمثل بيانات الخط لنمط خط محدد وبيانات الخط. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/ar/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | يحدد مستوى تضمين الخط من مصفوفة البايت المقدمة واسم الخط. |

### انظر أيضًا
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)