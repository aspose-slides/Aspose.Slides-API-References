---
title: get_object_storing_location method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
객체가 저장되어야 하는 위치를 결정합니다.
            이 메서드는 각각의 객체 ID마다 한 번 호출됩니다.
            동일한 데이터와 semanticName 및 contentType을 가지고 있지만 서로 다른 ID를 가진 두 객체가 존재하지 않을 것이라는 보장은 없습니다.

### 반환
결정



```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```



| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| id | **int** | 객체 ID. 이 ID는 저장 작업 전체에서 고유합니다. |
| entity_data | **bytes** | 객체 바이너리 데이터. 아직 객체 바이너리 데이터가 생성되지 않은 경우 이 매개변수는 None일 수 있습니다. |
| semantic_name | **str** | 객체의 의미를 설명하는 짧은 텍스트입니다. 컨트롤러는 이를 외부 객체 이름의 일부로 사용할 수 있지만, 이름이 고유하고 허용된 문자만 포함하도록 보장하는 것은 디스패처의 책임입니다. |
| content_type | **str** | 객체의 MIME 타입. |
| recomended_extension | **str** | 이 MIME 타입에 권장되는 파일 이름 확장자. |



### 참고
* 클래스 [`ILinkEmbedController`](/slides/python-net/ko/aspose.slides.export/ilinkembedcontroller)
* 열거형 [`LinkEmbedDecision`](/slides/python-net/ko/aspose.slides.export/linkembeddecision)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)