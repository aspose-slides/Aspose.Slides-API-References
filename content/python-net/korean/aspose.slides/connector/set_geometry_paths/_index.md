---
title: set_geometry_paths method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/connector/set_geometry_paths/
weight: 100
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
배열 [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath)에서 도형 기하학을 업데이트합니다. 좌표는 도형의 왼쪽 위 모서리를 기준으로 해야 합니다. 도형의 유형([`GeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/geometryshape/shape_type))을 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM)으로 변경합니다.

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | 배열 기하 경로 |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 경로를 찾을 수 없음 |
| **RuntimeError(Proxy error(ArgumentException))** | 빈 경로 |

### 참조
* 클래스 [`Connector`](/slides/python-net/ko/aspose.slides/connector)
* 클래스 [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)