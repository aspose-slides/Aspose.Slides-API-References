---
title: FontsManager class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/fontsmanager/
---
## FontsManager الفئة

يدير الخطوط عبر العرض التقديمي.

يعرض نوع FontsManager الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/ar/aspose.slides/fontsmanager/font_subst_rule_list/) | بدائل الخطوط التي يتم استخدامها عند العرض.<br/>            قراءة/كتابة [`IFontSubstRuleCollection`](/slides/python-net/ar/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/ar/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | يمثل مجموعة المستخدم من قواعد FontFallBack لإدارة مجموعات الخطوط من أجل الاستبدالات المناسبة عبر وظيفة التعويض.<br/>            قراءة/كتابة [`IFontFallBackRulesCollection`](/slides/python-net/ar/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/ar/aspose.slides/fontsmanager/prefer_registered_fonts_over_embedded/) | يحدد ما إذا كان يجب تفضيل الخطوط المسجلة على الخطوط المضمنة التي لها نفس اسم الخط والنمط.<br/>            عند التفعيل، يتم استبدال الخطوط المضمنة المتطابقة مؤقتًا بالخطوط المسجلة المقابلة أثناء التصدير. |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/ar/aspose.slides/fontsmanager/get_substitutions/#) | يجلب المعلومات حول الخطوط التي سيتم استبدالها أثناء عرض العرض التقديمي. |
| [`get_substitutions(self, slides)`](/slides/python-net/ar/aspose.slides/fontsmanager/get_substitutions/#listint) | يجلب المعلومات حول الخطوط التي سيتم استبدالها أثناء عرض الشرائح المحددة. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/ar/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | يضيف الخط المضمن<br/>            ضع في اعتبارك عند نسخ أي خطوط أن معظم الخطوط محمية بحقوق النشر. أولاً ابحث عن ترخيص الخط<br/>            قبل الاستخدام وتأكد من أنه يمكن نقله بحرية إلى جهاز آخر. يمكن رمي استثناء ArgumentException إذا كانت بيانات الخط None أو إذا كان هذا الخط مضمّنًا بالفعل |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/ar/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | يضيف الخط المضمن<br/>            ضع في اعتبارك عند نسخ أي خطوط أن معظم الخطوط محمية بحقوق النشر. أولاً ابحث عن ترخيص الخط<br/>            قبل الاستخدام وتأكد من أنه يمكن نقله بحرية إلى جهاز آخر. يمكن رمي استثناء ArgumentException إذا كانت بيانات الخط None أو إذا كان هذا الخط مضمّنًا بالفعل |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/ar/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | استبدال الخط في العرض التقديمي |
| [`replace_font(self, subst_rule)`](/slides/python-net/ar/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | استبدال الخط في العرض التقديمي باستخدام المعلومات المقدمة في [`FontSubstRule`](/slides/python-net/ar/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/ar/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | استبدال الخط في العرض التقديمي باستخدام المعلومات المقدمة في مجموعة من [`FontSubstRule`](/slides/python-net/ar/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/ar/aspose.slides/fontsmanager/get_fonts/#) | يُرجِع الخطوط المستخدمة في العرض التقديمي |
| [`get_embedded_fonts(self)`](/slides/python-net/ar/aspose.slides/fontsmanager/get_embedded_fonts/#) | يُرجِع الخطوط المضمنة في العرض التقديمي |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/ar/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | يزيل الخط المضمن |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/ar/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | يسترجع مصفوفة البايت التي تمثل بيانات الخط لنمط خط محدد وبيانات الخط. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/ar/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | يحدد مستوى تضمين الخط من مصفوفة البايت المعطاة واسم الخط. |

### أنظر أيضاً
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)