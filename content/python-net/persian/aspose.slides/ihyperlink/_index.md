---
title: IHyperlink class
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/ihyperlink/
---
## IHyperlink کلاس

Represents a hyperlink.

The IHyperlink type exposes the following members:

## ویژگی‌ها

| Property | Description |
| :- | :- |
| [`action_type`](/slides/python-net/fa/aspose.slides/ihyperlink/action_type/) | Returns type of HyperLinkEx's action.<br/>            فقط‌خواندنی [`HyperlinkActionType`](/slides/python-net/fa/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/fa/aspose.slides/ihyperlink/external_url/) | URL خارجی را مشخص می‌کند<br/>            اگر این ویژگی مقدار None نگیرد، ویژگی TargetSlide مقدار None می‌گیرد.<br/>            فقط‌خواندنی **str**. |
| [`external_url_original`](/slides/python-net/fa/aspose.slides/ihyperlink/external_url_original/) | یک پیوند را نشان می‌دهد که برای این بخش تنظیم شده است بدون توجه به محتوای واقعی بخش.<br/>            <br/>            PowerPoint رفتار خاصی نسبت به پیوندها و متن متناظر آن‌ها در یک بخش دارد. این امکان را می‌دهد که متن پیوند را به شکل یک URL معتبر ایجاد کند که با آدرس واقعی پیوند متفاوت باشد. در این حالت، هنگامی که پیوند را در پنجره ویرایش مشاهده می‌کنید، به متن بخش تبدیل می‌شود. این ویژگی مقدار اصلی پیوند را نشان می‌دهد. |
| [`target_slide`](/slides/python-net/fa/aspose.slides/ihyperlink/target_slide/) | اگر HyperlinkEx به اسلاید خاصی هدف داشته باشد، این اسلاید را برمی‌گرداند.<br/>            اگر این ویژگی مقدار None نگیرد، ویژگی ExternalUrl مقدار None می‌گیرد.<br/>            فقط‌خواندنی [`ISlide`](/slides/python-net/fa/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/fa/aspose.slides/ihyperlink/target_frame/) | Returns the frame within the parent HTML frameset for the target<br/>            of the parent hyperlink when one exists.<br/>            خواندنی/قابل‌نوشتن **str**. |
| [`tooltip`](/slides/python-net/fa/aspose.slides/ihyperlink/tooltip/) | Returns the string which may be surfaced in a user interface<br/>            as associated with the parent hyperlink.<br/>            خواندنی/قابل‌نوشتن **str**. |
| [`history`](/slides/python-net/fa/aspose.slides/ihyperlink/history/) | Determines whether the target of the parent hyperlink shall be added<br/>            to a list of viewed hyperlinks when it is invoked.<br/>            خواندنی/قابل‌نوشتن **bool**. |
| [`highlight_click`](/slides/python-net/fa/aspose.slides/ihyperlink/highlight_click/) | Determines whether the hyperlink should be highlighted on click.<br/>            خواندنی/قابل‌نوشتن **bool**. |
| [`stop_sound_on_click`](/slides/python-net/fa/aspose.slides/ihyperlink/stop_sound_on_click/) | Determines whether the sound should be stopped on hyperlink click.<br/>            خواندنی/قابل‌نوشتن **bool**. |
| [`sound`](/slides/python-net/fa/aspose.slides/ihyperlink/sound/) | Represents the playing sound of the hyperlink.<br/>            خواندنی/قابل‌نوشتن [`IAudio`](/slides/python-net/fa/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/fa/aspose.slides/ihyperlink/color_source/) | Represents the source of hyperlink color - either styles or portion format.<br/>            خواندنی/قابل‌نوشتن [`HyperlinkColorSource`](/slides/python-net/fa/aspose.slides/hyperlinkcolorsource). |

## متدها

| Method | Description |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/fa/aspose.slides/ihyperlink/equals/#ihyperlink) | Determines whether the two Hyperlink instances are equal. |

### همچنین ببینید
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)