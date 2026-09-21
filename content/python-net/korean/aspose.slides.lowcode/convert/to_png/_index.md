---
title: to_png method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
입력 프레젠테이션을 PNG 형식 이미지 세트로 변환합니다.  
            출력 파일 이름을 "myPath/myFilename.png" 로 지정하면, 결과는 "myPath/myFilename_N.png" 파일 세트로 저장되며, N은 슬라이드 번호입니다.


```python
@staticmethod
def to_png(pres, output_file_name):
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


## to_png(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
입력 프레젠테이션을 PNG 형식 이미지 세트로 변환합니다.  
            출력 파일 이름을 "myPath/myFilename.png" 로 지정하면, 결과는 "myPath/myFilename_N.png" 파일 세트로 저장되며, N은 슬라이드 번호입니다.


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ko/aspose.slides/presentation) | 입력 프레젠테이션 |
| output_file_name | **str** | 출력 파일 이름. |
| image_size | **aspose.slides.Size** | 각 생성된 이미지의 크기. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
입력 프레젠테이션을 PNG 형식 이미지 세트로 변환합니다.  
            출력 파일 이름을 "myPath/myFilename.png" 로 지정하면, 결과는 "myPath/myFilename_N.png" 파일 세트로 저장되며, N은 슬라이드 번호입니다.


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ko/aspose.slides/presentation) | 입력 프레젠테이션. |
| output_file_name | **str** | 출력 파일 이름. |
| scale | **float** | 원본 슬라이드 크기에 대한 출력 이미지의 적용 스케일링 계수. |
| options | [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions) | 렌더링 옵션. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### 참고
* 클래스 [`Convert`](/slides/python-net/ko/aspose.slides.lowcode/convert)
* 클래스 [`IRenderingOptions`](/slides/python-net/ko/aspose.slides.export/irenderingoptions)
* 클래스 [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)
* 모듈 [`aspose.slides.lowcode`](/slides/python-net/ko/aspose.slides.lowcode)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)