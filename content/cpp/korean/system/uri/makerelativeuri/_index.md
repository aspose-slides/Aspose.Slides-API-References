---
title: MakeRelativeUri()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체와 지정된 Uri 객체가 나타내는 URI 간의 차이를 결정합니다.
type: docs
weight: 352
url: /ko/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) 메서드

현재 객체와 지정된 [Uri](../) 객체가 나타내는 URI 간의 차이를 결정합니다.

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 비교 대상 |

### 반환 값

현재 객체와 **toUri**가 나타내는 URI의 호스트 이름과 스킴이 동일하면, 이 메서드는 현재 URI 인스턴스에 추가될 때 **toUri**를 만드는 상대 [Uri](../)를 반환합니다. 호스트 이름이나 스킴이 다르면, 이 메서드는 **uri** 매개변수를 나타내는 [Uri](../) 객체를 반환합니다.

## 관련 항목

* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [Uri](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)