---
title: ILinkEmbedController class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController 클래스

저장 중 객체가 어떻게 처리되어야 하는지를 결정하는 콜백 인터페이스입니다.

ILinkEmbedController 유형은 다음 멤버를 노출합니다.

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/ko/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | 객체가 저장되어야 할 위치를 결정합니다.<br/>            이 메서드는 각 객체 ID마다 한 번 호출됩니다.<br/>            동일한 data, semanticName 및 contentType을 가지지만 ID가 다른 두 객체가 존재하지 않을 것이라는 보장은 없습니다. |
| [`get_url(self, id, referrer)`](/slides/python-net/ko/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | 외부 객체에 대한 URL을 반환합니다.<br/>            이 메서드는 **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** 가 [`LinkEmbedDecision.LINK`](/slides/python-net/ko/aspose.slides.export/linkembeddecision/LINK) 을 반환할 경우 항상 호출되며, **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** 가 [`LinkEmbedDecision.EMBED`](/slides/python-net/ko/aspose.slides.export/linkembeddecision/EMBED) 을 반환할 경우에도 임베딩이 불가능할 때 호출될 수 있습니다.<br/>            같은 객체 ID에 대해 여러 번 호출될 수 있습니다. |
| [`save_external(self, id, entity_data)`](/slides/python-net/ko/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | 외부 객체를 저장합니다. |


### 관련 항목
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)