---
title: generate_presentation method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
یک نمونه ارائه را از یک توصیف متنی تولید می‌کند. یک موضوع، ایده‌ها، نقل‌قول‌ها یا قطعات متنی را به زبان مورد نیاز فراهم کنید.


```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| description | **str** | موضوع، ایده‌ها، نقل‌قول‌ها یا قطعات متنی. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/fa/aspose.slides.ai/presentationcontentamounttype) | مقدار محتوا در ارائهٔ تولید شده. |

### توضیحات

مثال زیر از پیش‌فرض [`AsposeAIWebClient`](/slides/python-net/fa/aspose.slides.ai/asposeaiwebclient) استفاده می‌کند که توسط سازنده بدون پارامتر **SlidesAIAgent.#ctor** ایجاد شده و به LLM داخلی Aspose متصل می‌شود. برای استفاده از ارائه‌دهندهٔ AI دیگری، LLM خود را فراهم کنید یا اتصال را سفارشی کنید (برای مثال، با فراهم کردن `HttpClient` خود)، یک پیاده‌سازی [`IAIWebClient`](/slides/python-net/fa/aspose.slides.ai/iaiwebclient) را به سازنده **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** بدهید. پیاده‌سازی‌های موجود شامل:
             
* [`AsposeAIWebClient`](/slides/python-net/fa/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/fa/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/fa/aspose.slides.ai/openaicompatiblewebclient)

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | دستور گفت‌وگوی AI نمی‌تواند None یا خالی باشد. |


## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
یک نمونه ارائه را از یک توصیف متنی تولید می‌کند. یک موضوع، ایده‌ها، نقل‌قول‌ها یا قطعات متنی را به زبان مورد نیاز فراهم کنید.


```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| description | **str** | موضوع، ایده‌ها، نقل‌قول‌ها یا قطعات متنی. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/fa/aspose.slides.ai/presentationcontentamounttype) | مقدار محتوا در ارائهٔ تولید شده. |
| presentation_template | [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation) | ارائه‌ای برای استفاده به‌عنوان الگو برای چیدمان و طراحی، که الگوی پیش‌فرض را جایگزین می‌کند. |

### توضیحات

مثال زیر از پیش‌فرض [`AsposeAIWebClient`](/slides/python-net/fa/aspose.slides.ai/asposeaiwebclient) استفاده می‌کند که توسط سازنده بدون پارامتر **SlidesAIAgent.#ctor** ایجاد شده و به LLM داخلی Aspose متصل می‌شود. برای استفاده از ارائه‌دهندهٔ AI دیگری، LLM خود را فراهم کنید یا اتصال را سفارشی کنید (برای مثال، با فراهم کردن `HttpClient` خود)، یک پیاده‌سازی [`IAIWebClient`](/slides/python-net/fa/aspose.slides.ai/iaiwebclient) را به سازنده **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** بدهید. پیاده‌سازی‌های موجود شامل:
            
* [`AsposeAIWebClient`](/slides/python-net/fa/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/fa/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/fa/aspose.slides.ai/openaicompatiblewebclient)

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | قالب ارائه ارائه نشده است. |
| **RuntimeError(Proxy error(ArgumentException))** | دستور گفت‌وگوی AI نمی‌تواند None یا خالی باشد. |



### موارد مرتبط
* class [`AsposeAIWebClient`](/slides/python-net/fa/aspose.slides.ai/asposeaiwebclient)
* class [`IAIWebClient`](/slides/python-net/fa/aspose.slides.ai/iaiwebclient)
* class [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation)
* class [`OpenAICompatibleWebClient`](/slides/python-net/fa/aspose.slides.ai/openaicompatiblewebclient)
* class [`OpenAIWebClient`](/slides/python-net/fa/aspose.slides.ai/openaiwebclient)
* enumeration [`PresentationContentAmountType`](/slides/python-net/fa/aspose.slides.ai/presentationcontentamounttype)
* class [`SlidesAIAgent`](/slides/python-net/fa/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/fa/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)