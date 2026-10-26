---
title: FontsManager class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/fontsmanager/
---
## FontsManager کلاس

Manages fonts across the presentation.

The FontsManager type exposes the following members:

## ویژگی‌ها

| خاصیت | توضیح |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/fa/aspose.slides/fontsmanager/font_subst_rule_list/) | جایگزینی‌های قلم برای استفاده در هنگام رندر.<br/>            Read/write [`IFontSubstRuleCollection`](/slides/python-net/fa/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/fa/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | نمایانگر مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های قلم‌ها به‌منظور جایگزینی صحیح توسط عملکرد fallback.<br/>            Read/write [`IFontFallBackRulesCollection`](/slides/python-net/fa/aspose.slides/ifontfallbackrulescollection). |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/fa/aspose.slides/fontsmanager/get_substitutions/#) | اطلاعات مربوط به قلم‌هایی که در رندر ارائه جایگزین خواهند شد را دریافت می‌کند. |
| [`get_substitutions(self, slides)`](/slides/python-net/fa/aspose.slides/fontsmanager/get_substitutions/#listint) | اطلاعات مربوط به قلم‌هایی که در رندر اسلایدهای مشخص شده جایگزین خواهند شد را دریافت می‌کند. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/fa/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | قلم جاسازی شده را اضافه می‌کند<br/>            هنگام کپی کردن هر قلمی به‌خاطر داشته باشید که اکثر قلم‌ها دارای حق تکثیر هستند. ابتدا مجوز یک قلم را پیشاپیش پیدا کنید و تأیید کنید که می‌تواند به‌صورت رایگان به ماشین دیگری منتقل شود. اگر داده‌های قلم None باشد یا این قلم قبلاً جاسازی شده باشد، یک ArgumentException می‌تواند پرتاب شود |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/fa/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | قلم جاسازی شده را اضافه می‌کند<br/>            هنگام کپی کردن هر قلمی به‌خاطر داشته باشید که اکثر قلم‌ها دارای حق تکثیر هستند. ابتدا مجوز یک قلم را پیشاپیش پیدا کنید و تأیید کنید که می‌تواند به‌صورت رایگان به ماشین دیگری منتقل شود. اگر داده‌های قلم None باشد یا این قلم قبلاً جاسازی شده باشد، یک ArgumentException می‌تواند پرتاب شود |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/fa/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | قلم را در ارائه جایگزین می‌کند |
| [`replace_font(self, subst_rule)`](/slides/python-net/fa/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | قلم را در ارائه با استفاده از اطلاعات ارائه شده در [`FontSubstRule`](/slides/python-net/fa/aspose.slides/fontsubstrule) جایگزین می‌کند |
| [`replace_font(self, subst_rules)`](/slides/python-net/fa/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | قلم را در ارائه با استفاده از اطلاعات ارائه شده در مجموعه‌ای از [`FontSubstRule`](/slides/python-net/fa/aspose.slides/fontsubstrule) جایگزین می‌کند |
| [`get_fonts(self)`](/slides/python-net/fa/aspose.slides/fontsmanager/get_fonts/#) | قلم‌های استفاده شده در ارائه را برمی‌گرداند |
| [`get_embedded_fonts(self)`](/slides/python-net/fa/aspose.slides/fontsmanager/get_embedded_fonts/#) | قلم‌های جاسازی شده در ارائه را برمی‌گرداند |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/fa/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | قلم جاسازی شده را حذف می‌کند |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/fa/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | آرایه بایتی که داده‌های قلم برای سبک قلم مشخص‌شده را نشان می‌دهد را بازیابی می‌کند. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/fa/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | سطح جاسازی یک قلم را از آرایه بایت داده‌شده و نام قلم تعیین می‌کند. |


### همچنین ببینید
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)