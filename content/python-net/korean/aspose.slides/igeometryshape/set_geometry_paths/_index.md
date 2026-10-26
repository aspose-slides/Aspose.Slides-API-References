---
title: set_geometry_paths method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/igeometryshape/set_geometry_paths/
weight: 80
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
모양 기하학을 [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) 배열에서 업데이트합니다. 좌표는 모양의 왼쪽 위 모서리를 기준으로 상대적이어야 합니다. 모양의 유형([`IGeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/igeometryshape/shape_type))을 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM) 로 변경합니다.

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
| **RuntimeError(Proxy error(ArgumentException))** | 경로를 찾을 수 없습니다 |
| **RuntimeError(Proxy error(ArgumentException))** | 경로가 비어 있습니다 |

### 참고
* 클래스 [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath)
* 클래스 [`IGeometryShape`](/slides/python-net/ko/aspose.slides/igeometryshape)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)