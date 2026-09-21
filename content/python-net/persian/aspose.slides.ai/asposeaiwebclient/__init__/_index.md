---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
یک نمونه از Aspose AI web client ایجاد می‌کند که به نقطه انتهایی پیش‌فرض Aspose LLM متصل می‌شود.
این همان کلاینتی است که توسط سازنده بدون پارامتر **SlidesAIAgent.#ctor** استفاده می‌شود، بنابراین ایجاد آن به‌صورت صریح فقط زمانی لازم است که کلاینت را مستقیماً به سازنده **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** منتقل کنید.


```python
def __init__(self):
    ...
```



## __init__(self, url) {#str}
یک نمونه از Aspose AI web client ایجاد می‌کند که به یک URL نقطه انتهایی سفارشی متصل می‌شود. از این overload زمانی استفاده کنید که URL توسط تیم Aspose.Slides فراهم شده باشد؛ در غیر این صورت، از overload **AsposeAIWebClient.#ctor** با URL پیش‌فرض استفاده کنید.


```python
def __init__(self, url):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| url | **str** | URL نقطه انتهایی Aspose LLM که توسط تیم Aspose.Slides فراهم شده است. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | URL نمی‌تواند None یا خالی باشد. |



### موارد مرتبط
* کلاس [`AsposeAIWebClient`](/slides/python-net/fa/aspose.slides.ai/asposeaiwebclient)
* ماژول [`aspose.slides.ai`](/slides/python-net/fa/aspose.slides.ai)
* کتابخانه [`Aspose.Slides`](/slides/python-net)