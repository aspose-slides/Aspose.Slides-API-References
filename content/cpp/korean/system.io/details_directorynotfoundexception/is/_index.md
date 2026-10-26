---
title: Is()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 
type: docs
weight: 27
url: /ko/system.io/details_directorynotfoundexception/is/
---
## Details_DirectoryNotFoundException::Is(const System::TypeInfo\&) const 메서드

```cpp
bool System::IO::Details_DirectoryNotFoundException::Is(const System::TypeInfo &target) const override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 구조는 현재 객체를 테스트할 대상 유형을 설명합니다. |

### 반환 값

객체가 지정된 타입 또는 그 하위 클래스인 경우 true, 그렇지 않으면 false.

## 비고

객체가 targetType이 설명하는 유형의 인스턴스인지 확인합니다. C#의 'is' 연산자와 유사합니다.

## 참고

* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [Details_DirectoryNotFoundException](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)