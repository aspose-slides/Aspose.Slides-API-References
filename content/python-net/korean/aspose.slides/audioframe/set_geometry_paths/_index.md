---
title: set_geometry_paths method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/audioframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
모양의 지오메트리를 [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) 배열에서 업데이트합니다. 좌표는 모양의 왼쪽 상단 모서를 기준으로 상대적이어야 합니다. 모양의 유형 ([`GeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/geometryshape/shape_type))을 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM)(으)로 변경합니다.

```python
def set_geometry_paths(self, geometry_paths):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | 배열 지오메트리 경로 |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 경로를 찾을 수 없습니다 |
| **RuntimeError(Proxy error(ArgumentException))** | 빈 경로 |



### 참고
* 클래스 [`AudioFrame`](/slides/python-net/ko/aspose.slides/audioframe)
* 클래스 [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)