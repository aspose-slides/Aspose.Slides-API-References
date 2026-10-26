---
title: TryCreate()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 URI를 나타내는 Uri 객체를 생성합니다; 인수가 URI 유형을 지정합니다.
type: docs
weight: 508
url: /ko/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) method

지정된 URI를 나타내는 [Uri](../) 객체를 생성합니다; 인수가 URI 유형을 지정합니다.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | 구축되는 객체가 나타낼 문자열 URI |
| uriKind | [UriKind](../../urikind/) | URI 유형을 지정합니다 |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 구성이 성공하면 메서드 반환 시 새로 생성된 [Uri](../) 객체를 가리키는 출력 인수 |

### 반환 값

구성이 성공하면 true, 그렇지 않으면 false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) method

지정된 [Uri](../) 객체(기본 URI를 나타냄)와 상대 URI의 문자열 표현을 사용하여 [Uri](../) 객체를 생성합니다.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 기본 URI |
| relativeUri | const [String](../../string/)\& | 기본 URI에 추가되는 상대 URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 구성이 성공하면 메서드 반환 시 새로 생성된 [Uri](../) 객체를 가리키는 출력 인수 |

### 반환 값

구성이 성공하면 true, 그렇지 않으면 false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) method

지정된 기본 및 상대 URI를 사용하여 [Uri](../) 객체를 생성합니다.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 기본 URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 기본 URI에 추가되는 상대 URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 구성이 성공하면 메서드 반환 시 새로 생성된 [Uri](../) 객체를 가리키는 출력 인수 |

### 반환 값

구성이 성공하면 true, 그렇지 않으면 false

## 참고

* 열거형 [UriKind](../../urikind/)
* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [Uri](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)