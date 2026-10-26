---
title: insert_picture_frame method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/shapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
새로운 그림 프레임을 생성하고 지정된 이미지를 포함한 뒤, 지정된 인덱스에 도형 컬렉션에 삽입합니다.

### 반환값

새로 만든 [`IPictureFrame`](/slides/python-net/ko/aspose.slides/ipictureframe).

```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 그림 프레임을 삽입할 0부터 시작하는 인덱스. |
| shape_type | [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype)에 포함된 도형 유형을 지정합니다.<br/><br/>            단, 모든 종류의 선을 제외합니다:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | 그림 프레임의 x 좌표(포인트 단위). |
| y | **float** | 그림 프레임의 y 좌표(포인트 단위). |
| width | **float** | 그림 프레임의 너비(포인트 단위). |
| height | **float** | 그림 프레임의 높이(포인트 단위). |
| image | [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage) | 그림 프레임에 표시할 [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage). |

### 참고
* 클래스 [`IPictureFrame`](/slides/python-net/ko/aspose.slides/ipictureframe)
* 클래스 [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage)
* 클래스 [`ShapeCollection`](/slides/python-net/ko/aspose.slides/shapecollection)
* 열거형 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)