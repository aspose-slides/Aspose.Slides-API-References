---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/paragraph/get_image/
weight: 20
---
## get_image(self) {#}
단락의 이미지를 반환합니다.

### 반환값

렌더링된 단락을 포함하는 이미지이며, **None**
             단락을 상위 컬렉션에서 찾을 수 없거나, 유효한 렌더링 경계가 없거나, 이미지를 렌더링하는 중 오류가 발생한 경우

```python
def get_image(self):
    ...
```

## get_image(self, scale_x, scale_y) {#float-float}
지정된 배율로 단락의 이미지를 반환합니다.

### 반환값

렌더링된 단락을 포함하는 이미지이며, **None**
             단락을 상위 컬렉션에서 찾을 수 없거나, 유효한 렌더링 경계가 없거나, 이미지를 렌더링하는 중 오류가 발생한 경우

```python
def get_image(self, scale_x, scale_y):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| scale_x | **float** | 단락 이미지에 적용되는 가로 배율 계수입니다. |
| scale_y | **float** | 단락 이미지에 적용되는 세로 배율 계수입니다. |

### 또 보기
* 클래스 [`IImage`](/slides/python-net/ko/aspose.slides/iimage)
* 클래스 [`Paragraph`](/slides/python-net/ko/aspose.slides/paragraph)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)