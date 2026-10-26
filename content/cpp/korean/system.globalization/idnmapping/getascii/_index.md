---
title: GetAscii()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Unicode 도메인 이름을 ASCII 등가 문자열로 변환합니다.
type: docs
weight: 79
url: /ko/system.globalization/idnmapping/getascii/
---
## IdnMapping::GetAscii(const String\&) const 메서드


[Convert](../../../system/convert/) unicode 도메인 이름을 ascii 등가 문자열로 변환합니다.

```cpp
String System::Globalization::IdnMapping::GetAscii(const String &unicode) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| unicode | const [String](../../../system/string/)\& | [String](../../../system/string/) 변환할. |

### 반환 값

unicode 문자열의 ascii 등가 문자열.

## IdnMapping::GetAscii(const String\&, int) const 메서드


[Convert](../../../system/convert/) unicode 도메인 이름을 ascii 등가 문자열로 변환합니다.

```cpp
String System::Globalization::IdnMapping::GetAscii(const String &unicode, int index) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| unicode | const [String](../../../system/string/)\& | [String](../../../system/string/) 변환할. |
| index | int | 변환할 부분 문자열의 시작 인덱스 |

### 반환 값

unicode 문자열의 ascii 등가 문자열.

## IdnMapping::GetAscii(const String\&, int, int) const 메서드


[Convert](../../../system/convert/) unicode 도메인 이름을 ascii 등가 문자열로 변환합니다.

```cpp
String System::Globalization::IdnMapping::GetAscii(const String &unicode, int index, int count) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| unicode | const [String](../../../system/string/)\& | [String](../../../system/string/) 변환할. |
| index | int | 변환할 부분 문자열의 시작 인덱스 |
| count | int | 변환할 문자 수. |

### 반환 값

unicode 문자열의 ascii 등가 문자열.

## 관련 항목

* 클래스 [String](../../../system/string/)
* 클래스 [IdnMapping](../)
* 네임스페이스 [System::Globalization](../../)
* 라이브러리 [Aspose.Slides](../../../)