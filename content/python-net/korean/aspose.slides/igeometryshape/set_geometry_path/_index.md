---
title: set_geometry_path method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/igeometryshape/set_geometry_path/
weight: 70
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
주어진 [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) 객체에서 모양 기하학을 업데이트합니다. 좌표는 모양의 왼쪽 상단 모서리를 기준으로 상대적이어야 합니다.
모양의 유형 ([`IGeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/igeometryshape/shape_type))을 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM)(으)로 변경합니다.

```python
def set_geometry_path(self, geometry_path):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) | Geometry path |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | No path found |
| **RuntimeError(Proxy error(ArgumentException))** | Empty path found |

### 참고
* 클래스 [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath)
* 클래스 [`IGeometryShape`](/slides/python-net/ko/aspose.slides/igeometryshape)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)