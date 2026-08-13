---
title: GetUrl()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "외부 객체에 대한 URL을 반환합니다. 이 메서드는 ILinkEmbedController::GetObjectStoringLocation이 LinkEmbedDecision::Link를 반환한 경우 항상 호출되며, ILinkEmbedController::GetObjectStoringLocation이 LinkEmbedDecision::Embed를 반환했지만 삽입이 불가능한 경우에도 호출될 수 있습니다. 동일한 객체 ID에 대해 여러 번 호출될 수 있습니다."
type: docs
weight: 14
url: /ko/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) 메서드


외부 객체에 대한 URL을 반환합니다. 이 메서드는 [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/)가 [LinkEmbedDecision::Link](../../linkembeddecision/)를 반환한 경우 항상 호출되며, [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/)가 [LinkEmbedDecision::Embed](../../linkembeddecision/)를 반환했지만 삽입이 불가능한 경우에도 호출될 수 있습니다. 동일한 객체 ID에 대해 여러 번 호출될 수 있습니다.

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| id | **int32_t** | 객체 ID. 이 ID는 작업 전체에서 고유하게 저장됩니다. |
| referrer | **int32_t** | 참조하는 객체의 ID 또는 0(객체가 루트 문서에 의해 참조되는 경우). 상대 링크를 생성하는데 사용될 수 있습니다. |

### 반환값

외부 객체의 URL 또는 이 객체를 무시해야 하는 경우 null.

## 관련 항목

* 클래스 [String](../../../system/string/)
* 클래스 [ILinkEmbedController](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)