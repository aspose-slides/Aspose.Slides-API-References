---
title: Uri()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 URI를 나타내는 Uri 객체를 생성합니다.
type: docs
weight: 287
url: /ko/system/uri/uri/
---
## Uri::Uri(const String\&) 생성자

지정된 URI를 나타내는 [Uri](../) 객체를 생성합니다.

```cpp
System::Uri::Uri(const String &uriString)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | 구성 중인 객체가 나타내는 문자열 URI |
|  |  |  |

## Uri::Uri(const String\&, bool) 생성자

지정된 URI를 나타내는 [Uri](../) 객체를 생성합니다; 인수는 URI를 이스케이프할지 여부를 지정합니다.

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | 구성 중인 객체가 나타내는 문자열 URI |
| dontEscape | **bool** | URI를 이스케이프하지 않아야 하는지 여부를 지정합니다 |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) 생성자

지정된 [Uri](../) 객체(기본 URI를 나타냄)와 상대 URI의 문자열 표현으로부터 [Uri](../) 객체를 생성합니다; 인수는 URI를 이스케이프할지 여부를 지정합니다.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 기본 URI |
| relativeUri | const [String](../../string/)\& | 기본 URI에 추가되는 상대 URI |
| dontEscape | **bool** | URI를 이스케이프하지 않아야 하는지 여부를 지정합니다 |

## Uri::Uri(const String\&, UriKind) 생성자

지정된 URI를 나타내는 [Uri](../) 객체를 생성합니다; 인수는 URI 종류를 지정합니다.

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | 구성 중인 객체가 나타내는 문자열 URI |
| uriKind | [UriKind](../../urikind/) | URI 종류를 지정합니다 |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) 생성자

지정된 기본 및 상대 URI로부터 [Uri](../) 객체를 생성합니다.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 기본 URI |
| relativeUri | const [String](../../string/)\& | 기본 URI에 추가되는 상대 URI |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) 생성자

지정된 기본 및 상대 URI로부터 [Uri](../) 객체를 생성합니다.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 기본 URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 기본 URI에 추가되는 상대 URI |

## 참고

* 열거형 [UriKind](../../urikind/)
* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [Uri](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)