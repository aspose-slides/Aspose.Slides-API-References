---
title: insert_ole_object_frame method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/ishapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
새로운 OLE 개체 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

### 반환값

새로 생성된 [`IOleObjectFrame`](/slides/python-net/ko/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | **int** | OLE 개체 프레임을 삽입할 0부터 시작하는 인덱스입니다. |
| x | **float** | 새로운 OLE 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새로운 OLE 프레임의 y 좌표(포인트 단위)입니다. |
| width | **float** | 새로운 OLE 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 새로운 OLE 프레임의 높이(포인트 단위)입니다. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/ko/aspose.slides/ioleembeddeddatainfo) | 내장된 OLE 데이터 정보([`IOleEmbeddedDataInfo`](/slides/python-net/ko/aspose.slides/ioleembeddeddatainfo))입니다. |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
새로운 OLE 개체 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

### 반환값

새로 생성된 [`IOleObjectFrame`](/slides/python-net/ko/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | **int** | OLE 개체 프레임을 삽입할 0부터 시작하는 인덱스입니다. |
| x | **float** | 새로운 OLE 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새로운 OLE 프레임의 y 좌표(포인트 단위)입니다. |
| width | **float** | 새로운 OLE 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 새로운 OLE 프레임의 높이(포인트 단위)입니다. |
| class_name | **str** | OLE 개체의 클래스 이름입니다. |
| path | **str** | 링크된 파일의 경로입니다. <br/><br/>이 경로는 프레젠테이션에 그대로 저장됩니다.<br/><br/>            상대 경로를 지정하면 다른 디렉터리에서 프레젠테이션을 열 때 파일에 접근할 수 없습니다.<br/><br/>            |



### 참고
* class [`IOleEmbeddedDataInfo`](/slides/python-net/ko/aspose.slides/ioleembeddeddatainfo)
* class [`IOleObjectFrame`](/slides/python-net/ko/aspose.slides/ioleobjectframe)
* class [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)