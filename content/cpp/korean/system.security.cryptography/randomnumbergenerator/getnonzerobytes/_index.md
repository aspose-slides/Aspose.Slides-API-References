---
title: GetNonZeroBytes()
second_title: Aspose.Slides for C++ API 참조
description: 기존 배열 요소를 무작위 비영(0이 아닌) 바이트로 채웁니다.
type: docs
weight: 27
url: /ko/system.security.cryptography/randomnumbergenerator/getnonzerobytes/
---
## RandomNumberGenerator::GetNonZeroBytes(ArrayPtr\<uint8_t\>) 메서드

기존 배열 요소를 무작위 비영(0이 아닌) 바이트로 채웁니다.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetNonZeroBytes(ArrayPtr<uint8_t> bytes)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 채울 바이트 배열입니다. |

## RandomNumberGenerator::GetNonZeroBytes(System::Details::ArrayView\<uint8_t\>) 메서드

기존 배열 뷰 요소를 무작위 비영(0이 아닌) 바이트로 채웁니다.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetNonZeroBytes(System::Details::ArrayView<uint8_t> bytes)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | 채울 바이트 배열 뷰입니다. |

## RandomNumberGenerator::GetNonZeroBytes(System::Details::StackArray\<uint8_t, N\>\&) 메서드

기존 스택 배열 요소를 무작위 비영(0이 아닌) 바이트로 채웁니다.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetNonZeroBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | 채울 바이트 스택 배열입니다. |

## 참고

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [RandomNumberGenerator](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)