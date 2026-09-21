---
title: set_geometry_paths method
second_title: Aspose.Slides Python용 .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.smartart/smartartshape/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
[`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) 배열에서 도형 기하 정보를 업데이트합니다. 좌표는 도형의 왼쪽 위 모서리를 기준으로 상대적이어야 합니다. 도형의 유형([`GeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/geometryshape/shape_type))을 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM)(으)로 변경합니다.

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | 배열 기하 경로 |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 경로를 찾을 수 없습니다 |
| **RuntimeError(Proxy error(ArgumentException))** | 경로가 비어 있습니다 |

### 참조
* 클래스 [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath)
* 클래스 [`SmartArtShape`](/slides/python-net/ko/aspose.slides.smartart/smartartshape)
* 모듈 [`aspose.slides.smartart`](/slides/python-net/ko/aspose.slides.smartart)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)