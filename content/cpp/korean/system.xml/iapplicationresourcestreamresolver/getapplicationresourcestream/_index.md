---
title: GetApplicationResourceStream()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 URI에서 애플리케이션 리소스 스트림을 반환합니다.
type: docs
weight: 1
url: /ko/system.xml/iapplicationresourcestreamresolver/getapplicationresourcestream/
---
## IApplicationResourceStreamResolver::GetApplicationResourceStream(SharedPtr\<Uri\>) 메서드

지정된 URI에서 애플리케이션 리소스 스트림을 반환합니다.

```cpp
virtual SharedPtr<IO::Stream> System::Xml::IApplicationResourceStreamResolver::GetApplicationResourceStream(SharedPtr<Uri> relativeUri)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| relativeUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 상대 URI. |

### 반환 값

애플리케이션 리소스 스트림.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [Uri](../../../system/uri/)
* 클래스 [IApplicationResourceStreamResolver](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)