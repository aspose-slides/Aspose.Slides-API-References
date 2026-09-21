---
title: set_size method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/slidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
슬라이드 크기를 유형별로 설정하고 기존 콘텐츠를 스케일합니다.


```python
def set_size(self, type, scale_type):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/ko/aspose.slides/slidesizetype) | 적용할 미리 정의된 슬라이드 크기입니다. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/ko/aspose.slides/slidesizescaletype) | 사용할 콘텐츠 스케일링 모드입니다. |

### 비고

[`SlideSizeType.CUSTOM`](/slides/python-net/ko/aspose.slides/slidesizetype/CUSTOM) 이외의 값을 할당하면 선택한 유형에 따라 [`SlideSize.size`](/slides/python-net/ko/aspose.slides/slidesize/size) 가 조정되며, [`SlideSize.orientation`](/slides/python-net/ko/aspose.slides/slidesize/orientation) 를 보존합니다.


## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
슬라이드 크기를 명시적으로 설정하고 기존 콘텐츠를 스케일합니다.


```python
def set_size(self, width, height, scale_type):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| width | **float** | 새 슬라이드 너비(포인트 단위)입니다. |
| height | **float** | 새 슬라이드 높이(포인트 단위)입니다. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/ko/aspose.slides/slidesizescaletype) | 사용할 콘텐츠 스케일링 모드입니다. |

### 비고

이 작업은 [`SlideSize.type`](/slides/python-net/ko/aspose.slides/slidesize/type) 속성을 [`SlideSizeType.CUSTOM`](/slides/python-net/ko/aspose.slides/slidesizetype/CUSTOM) 로 재설정하고 [`SlideSize.orientation`](/slides/python-net/ko/aspose.slides/slidesize/orientation) 를 설정합니다.



### 참고
* 클래스 [`SlideSize`](/slides/python-net/ko/aspose.slides/slidesize)
* 열거형 [`SlideSizeScaleType`](/slides/python-net/ko/aspose.slides/slidesizescaletype)
* 열거형 [`SlideSizeType`](/slides/python-net/ko/aspose.slides/slidesizetype)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)