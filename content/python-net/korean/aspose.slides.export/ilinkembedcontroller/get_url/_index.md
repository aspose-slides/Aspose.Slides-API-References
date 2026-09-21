---
title: get_url method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
외부 객체에 대한 URL을 반환합니다.
            이 메서드는 항상 **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** 가 [`LinkEmbedDecision.LINK`](/slides/python-net/ko/aspose.slides.export/linkembeddecision/LINK) 를 반환한 경우 호출되며, **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** 가 [`LinkEmbedDecision.EMBED`](/slides/python-net/ko/aspose.slides.export/linkembeddecision/EMBED) 를 반환했지만 삽입이 불가능한 경우에도 호출될 수 있습니다.
            같은 객체 ID에 대해 여러 번 호출될 수 있습니다.

### 반환

외부 객체의 URL 또는 이 객체를 무시해야 할 경우 None.



```python
def get_url(self, id, referrer):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| id | **int** | 객체 ID. 이 ID는 저장 작업 전체에서 고유합니다. |
| referrer | **int** | 참조 객체의 ID 또는 루트 문서에 의해 객체가 참조되는 경우 0. 상대 링크 생성에 사용할 수 있습니다. |



### 관련 항목
* 클래스 [`ILinkEmbedController`](/slides/python-net/ko/aspose.slides.export/ilinkembedcontroller)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)