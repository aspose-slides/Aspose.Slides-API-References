---
title: to_tiff method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
입력 프레젠테이션을 TIFF 형식 이미지 집합으로 변환합니다.  
            출력 파일 이름을 "myPath/myFilename.tiff" 로 지정하면, 결과는 "myPath/myFilename_N.tiff" 파일 집합으로 저장되며, N은 슬라이드 번호입니다.


```python
@staticmethod
def to_tiff(pres, output_file_name):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ko/aspose.slides/presentation) | 입력 프레젠테이션. |
| output_file_name | **str** | 출력 파일 이름. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
입력 프레젠테이션을 사용자 지정 옵션으로 TIFF 형식으로 변환합니다.  
            출력 파일 이름을 "myPath/myFilename.tiff" 로 지정하고 `multipage` 가 `false` 인 경우, 결과는 "myPath/myFilename_N.tiff" 파일 집합으로 저장되며, N은 슬라이드 번호입니다.  
            반대로 `multipage` 가 `true` 인 경우, 결과는 다중 페이지 "myPath/myFilename.tiff" 문서가 됩니다.


```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ko/aspose.slides/presentation) | 입력 프레젠테이션. |
| output_file_name | **str** | 출력 파일 이름. |
| options | [`ITiffOptions`](/slides/python-net/ko/aspose.slides.export/itiffoptions) | TIFF 저장 옵션. |
| multipage | **bool** | 생성된 TIFF 문서가 다중 페이지여야 하는지 여부를 지정합니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### 참고
* 클래스 [`Convert`](/slides/python-net/ko/aspose.slides.lowcode/convert)
* 클래스 [`ITiffOptions`](/slides/python-net/ko/aspose.slides.export/itiffoptions)
* 클래스 [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)
* 모듈 [`aspose.slides.lowcode`](/slides/python-net/ko/aspose.slides.lowcode)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)