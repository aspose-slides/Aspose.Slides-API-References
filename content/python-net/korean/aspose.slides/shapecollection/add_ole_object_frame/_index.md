---
title: add_ole_object_frame method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/shapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
새 OLE 개체 프레임을 생성하고 쉐이프 컬렉션 끝에 추가합니다.

### 반환값

새로 생성된 [`IOleObjectFrame`](/slides/python-net/ko/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x | **float** | 새로운 OLE 프레임의 x좌표(포인트 단위)입니다. |
| y | **float** | 새로운 OLE 프레임의 y좌표(포인트 단위)입니다. |
| width | **float** | 새로운 OLE 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 새로운 OLE 프레임의 높이(포인트 단위)입니다. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/ko/aspose.slides/ioleembeddeddatainfo) | 포함된 OLE 데이터에 대한 정보([`IOleEmbeddedDataInfo`](/slides/python-net/ko/aspose.slides/ioleembeddeddatainfo))입니다. |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
새 OLE 개체 프레임을 생성하고 쉐이프 컬렉션 끝에 추가합니다.

### 반환값

새로 생성된 [`IOleObjectFrame`](/slides/python-net/ko/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x | **float** | 새로운 OLE 프레임의 x좌표(포인트 단위)입니다. |
| y | **float** | 새로운 OLE 프레임의 y좌표(포인트 단위)입니다. |
| width | **float** | 새로운 OLE 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 새로운 OLE 프레임의 높이(포인트 단위)입니다. |
| class_name | **str** | OLE 개체의 클래스 이름입니다. |
| path | **str** | 링크된 파일의 경로입니다.<br/><br/>이 경로는 프레젠테이션에 그대로 저장됩니다.<br/><br/>상대 경로가 지정된 경우, 다른 디렉터리에서 프레젠테이션을 열면 파일에 접근할 수 없습니다. |



### 또한 보기
* 클래스 [`IOleEmbeddedDataInfo`](/slides/python-net/ko/aspose.slides/ioleembeddeddatainfo)
* 클래스 [`IOleObjectFrame`](/slides/python-net/ko/aspose.slides/ioleobjectframe)
* 클래스 [`ShapeCollection`](/slides/python-net/ko/aspose.slides/shapecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)