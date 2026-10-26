---
title: VerifySetDefaults()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 기본 속성 값을 확인하고 설정합니다.
type: docs
weight: 482
url: /ko/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) 메서드


기본 속성 값을 확인하고 설정합니다.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | 쿠키의 사양. |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 내부 필드를 초기화하는 데 사용되는 Uri 클래스 인스턴스. |
| isLocalDomain | **bool** | 쿠키가 로컬 도메인에 푸시되는지 여부를 나타내는 값. |
| localDomain | [String](../../../system/string/) | 로컬 도메인 이름. |
| setDefault | **bool** | 쿠키 속성을 기본값으로 초기화해야 하는지 여부를 나타내는 값. |
| shouldThrow | **bool** | 지정된 값이 유효하지 않을 때 예외를 발생시켜야 하는지 여부를 나타내는 값. |

### 반환 값

모든 값이 유효하면 true, 그렇지 않으면 false.

## 참고

* Enum [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [Cookie](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)