---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
يقوم بإنشاء مثيل لعميل الويب Aspose AI الذي يتصل بنقطة النهاية الافتراضية لـ Aspose LLM.  
هذا هو العميل المستخدم من قبل منشئ **SlidesAIAgent.#ctor** بدون معلمات، لذلك لا يكون إنشاءه صراحةً مطلوبًا إلا عند تمرير العميل إلى منشئ **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** مباشرةً.


```python
def __init__(self):
    ...
```



## __init__(self, url) {#str}
يقوم بإنشاء مثيل لعميل الويب Aspose AI الذي يتصل بعنوان URL لنقطة نهاية مخصصة. استخدم هذا التحميل الزائد عندما يكون لديك عنوان URL مقدم من فريق Aspose.Slides؛ وإلا، استخدم التحميل الزائد **AsposeAIWebClient.#ctor** مع عنوان URL الافتراضي.


```python
def __init__(self, url):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| url | **str** | عنوان URL لنقطة النهاية لـ Aspose LLM، المقدم من فريق Aspose.Slides. |

### استثناءات

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | لا يمكن أن يكون URL فارغًا أو غير محدد. |



### انظر أيضًا
* الفئة [`AsposeAIWebClient`](/slides/python-net/ar/aspose.slides.ai/asposeaiwebclient)
* الوحدة [`aspose.slides.ai`](/slides/python-net/ar/aspose.slides.ai)
* المكتبة [`Aspose.Slides`](/slides/python-net)