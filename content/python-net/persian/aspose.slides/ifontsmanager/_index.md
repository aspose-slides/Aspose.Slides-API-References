---
title: IFontsManager class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/ifontsmanager/
---
## IFontsManager کلاس

قلم‌ها را در تمام ارائه مدیریت می‌کند.

نوع IFontsManager اعضای زیر را در اختیار می‌گذارد:

## خصوصیات

| خاصیت | توضیح |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/fa/aspose.slides/ifontsmanager/font_subst_rule_list/) | جایگزینی‌های قلم برای استفاده هنگام رندرینگ<br/>            خواندن/نوشتن [`IFontSubstRuleCollection`](/slides/python-net/fa/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/fa/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | نمایش‌دهنده مجموعه قوانین FontFallBack کاربر برای مدیریت مجموعه‌های قلم‌ها برای جایگزینی صحیح توسط عملکرد fallback<br/>            خواندن/نوشتن [`IFontFallBackRulesCollection`](/slides/python-net/fa/aspose.slides/ifontfallbackrulescollection). |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/fa/aspose.slides/ifontsmanager/get_substitutions/#) | اطلاعاتی درباره قلم‌هایی که در رندرینگ ارائه جایگزین خواهند شد را دریافت می‌کند. |
| [`get_substitutions(self, slides)`](/slides/python-net/fa/aspose.slides/ifontsmanager/get_substitutions/#listint) | اطلاعاتی درباره قلم‌هایی که هنگام رندرینگ اسلایدهای مشخص‌شده جایگزین خواهند شد را دریافت می‌کند. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/fa/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | قلم توکار را اضافه می‌کند.<br/>            هنگام کپی کردن هر قلمی به خاطر داشته باشید که اکثر قلم‌ها دارای حق‌نشر هستند. ابتدا مجوز یک قلم را پیشاپیش پیدا کنید و تأیید کنید که می‌توانند به‌صورت آزاد به ماشین دیگری منتقل شوند. اگر داده‌های قلم None باشد یا این قلم پیش از این توکار شده باشد، ممکن است ArgumentException پرتاب شود |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/fa/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | قلم توکار را اضافه می‌کند<br/>            هنگام افزودن هر قلمی به خاطر داشته باشید که اکثر قلم‌ها دارای حق‌نشر هستند. ابتدا مجوز یک قلم را پیشاپیش پیدا کنید و تأیید کنید که می‌توانند به‌صورت آزاد به ماشین دیگری منتقل شوند. اگر داده‌های قلم None باشد یا این قلم پیش از این توکار شده باشد، ممکن است ArgumentException پرتاب شود |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/fa/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | جایگزین کردن قلم در ارائه |
| [`replace_font(self, subst_rule)`](/slides/python-net/fa/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | جایگزین کردن قلم در ارائه با استفاده از اطلاعات ارائه‌شده در [`IFontSubstRule`](/slides/python-net/fa/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/fa/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | جایگزین کردن قلم در ارائه با استفاده از اطلاعات ارائه‌شده در مجموعه‌ای از [`IFontSubstRule`](/slides/python-net/fa/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/fa/aspose.slides/ifontsmanager/get_fonts/#) | قلم‌های مورد استفاده در ارائه را برمی‌گرداند |
| [`get_embedded_fonts(self)`](/slides/python-net/fa/aspose.slides/ifontsmanager/get_embedded_fonts/#) | قلم‌های توکار در ارائه را برمی‌گرداند |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/fa/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | قلم توکار را حذف می‌کند |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/fa/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | آرایه بایت نمایانگر داده‌های قلم برای یک سبک قلم مشخص و داده‌های قلم را بازیابی می‌کند. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/fa/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | سطح توکاری یک قلم را از آرایه بایت و نام قلم داده‌شده تعیین می‌کند. |

### موارد مرتبط
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)