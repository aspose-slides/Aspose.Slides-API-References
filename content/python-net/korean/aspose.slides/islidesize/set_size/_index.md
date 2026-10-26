---
title: set_size method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
형식에 따라 슬라이드 크기를 설정하고 기존 콘텐츠를 확대/축소합니다.


```python
def set_size(self, type, scale_type):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/ko/aspose.slides/slidesizetype) | 적용할 사전 정의된 슬라이드 크기입니다. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/ko/aspose.slides/slidesizescaletype) | 사용할 콘텐츠 확대/축소 모드입니다. |

### 비고

[`SlideSizeType.CUSTOM`](/slides/python-net/ko/aspose.slides/slidesizetype/CUSTOM) 외의 값을 할당하면 선택된 형식에 따라 [`ISlideSize.size`](/slides/python-net/ko/aspose.slides/islidesize/size)가 조정되며, [`ISlideSize.orientation`](/slides/python-net/ko/aspose.slides/islidesize/orientation)는 유지됩니다.


## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
슬라이드 차원을 명시적으로 설정하고 기존 콘텐츠를 확대/축소합니다.


```python
def set_size(self, width, height, scale_type):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| width | **float** | 새 슬라이드 너비(포인트 단위)입니다. |
| height | **float** | 새 슬라이드 높이(포인트 단위)입니다. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/ko/aspose.slides/slidesizescaletype) | 사용할 콘텐츠 확대/축소 모드입니다. |

### 비고

이 작업은 [`ISlideSize.type`](/slides/python-net/ko/aspose.slides/islidesize/type) 속성을 [`SlideSizeType.CUSTOM`](/slides/python-net/ko/aspose.slides/slidesizetype/CUSTOM)로 재설정하고 [`ISlideSize.orientation`](/slides/python-net/ko/aspose.slides/islidesize/orientation)를 설정합니다.



### 참고
* 
* 클래스 [`ISlideSize`](/slides/python-net/ko/aspose.slides/islidesize)
* 열거형 [`SlideSizeScaleType`](/slides/python-net/ko/aspose.slides/slidesizescaletype)
* 열거형 [`SlideSizeType`](/slides/python-net/ko/aspose.slides/slidesizetype)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)