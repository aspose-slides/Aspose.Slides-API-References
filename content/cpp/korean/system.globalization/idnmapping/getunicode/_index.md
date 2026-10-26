---
title: GetUnicode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: ASCII 도메인 이름을 유니코드 등가 문자열로 변환합니다.
type: docs
weight: 92
url: /ko/system.globalization/idnmapping/getunicode/
---
## IdnMapping::GetUnicode(const String\&) const 메서드


[Convert](../../../system/convert/) ASCII 도메인 이름을 유니코드 등가 문자열로 변환합니다.

```cpp
String System::Globalization::IdnMapping::GetUnicode(const String &ascii) const
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ascii | const [String](../../../system/string/)\& | [String](../../../system/string/) 변환할 문자열. |

### 반환값

ASCII 문자열의 유니코드 등가 문자열.

## IdnMapping::GetUnicode(const String\&, int) const 메서드


[Convert](../../../system/convert/) ASCII 도메인 이름을 유니코드 등가 문자열로 변환합니다.

```cpp
String System::Globalization::IdnMapping::GetUnicode(const String &ascii, int index) const
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ascii | const [String](../../../system/string/)\& | [String](../../../system/string/) 변환할 문자열. |
| index | int | 변환할 하위 문자열의 시작 인덱스 |
 
### 반환값

ASCII 문자열의 유니코드 등가 문자열.

## IdnMapping::GetUnicode(const String\&, int, int) const 메서드


[Convert](../../../system/convert/) ASCII 도메인 이름을 유니코드 등가 문자열로 변환합니다.

```cpp
String System::Globalization::IdnMapping::GetUnicode(const String &ascii, int index, int count) const
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ascii | const [String](../../../system/string/)\& | [String](../../../system/string/) 변환할 문자열. |
| index | int | 변환할 하위 문자열의 시작 인덱스 |
| count | int | 변환할 문자 수. |

### 반환값

ASCII 문자열의 유니코드 등가 문자열.

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [IdnMapping](../)
* 네임스페이스 [System::Globalization](../../)
* 라이브러리 [Aspose.Slides](../../../)