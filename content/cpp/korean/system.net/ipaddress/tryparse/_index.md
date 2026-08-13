---
title: TryParse()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 전달된 문자열을 IPAddress 클래스의 인스턴스로 변환하려 시도합니다.
type: docs
weight: 222
url: /ko/system.net/ipaddress/tryparse/
---
## IPAddress::TryParse(String, System::SharedPtr\<IPAddress\>\&) 메서드

전달된 문자열을 [IPAddress](../) 클래스의 인스턴스로 변환하려 시도합니다.

```cpp
static bool System::Net::IPAddress::TryParse(String ipString, System::SharedPtr<IPAddress> &address)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ipString | [String](../../../system/string/) | 분석할 문자열. |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../)\>\& | 분석된 객체가 할당될 인스턴스. |

### 반환값

구문 분석이 성공적으로 완료되면 true, 그렇지 않으면 false.

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [IPAddress](../)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)