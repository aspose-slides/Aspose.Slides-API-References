---
title: set_geometry_paths method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/pictureframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
배열 [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath)에서 도형 기하학을 업데이트합니다. 좌표는 도형의 왼쪽 위 모서리를 기준으로 상대적이어야 합니다. 도형의 유형([`GeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/geometryshape/shape_type))을 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM)로 변경합니다.

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
| **RuntimeError(Proxy error(ArgumentException))** | 경로를 찾을 수 없음 |
| **RuntimeError(Proxy error(ArgumentException))** | 경로가 비어 있음 |

### 참고
* 클래스 [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath)
* 클래스 [`PictureFrame`](/slides/python-net/ko/aspose.slides/pictureframe)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)