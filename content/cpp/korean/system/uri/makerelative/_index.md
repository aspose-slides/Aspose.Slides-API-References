---
title: MakeRelative()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 두 Uri 인스턴스 간의 차이를 결정합니다.
type: docs
weight: 365
url: /ko/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) 메서드

두 개의 [Uri](../) 인스턴스 간의 차이를 결정합니다.

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 현재 URI와 비교할 URI |

### 반환 값

현재 객체와 **toUri**가 나타내는 URI의 호스트 이름과 스킴이 동일한 경우, 이 메서드는 현재 URI 인스턴스에 추가되었을 때 **toUri**가 되는 상대 [Uri](../)을 나타내는 [String](../../string/)를 반환합니다. 호스트 이름이나 스킴이 다른 경우, 이 메서드는 **uri** 매개변수를 나타내는 [String](../../string/)를 반환합니다.

## 참조

* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [Uri](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)