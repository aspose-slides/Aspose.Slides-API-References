---
title: GetBytes()
second_title: C++용 Aspose.Slides API 참조
description: 기존 배열 요소를 무작위 바이트로 채웁니다.
type: docs
weight: 14
url: /ko/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) 메서드

기존 배열 요소를 무작위 바이트로 채웁니다.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 채울 바이트 배열. |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) 메서드

기존 배열 슬라이스를 무작위 바이트로 채웁니다.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 슬라이스를 채울 바이트 배열. |
| offset | int | 슬라이스 시작 인덱스. |
| count | int | 슬라이스 크기. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) 메서드

기존 배열 뷰 요소를 무작위 바이트로 채웁니다.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | 채울 바이트 배열 뷰. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) 메서드

기존 배열 뷰 슬라이스를 무작위 바이트로 채웁니다.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | 슬라이스를 채울 바이트 배열 뷰. |
| offset | int | 슬라이스 시작 인덱스. |
| count | int | 슬라이스 크기. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) 메서드

기존 스택 배열 요소를 무작위 바이트로 채웁니다.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | 채울 바이트 스택 배열. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) 메서드

기존 스택 배열 슬라이스를 무작위 바이트로 채웁니다.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | 슬라이스를 채울 바이트 스택 배열. |
| offset | int | 슬라이스 시작 인덱스. |
| count | int | 슬라이스 크기. |

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [RandomNumberGenerator](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)