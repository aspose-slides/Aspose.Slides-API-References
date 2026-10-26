---
title: get_font_bytes method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/fontsmanager/get_font_bytes/
weight: 30
---
## get_font_bytes(self, font_data, font_style) {#ifontdata-fontstyletype}
지정된 폰트 스타일 및 폰트 데이터에 대한 폰트 데이터를 나타내는 바이트 배열을 검색합니다.

### 반환값

지정된 폰트 스타일에 대한 폰트 데이터를 포함하는 바이트 배열을 반환합니다. 폰트 데이터나 스타일을 찾을 수 없는 경우, None을 반환합니다.



```python
def get_font_bytes(self, font_data, font_style):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| font_data | [`IFontData`](/slides/python-net/ko/aspose.slides/ifontdata) | 폰트 [`IFontData`](/slides/python-net/ko/aspose.slides/ifontdata)에 대한 정보를 포함하는 폰트 데이터 객체. |
| font_style | [`FontStyleType`](/slides/python-net/ko/aspose.slides/fontstyletype) | 데이터를 검색하려는 폰트의 스타일 [`FontStyleType`](/slides/python-net/ko/aspose.slides/fontstyletype). |



### 참고
* 클래스 [`FontsManager`](/slides/python-net/ko/aspose.slides/fontsmanager)
* 열거형 [`FontStyleType`](/slides/python-net/ko/aspose.slides/fontstyletype)
* 클래스 [`IFontData`](/slides/python-net/ko/aspose.slides/ifontdata)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)