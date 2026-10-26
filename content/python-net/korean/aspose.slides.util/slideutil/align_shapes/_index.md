---
title: align_shapes method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
슬라이드의 모든 도형 배치를 변경합니다. 도형을 여백이나 슬라이드 가장자리에 맞추거나
            서로 상대적으로 정렬합니다.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/ko/aspose.slides/shapesalignmenttype) | 적용될 정렬 유형을 결정합니다. |
| align_to_slide | **bool** | true이면 도형이 슬라이드 가장자를 기준으로 정렬됩니다. |
| slide | [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide) | 부모 슬라이드. |

## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
그룹 도형 내 모든 도형의 배치를 변경합니다. 도형을 여백이나 슬라이드 가장자리에 맞추거나
            서로 상대적으로 정렬합니다.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/ko/aspose.slides/shapesalignmenttype) | 적용될 정렬 유형을 결정합니다. |
| align_to_slide | **bool** | true이면 도형이 슬라이드 가장자를 기준으로 정렬됩니다. |
| group_shape | [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape) | 부모 그룹 도형. |

## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
선택된 도형의 배치를 슬라이드에서 변경합니다. 도형을 여백이나 슬라이드 가장자리에 맞추거나
            서로 상대적으로 정렬합니다.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/ko/aspose.slides/shapesalignmenttype) | 적용될 정렬 유형을 결정합니다. |
| align_to_slide | **bool** | true이면 도형이 슬라이드 가장자를 기준으로 정렬됩니다. |
| slide | [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide) | 부모 슬라이드. |
| shape_indexes | **List[int]** | 정렬될 도형의 인덱스. |

## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
그룹 도형 내 선택된 도형의 배치를 변경합니다. 도형을 여백이나 슬라이드 가장자리에 맞추거나
            서로 상대적으로 정렬합니다.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/ko/aspose.slides/shapesalignmenttype) | 적용될 정렬 유형을 결정합니다. |
| align_to_slide | **bool** | true이면 도형이 슬라이드 가장자를 기준으로 정렬됩니다. |
| group_shape | [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape) | 부모 그룹 도형. |
| shape_indexes | **List[int]** | 정렬될 도형의 인덱스. |

### 참고
* 클래스 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide)
* 클래스 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape)
* 열거형 [`ShapesAlignmentType`](/slides/python-net/ko/aspose.slides/shapesalignmenttype)
* 클래스 [`SlideUtil`](/slides/python-net/ko/aspose.slides.util/slideutil)
* 모듈 [`aspose.slides.util`](/slides/python-net/ko/aspose.slides.util)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)