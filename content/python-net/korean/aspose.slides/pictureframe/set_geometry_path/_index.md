---
title: set_geometry_path method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/pictureframe/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
업데이트된 [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) 객체에서 도형 기하학을 변경합니다. 좌표는 도형의 왼쪽 위 모서리를 기준으로 상대적이어야 합니다.
도형 유형([`GeometryShape.shape_type`](/slides/python-net/ko/aspose.slides/geometryshape/shape_type))을 [`ShapeType.CUSTOM`](/slides/python-net/ko/aspose.slides/shapetype/CUSTOM)로 변경합니다.


```python
def set_geometry_path(self, geometry_path):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath) | 기하 경로 |


### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 경로를 찾을 수 없습니다 |
| **RuntimeError(Proxy error(ArgumentException))** | 빈 경로를 찾았습니다 |



### 참고
* 클래스 [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath)
* 클래스 [`PictureFrame`](/slides/python-net/ko/aspose.slides/pictureframe)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)