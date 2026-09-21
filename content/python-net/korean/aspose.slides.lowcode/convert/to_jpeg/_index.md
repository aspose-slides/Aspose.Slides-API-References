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


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ko/aspose.slides/presentation) | The input presentation. |
| output_file_name | **str** | The output file name. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
입력 프레젠테이션을 JPEG 형식 이미지 집합으로 변환합니다.  
If the output file name is given as "myPath/myFilename.jpeg", the result will be saved as a set of "myPath/myFilename_N.jpeg" files, where N is a slide number.


```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ko/aspose.slides/presentation) | The input presentation |
| output_file_name | **str** | The output file name. |
| image_size | **aspose.slides.Size** | The size of each generated image. |

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


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ko/aspose.slides/presentation) | The input presentation. |
| output_file_name | **str** | The output file name. |
| scale | **float** | The scaling factor applied to the output images relative to the original slide size. |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | The rendering options. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### 참조
* 클래스 [`Convert`](/slides/python-net/ko/aspose.slides.lowcode/convert)
* 클래스 [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions)
* 클래스 [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)
* 모듈 [`aspose.slides.lowcode`](/slides/python-net/ko/aspose.slides.lowcode)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)