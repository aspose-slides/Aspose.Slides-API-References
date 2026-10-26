---
title: SlidesAIAgent class
second_title: Aspose.Slides برای پایتون از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent کلاس

امکانات مبتنی بر هوش مصنوعی را برای پردازش ارائه‌ها فراهم می‌کند.

نوع SlidesAIAgent اعضای زیر را نشان می‌دهد:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/fa/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | یک نمونه جدید از [`SlidesAIAgent`](/slides/python-net/fa/aspose.slides.ai/slidesaiagent) را با یک کلاینت AI سفارشی مقداردهی اولیه می‌کند.<br/>            برای مشخص کردن فراهم‌کننده AI، ارائه LLM خودتان، یا سفارشی‌سازی<br/>            اتصال (به عنوان مثال، با فراهم کردن `HttpClient` خود)، از این overload استفاده کنید.<br/>            می‌توان از هر پیاده‌سازی از [`IAIWebClient`](/slides/python-net/fa/aspose.slides.ai/iaiwebclient) استفاده کرد، از جمله:<br/>            <br/>* [`AsposeAIWebClient`](/slides/python-net/fa/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/fa/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/fa/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>            برای استفاده از [`AsposeAIWebClient`](/slides/python-net/fa/aspose.slides.ai/asposeaiwebclient) داخلی با پیکربندی پیش‌فرض آن،<br/>            به‌جای آن از overload **SlidesAIAgent.#ctor** استفاده کنید. |
| [`__init__(self)`](/slides/python-net/fa/aspose.slides.ai/slidesaiagent/__init__/#) | یک نمونه جدید از [`SlidesAIAgent`](/slides/python-net/fa/aspose.slides.ai/slidesaiagent) را با استفاده از [`AsposeAIWebClient`](/slides/python-net/fa/aspose.slides.ai/asposeaiwebclient) داخلی<br/>            با پیکربندی پیش‌فرض آن مقداردهی اولیه می‌کند. کلاینت به LLM خود Aspose متصل می‌شود و نیازی به پیکربندی اضافی ندارد.<br/>            برای استفاده از کلاینت AI متفاوت، به‌جای آن از overload **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** استفاده کنید. |

## متدها

| متد | توضیح |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/fa/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | یک نمونه ارائه را از توضیح متنی تولید می‌کند. یک موضوع، ایده، نقل قول یا قطعات متنی را به زبان مورد نیاز ارائه دهید. |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/fa/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | یک نمونه ارائه را از توضیح متنی تولید می‌کند. یک موضوع، ایده، نقل قول یا قطعات متنی را به زبان مورد نیاز ارائه دهید. |
| [`translate(self, presentation, language)`](/slides/python-net/fa/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | یک ارائه را به زبان مشخص‌شده با استفاده از هوش مصنوعی ترجمه می‌کند (نسخه همزمان). |

### موارد مرتبط
* کلاس [`AsposeAIWebClient`](/slides/python-net/fa/aspose.slides.ai/asposeaiwebclient)
* کلاس [`IAIWebClient`](/slides/python-net/fa/aspose.slides.ai/iaiwebclient)
* کلاس [`OpenAICompatibleWebClient`](/slides/python-net/fa/aspose.slides.ai/openaicompatiblewebclient)
* کلاس [`OpenAIWebClient`](/slides/python-net/fa/aspose.slides.ai/openaiwebclient)
* کلاس [`SlidesAIAgent`](/slides/python-net/fa/aspose.slides.ai/slidesaiagent)
* ماژول [`aspose.slides.ai`](/slides/python-net/fa/aspose.slides.ai)
* کتابخانه [`Aspose.Slides`](/slides/python-net)