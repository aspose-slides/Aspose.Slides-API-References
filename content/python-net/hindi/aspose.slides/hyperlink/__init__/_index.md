---
title: Hyperlink constructor
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
एक हाइपरलिंक का एक उदाहरण बनाता है।

```python
def __init__(self, url):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| url | **str** | हाइपरलिंक URL। |

## __init__(self, slide) {#islide}
एक हाइपरलिंक का एक उदाहरण बनाता है जो विशिष्ट स्लाइड की ओर इशारा करता है।

नोट: बनाया गया हाइपरलिंक उसी प्रस्तुति के किसी ऑब्जेक्ट को असाइन किया जाना चाहिए, अन्यथा लिंक NoAction के रूप में सहेजा जाएगा।

```python
def __init__(self, slide):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | लक्षित स्लाइड। |

## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
एक अन्य हाइपरलिंक को स्रोत के रूप में उपयोग करके, द्वितीयक गुणों को ओवरराइड करते हुए, एक हाइपरलिंक का उदाहरण बनाता है।

```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/hi/aspose.slides/hyperlink) | स्रोत हाइपरलिंक |
| target_frame | **str** | लक्षित फ्रेम |
| tooltip | **str** | टूलटिप टेक्स्ट |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |

### संबंधित देखें
* class [`Hyperlink`](/slides/python-net/hi/aspose.slides/hyperlink)
* class [`ISlide`](/slides/python-net/hi/aspose.slides/islide)
* module [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)