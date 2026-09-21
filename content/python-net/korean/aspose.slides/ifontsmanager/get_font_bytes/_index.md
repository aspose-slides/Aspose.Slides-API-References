---
title: get_font_bytes method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/ifontsmanager/get_font_bytes/
weight: 30
---
## get_font_bytes(self, font_data, font_style) {#ifontdata-fontstyletype}
지정된 font style와 font data에 대한 글꼴 데이터를 나타내는 바이트 배열을 반환합니다.

### 반환값

지정된 font style에 대한 font data를 포함하는 바이트 배열. font data 또는 style을 찾을 수 없는 경우, None을 반환합니다.



```python
def get_font_bytes(self, font_data, font_style):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| font_data | [`IFontData`](/slides/python-net/ko/aspose.slides/ifontdata) | font [`IFontData`](/slides/python-net/ko/aspose.slides/ifontdata)에 대한 정보를 포함하는 font data 객체. |
| font_style | [`FontStyleType`](/slides/python-net/ko/aspose.slides/fontstyletype) | 데이터를 검색해야 하는 font의 스타일 [`FontStyleType`](/slides/python-net/ko/aspose.slides/fontstyletype). |



### 관련 항목
* enumeration [`FontStyleType`](/slides/python-net/ko/aspose.slides/fontstyletype)
* class [`IFontData`](/slides/python-net/ko/aspose.slides/ifontdata)
* class [`IFontsManager`](/slides/python-net/ko/aspose.slides/ifontsmanager)
* module [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)