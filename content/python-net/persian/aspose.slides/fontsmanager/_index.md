---
title: FontsManager class
second_title: Aspose.Slides برای پایتون از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/fontsmanager/
---
## FontsManager کلاس

فونت‌ها را در سراسر ارائه مدیریت می‌کند.

نوع FontsManager اعضای زیر را در دسترس می‌گذارد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/fa/aspose.slides/fontsmanager/font_subst_rule_list/) | جایگزین‌های فونت برای استفاده هنگام رندر.<br/>            خواندن/نوشتن [`IFontSubstRuleCollection`](/slides/python-net/fa/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/fa/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | نمایش مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های فونت جهت جایگزینی مناسب با عملکرد fallback<br/>            خواندن/نوشتن [`IFontFallBackRulesCollection`](/slides/python-net/fa/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/fa/aspose.slides/fontsmanager/prefer_registered_fonts_over_embedded/) | مشخص می‌کند آیا فونت‌های ثبت‌شده باید بر فونت‌های توکار با همان نام و سبک فونت ترجیح داده شوند یا خیر.<br/>            وقتی فعال باشد، فونت‌های توکار مطابقت یافته به‌صورت موقت با فونت‌های ثبت‌شده مربوطه هنگام صادرات جایگزین می‌شوند. |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/fa/aspose.slides/fontsmanager/get_substitutions/#) | اطلاعات مربوط به فونت‌هایی که در رندر ارائه جایگزین خواهند شد را بازیابی می‌کند. |
| [`get_substitutions(self, slides)`](/slides/python-net/fa/aspose.slides/fontsmanager/get_substitutions/#listint) | اطلاعات مربوط به فونت‌هایی که هنگام رندر اسلایدهای مشخص‌شده جایگزین خواهند شد را دریافت می‌کند. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/fa/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | فونت توکار را اضافه می‌کند<br/>            به‌یاد داشته باشید هنگام کپی کردن هر فونتی اکثر فونت‌ها تحت حق‌نشر هستند. ابتدا مجوز یک فونت را پیشاپیش پیدا کنید و تأیید کنید که می‌توانند به‌آزادانه به ماشین دیگری منتقل شوند. اگر دادهٔ فونت None باشد یا این فونت قبلاً توکار باشد می‌تواند ArgumentException رخ دهد |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/fa/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | فونت توکار را اضافه می‌کند<br/>            به‌یاد داشته باشید هنگام کپی کردن هر فونتی اکثر فونت‌ها تحت حق‌نشر هستند. ابتدا مجوز یک فونت را پیشاپیش پیدا کنید و تأیید کنید که می‌توانند به‌آزادانه به ماشین دیگری منتقل شوند. اگر دادهٔ فونت None باشد یا این فونت قبلاً توکار باشد می‌تواند ArgumentException رخ دهد |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/fa/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | فونت را در ارائه جایگزین کنید |
| [`replace_font(self, subst_rule)`](/slides/python-net/fa/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | فونت را در ارائه با استفاده از اطلاعات ارائه‌شده در [`FontSubstRule`](/slides/python-net/fa/aspose.slides/fontsubstrule) جایگزین کنید |
| [`replace_font(self, subst_rules)`](/slides/python-net/fa/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | فونت را در ارائه با استفاده از اطلاعات ارائه‌شده در مجموعهٔ [`FontSubstRule`](/slides/python-net/fa/aspose.slides/fontsubstrule) جایگزین کنید |
| [`get_fonts(self)`](/slides/python-net/fa/aspose.slides/fontsmanager/get_fonts/#) | فونت‌های استفاده‌شده در ارائه را باز می‌گرداند |
| [`get_embedded_fonts(self)`](/slides/python-net/fa/aspose.slides/fontsmanager/get_embedded_fonts/#) | فونت‌های توکار در ارائه را باز می‌گرداند |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/fa/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | فونت توکار را حذف می‌کند |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/fa/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | آرایه بایتی که دادهٔ فونت را برای یک سبک فونت مشخص و دادهٔ فونت بیان می‌کند را بازیابی می‌کند. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/fa/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | سطح توکار بودن یک فونت را از آرایه بایت داده‌شده و نام فونت تعیین می‌کند. |

### موارد مرتبط
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)