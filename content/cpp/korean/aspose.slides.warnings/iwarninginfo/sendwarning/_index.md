---
title: SendWarning()
second_title: Aspose.Slides for C++ API 레퍼런스
description: receiver가 null이 아니면 지정된 수신자에게 경고를 종료하고, 수신자가 작업을 중단하기로 결정하면 AbortRequestedException을 발생시킵니다.
type: docs
weight: 27
url: /ko/aspose.slides.warnings/iwarninginfo/sendwarning/
---
## IWarningInfo::SendWarning(System::SharedPtr\<IWarningCallback\>) 메서드

receiver가 null이 아니면 지정된 수신자에게 경고를 종료하고, 수신자가 작업을 중단하기로 결정하면 AbortRequestedException을 발생시킵니다.

```cpp
virtual void Aspose::Slides::Warnings::IWarningInfo::SendWarning(System::SharedPtr<IWarningCallback> receiver)=0
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| receiver | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningCallback](../../iwarningcallback/)\> | 수신자 객체 [IWarningCallback](../../iwarningcallback/) |

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IWarningCallback](../../iwarningcallback/)
* 클래스 [IWarningInfo](../)
* 네임스페이스 [Aspose::Slides::Warnings](../../)
* 라이브러리 [Aspose.Slides](../../../)