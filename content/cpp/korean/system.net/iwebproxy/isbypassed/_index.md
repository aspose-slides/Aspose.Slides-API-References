---
title: IsBypassed()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 호스트에 대해 프록시를 사용하면 안 되는지를 나타내는 값을 반환합니다.
type: docs
weight: 40
url: /ko/system.net/iwebproxy/isbypassed/
---
## IWebProxy::IsBypassed(System::SharedPtr\<Uri\>) 메서드


지정된 호스트에 대해 프록시를 사용하면 안 되는지를 나타내는 값을 반환합니다.

```cpp
virtual bool System::Net::IWebProxy::IsBypassed(System::SharedPtr<Uri> host)=0
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| host | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 확인할 호스트 URI. |

### 반환 값

프록시 서버를 사용하면 안 될 경우 True, 그렇지 않으면 false.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Uri](../../../system/uri/)
* 클래스 [IWebProxy](../)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)