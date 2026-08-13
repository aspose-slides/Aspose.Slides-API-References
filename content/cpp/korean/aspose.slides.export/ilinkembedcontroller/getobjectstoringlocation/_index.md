---
title: GetObjectStoringLocation()
second_title: Aspose.Slides for C++ API 참조
description: 객체가 저장될 위치를 결정합니다. 이 메서드는 각 객체 ID마다 한 번 호출됩니다. 동일한 데이터, semanticName 및 contentType을 갖지만 ID가 다른 두 객체가 존재하지 않을 것이라는 보장은 없습니다.
type: docs
weight: 1
url: /ko/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) 메서드


객체가 저장될 위치를 결정합니다. 이 메서드는 각 객체 ID마다 한 번 호출됩니다. 동일한 데이터, semanticName 및 contentType을 갖지만 ID가 다른 두 객체가 존재할 수 있다는 보장은 없습니다.

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| id | **int32_t** | 객체 ID. 이 ID는 저장 작업 전체에서 고유합니다. |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 객체 바이너리 데이터. 객체 바이너리 데이터가 아직 생성되지 않은 경우 이 매개변수는 null일 수 있습니다. |
| semanticName | [System::String](../../../system/string/) | 객체의 의미를 설명하는 짧은 텍스트입니다. Controller는 이를 외부 객체 이름의 일부로 사용할 수 있지만, 이름이 고유하고 허용된 문자만 포함하도록 보장하는 것은 dispatcher의 책임입니다. |
| contentType | [System::String](../../../system/string/) | 객체의 MIME 유형. |
| recomendedExtension | [System::String](../../../system/string/) | 이 MIME 유형에 권장되는 파일 이름 확장자. |

### 반환값

결정

## 참고

* 열거형 [LinkEmbedDecision](../../linkembeddecision/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [ILinkEmbedController](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)