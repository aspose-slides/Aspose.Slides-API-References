---
title: add_group_shape method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/ishapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
새로운 빈 그룹 형상을 생성하고 이를 형상 컬렉션의 끝에 추가합니다.
            그룹의 프레임은 추가된 모든 형상에 맞게 자동으로 조정됩니다.

### 반환

새로 생성된 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape).



```python
def add_group_shape(self):
    ...
```



## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
새로운 그룹 형상을 생성하고 지정된 SVG 이미지를 개별 형상으로 변환한 다음, 결과 그룹을 형상 컬렉션의 끝에 추가합니다.

### 반환

새로 생성된 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape).



```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/ko/aspose.slides/isvgimage) | 벡터 콘텐츠를 형상으로 변환하기 위해 포함된 [`ISvgImage`](/slides/python-net/ko/aspose.slides/isvgimage). |
| x | **float** | 그룹 프레임의 x 좌표(포인트 단위). |
| y | **float** | 그룹 프레임의 y 좌표(포인트 단위). |
| width | **float** | 그룹 프레임의 너비(포인트 단위). |
| height | **float** | 그룹 프레임의 높이(포인트 단위). |



### 참조
* 클래스 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape)
* 클래스 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection)
* 클래스 [`ISvgImage`](/slides/python-net/ko/aspose.slides/isvgimage)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)