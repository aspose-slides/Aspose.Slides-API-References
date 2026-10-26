---
title: add_from_html method
second_title: Aspose.Slides برای Python از طریق مرجع API .NET
description: 
type: docs
url: /fa/aspose.slides/paragraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
متن را از رشتهٔ html مشخص به مجموعه اضافه می‌کند.

```python
def add_from_html(self, text):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| text | **str** | متن HTML. |

## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
متن را از رشتهٔ html مشخص به مجموعه اضافه می‌کند.

```python
def add_from_html(self, text, resolver, uri):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| text | **str** | متن HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fa/aspose.slides.importing/iexternalresourceresolver) | شیء callback حل‌کننده که URIها را حل می‌کند و اشیای ارجاع داده شده را دریافت می‌کند. |
| uri | **str** | URI برای افزودن سند HTML. برای حل پیوندهای نسبی استفاده می‌شود. |

### توضیحات
مشخص کردن resolver می‌تواند به‌طور بالقوه یک آسیب‌پذیری ایجاد کند. با احتیاط استفاده کنید.

### موارد مرتبط
* کلاس [`IExternalResourceResolver`](/slides/python-net/fa/aspose.slides.importing/iexternalresourceresolver)
* کلاس [`ParagraphCollection`](/slides/python-net/fa/aspose.slides/paragraphcollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)