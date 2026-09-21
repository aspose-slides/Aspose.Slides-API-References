---
title: add_from_html method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
متن را از رشتهٔ HTML مشخص به مجموعه اضافه می‌کند.


```python
def add_from_html(self, text):
    ...
```


| پارامتر | نوع | توضیحات |
| :- | :- | :- |
| text | **str** | متن HTML. |


## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
متن را از رشتهٔ HTML مشخص به مجموعه اضافه می‌کند.


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| پارامتر | نوع | توضیحات |
| :- | :- | :- |
| text | **str** | متن HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fa/aspose.slides.importing/iexternalresourceresolver) | شیء بازگشت فراخوان resolver که URIها را حل می‌کند و اشیای ارجاع داده‌شده را دریافت می‌کند. |
| uri | **str** | URI برای افزودن سند HTML. برای حل لینک‌های نسبی استفاده می‌شود. |

### توضیحات

مشخص کردن resolver می‌تواند به‌احتمال یک آسیب‌پذیری منجر شود. با احتیاط استفاده کنید.



### مراجع
* کلاس [`IExternalResourceResolver`](/slides/python-net/fa/aspose.slides.importing/iexternalresourceresolver)
* کلاس [`IParagraphCollection`](/slides/python-net/fa/aspose.slides/iparagraphcollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)