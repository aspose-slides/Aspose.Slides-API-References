---
title: Hyperlink constructor
second_title: Aspose.Slides للغة بايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
ينشئ كائنًا من ارتباط تشعبي.

```python
def __init__(self, url):
    ...
```

| معامل | نوع | وصف |
| :- | :- | :- |
| url | **str** | عنوان URL للارتباط التشعبي. |

## __init__(self, slide) {#islide}
ينشئ كائنًا من ارتباط تشعبي يشير إلى شريحة معينة.
ملاحظة: يجب تعيين الارتباط التشعبي المُنشأ إلى كائن من نفس العرض التقديمي، وإلا سيتم حفظ الرابط كـ NoAction.

```python
def __init__(self, slide):
    ...
```

| معامل | نوع | وصف |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الشريحة المستهدفة. |

## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
ينشئ كائنًا من ارتباط تشعبي باستخدام ارتباط تشعبي آخر كمصدر، مع تجاوز الخصائص الثانوية.

```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```

| معامل | نوع | وصف |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/ar/aspose.slides/hyperlink) | الارتباط التشعبي المصدر |
| target_frame | **str** | إطار الهدف |
| tooltip | **str** | نص تلميح الأداة |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |

### انظر أيضا
* الفئة [`Hyperlink`](/slides/python-net/ar/aspose.slides/hyperlink)
* الفئة [`ISlide`](/slides/python-net/ar/aspose.slides/islide)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)