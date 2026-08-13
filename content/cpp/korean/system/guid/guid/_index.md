---
title: Guid()
second_title: Aspose.Slides for C++ API 참조
description: 모든 비트가 0인 GUID를 나타내는 객체를 생성합니다.
type: docs
weight: 1
url: /ko/system/guid/guid/
---
## Guid::Guid() 생성자

모든 비트가 0인 GUID를 나타내는 객체를 생성합니다.

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) 생성자

부호 없는 8비트 정수값 배열로 지정된 GUID를 나타내는 객체를 생성합니다.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | GUID의 개별 바이트를 포함하는 바이트 배열 |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) 생성자

부호 없는 8비트 정수값 배열 뷰로 지정된 GUID를 나타내는 객체를 생성합니다.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | GUID의 개별 바이트를 포함하는 바이트 배열 |

## Guid::Guid(const String\&) 생성자

문자열로 지정된 GUID를 나타내는 객체를 생성합니다.

```cpp
System::Guid::Guid(const String &g)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| g | const [String](../../string/)\& | 생성되는 객체가 나타낼 GUID의 문자열 표현 |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) 생성자

지정된 GUID 구성 요소로부터 [Guid](../) 클래스를 인스턴스화합니다.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | **int32_t** | GUID의 비트 0-31 |
| b | **int16_t** | GUID의 비트 32-47 |
| c | **int16_t** | GUID의 비트 48-63 |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | GUID의 비트 64-127을 포함하는 바이트 배열 |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) 생성자

지정된 GUID 구성 요소로부터 [Guid](../) 클래스를 인스턴스화합니다.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | **int32_t** | GUID의 비트 0-31 |
| b | **int16_t** | GUID의 비트 32-47 |
| c | **int16_t** | GUID의 비트 48-63 |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | GUID의 비트 64-127을 포함하는 바이트 배열 뷰 |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) 생성자

지정된 부호 없는 정수와 바이트로부터 [Guid](../) 클래스를 인스턴스화합니다.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | **int32_t** | GUID의 비트 0-31 |
| b | **int16_t** | GUID의 비트 32-47 |
| c | **int16_t** | GUID의 비트 48-63 |
| d | **uint8_t** | GUID의 비트 64-71 |
| e | **uint8_t** | GUID의 비트 72-79 |
| f | **uint8_t** | GUID의 비트 80-87 |
| g | **uint8_t** | GUID의 비트 88-95 |
| h | **uint8_t** | GUID의 비트 96-103 |
| i | **uint8_t** | GUID의 비트 104-111 |
| j | **uint8_t** | GUID의 비트 112-119 |
| k | **uint8_t** | GUID의 비트 120-127 |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) 생성자

지정된 부호 없는 정수와 바이트로부터 [Guid](../) 클래스를 인스턴스화합니다.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | **uint32_t** | GUID의 비트 0-31 |
| b | **uint16_t** | GUID의 비트 32-47 |
| c | **uint16_t** | GUID의 비트 48-63 |
| d | **uint8_t** | GUID의 비트 64-71 |
| e | **uint8_t** | GUID의 비트 72-79 |
| f | **uint8_t** | GUID의 비트 80-87 |
| g | **uint8_t** | GUID의 비트 88-95 |
| h | **uint8_t** | GUID의 비트 96-103 |
| i | **uint8_t** | GUID의 비트 104-111 |
| j | **uint8_t** | GUID의 비트 112-119 |
| k | **uint8_t** | GUID의 비트 120-127 |

## Guid::Guid(const Guid\&) 생성자

지정된 객체와 동일한 GUID를 나타내는 객체를 생성합니다.

```cpp
System::Guid::Guid(const Guid &guid)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| guid | const [Guid](../)\& | [Guid](../) 객체에서 GUID 값을 복사합니다 |

## 참고

* Typedef [ArrayPtr](../../arrayptr/)
* 클래스 [Guid](../)
* 클래스 [String](../../string/)
* 네임스페이스 [System](../../)
* Library [Aspose.Slides](../../../)