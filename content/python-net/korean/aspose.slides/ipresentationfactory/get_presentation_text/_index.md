---
title: get_presentation_text method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/ipresentationfactory/get_presentation_text/
weight: 30
---
## get_presentation_text(self, file, mode) {#str-textextractionarrangingmode}
슬라이드에서 원시 텍스트를 검색합니다

### 반환값
원시 슬라이드 텍스트를 나타내는 SlideText 배열을 포함하는 PresentationText 인스턴스



```python
def get_presentation_text(self, file, mode):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file | **str** | 입력 파일 |
| mode | [`TextExtractionArrangingMode`](/slides/python-net/ko/aspose.slides/textextractionarrangingmode) | 추출 모드 |


## get_presentation_text(self, stream, mode) {#iorawiobase-textextractionarrangingmode}
슬라이드에서 원시 텍스트를 검색합니다

### 반환값
원시 슬라이드 텍스트를 나타내는 SlideText 배열을 포함하는 PresentationText 인스턴스



```python
def get_presentation_text(self, stream, mode):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 입력 스트림 |
| mode | [`TextExtractionArrangingMode`](/slides/python-net/ko/aspose.slides/textextractionarrangingmode) | 추출 모드 |


## get_presentation_text(self, stream, mode, options) {#iorawiobase-textextractionarrangingmode-iloadoptions}
슬라이드에서 원시 텍스트를 검색합니다

### 반환값
원시 슬라이드 텍스트를 나타내는 SlideText 배열을 포함하는 PresentationText 인스턴스



```python
def get_presentation_text(self, stream, mode, options):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 입력 스트림 |
| mode | [`TextExtractionArrangingMode`](/slides/python-net/ko/aspose.slides/textextractionarrangingmode) | 추출 모드 |
| options | [`ILoadOptions`](/slides/python-net/ko/aspose.slides/iloadoptions) | 로드 옵션 |



### 참고
* 클래스 [`ILoadOptions`](/slides/python-net/ko/aspose.slides/iloadoptions)
* 클래스 [`IPresentationFactory`](/slides/python-net/ko/aspose.slides/ipresentationfactory)
* 클래스 [`IPresentationText`](/slides/python-net/ko/aspose.slides/ipresentationtext)
* 열거형 [`TextExtractionArrangingMode`](/slides/python-net/ko/aspose.slides/textextractionarrangingmode)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)