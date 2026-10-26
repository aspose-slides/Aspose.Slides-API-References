---
title: align_shapes method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
Thay đổi vị trí của tất cả các hình trên slide. Căn các hình tới lề hoặc mép của slide hoặc căn chúng tương đối với nhau.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/vi/aspose.slides/shapesalignmenttype) | Xác định loại căn nào sẽ được áp dụng. |
| align_to_slide | **bool** | Nếu true, các hình sẽ được căn tương đối với các cạnh của slide. |
| slide | [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide) | Slide cha. |

## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
Thay đổi vị trí của tất cả các hình trong nhóm hình. Căn các hình tới lề hoặc mép của slide hoặc căn chúng tương đối với nhau.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/vi/aspose.slides/shapesalignmenttype) | Xác định loại căn nào sẽ được áp dụng. |
| align_to_slide | **bool** | Nếu true, các hình sẽ được căn tương đối với các cạnh của slide. |
| group_shape | [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape) | Nhóm hình cha. |

## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
Thay đổi vị trí của các hình được chọn trên slide. Căn các hình tới lề hoặc mép của slide hoặc căn chúng tương đối với nhau.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/vi/aspose.slides/shapesalignmenttype) | Xác định loại căn nào sẽ được áp dụng. |
| align_to_slide | **bool** | Nếu true, các hình sẽ được căn tương đối với các cạnh của slide. |
| slide | [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide) | Slide cha. |
| shape_indexes | **List[int]** | Chỉ mục của các hình cần được căn. |

## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
Thay đổi vị trí của các hình được chọn trong nhóm hình. Căn các hình tới lề hoặc mép của slide hoặc căn chúng tương đối với nhau.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/vi/aspose.slides/shapesalignmenttype) | Xác định loại căn nào sẽ được áp dụng. |
| align_to_slide | **bool** | Nếu true, các hình sẽ được căn tương đối với các cạnh của slide. |
| group_shape | [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape) | Nhóm hình cha. |
| shape_indexes | **List[int]** | Chỉ mục của các hình cần được căn. |

### Xem thêm
* lớp [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide)
* lớp [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape)
* enumeration [`ShapesAlignmentType`](/slides/python-net/vi/aspose.slides/shapesalignmenttype)
* lớp [`SlideUtil`](/slides/python-net/vi/aspose.slides.util/slideutil)
* mô-đun [`aspose.slides.util`](/slides/python-net/vi/aspose.slides.util)
* library [`Aspose.Slides`](/slides/python-net)