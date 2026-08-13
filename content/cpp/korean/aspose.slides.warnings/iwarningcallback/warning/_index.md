---
title: Warning()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 경고를 수신하고 작업을 중단해야 하는지 결정하는 콜백 메서드.
type: docs
weight: 1
url: /ko/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning(System::SharedPtr\<IWarningInfo\>) 메서드

경고를 수신하고 작업을 중단해야 하는지 결정하는 콜백 메서드.

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | 처리할 경고. |

### 반환 값

중단 결정 [ReturnAction](../../returnaction/).

## 참조

* Enum [ReturnAction](../../returnaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWarningInfo](../../iwarninginfo/)
* Class [IWarningCallback](../)
* Namespace [Aspose::Slides::Warnings](../../)
* Library [Aspose.Slides](../../../)