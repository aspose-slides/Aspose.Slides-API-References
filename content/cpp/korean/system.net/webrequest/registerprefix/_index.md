---
title: RegisterPrefix()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 URI에 대한 WebRequest 하위 항목을 등록합니다.
type: docs
weight: 92
url: /ko/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) 메서드


지정된 URI에 [WebRequest](../) 하위 항목을 등록합니다.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | URI 또는 URI 접두사입니다. |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | 새 [WebRequest](../) 클래스 인스턴스를 생성합니다. |

### 반환 값

지정된 URI에 대해 [WebRequest](../) 하위 항목이 성공적으로 등록되면 true, 그렇지 않으면 false.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [IWebRequestCreate](../../iwebrequestcreate/)
* 클래스 [WebRequest](../)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)