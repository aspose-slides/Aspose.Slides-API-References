---
title: to_jpeg method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
입력 프레젠테이션을 JPEG 형식 이미지 집합으로 변환합니다.  
If the output file name is given as "myPath/myFilename.jpeg", the result will be saved as a set of "myPath/myFilename_N.jpeg" files, where N is a slide number.


```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ko/aspose.slides/presentation) | 입력 프레젠테이션. |
| output_file_name | **str** | 출력 파일 이름. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
입력 프레젠테이션을 JPEG 형식 이미지 집합으로 변환합니다.  
If the output file name is given as "myPath/myFilename.jpeg", the result will be saved as a set of "myPath/myFilename_N.jpeg" files, where N is a slide number.


```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ko/aspose.slides/presentation) | 입력 프레젠테이션 |
| output_file_name | **str** | 출력 파일 이름. |
| image_size | [`Size`](/slides/python-net/ko/aspose.slides/size) | 생성된 각 이미지의 크기. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
입력 프레젠테이션을 JPEG 형식 이미지 집합으로 변환합니다.  
If the output file name is given as "myPath/myFilename.jpeg", the result will be saved as a set of "myPath/myFilename_N.jpeg" files, where N is a slide number.


```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ko/aspose.slides/presentation) | 입력 프레젠테이션. |
| output_file_name | **str** | 출력 파일 이름. |
| scale | **float** | 원본 슬라이드 크기에 대한 출력 이미지의 스케일링 계수. |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | 렌더링 옵션. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### 참조
* 클래스 [`Convert`](/slides/python-net/ko/aspose.slides.lowcode/convert)
* 클래스 [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions)
* 클래스 [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)
* 클래스 [`Size`](/slides/python-net/ko/aspose.slides/size)
* 모듈 [`aspose.slides.lowcode`](/slides/python-net/ko/aspose.slides.lowcode)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)