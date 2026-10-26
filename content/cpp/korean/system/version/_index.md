---
title: Version
second_title: Aspose.Slides for C++ API 레퍼런스
description: "버전 번호를 나타냅니다. 이 타입은 스택에 할당하고 값이나 참조로 함수에 전달해야 합니다. 이 타입의 객체를 관리하려면 System::SmartPtr 클래스를 사용하지 마십시오."
type: docs
weight: 1470
url: /ko/system/version/
---
## Version 클래스

버전 번호를 나타냅니다. 이 타입은 스택에 할당하고 값이나 참조로 함수에 전달해야 합니다. [System::SmartPtr](../smartptr/) 클래스를 사용하여 이 타입의 객체를 관리하지 마십시오.

```cpp
class Version
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | 현재 객체와 지정된 객체가 나타내는 버전을 비교합니다. |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | 현재 객체와 지정된 객체가 나타내는 버전 번호가 같은지 여부를 결정합니다. |
| int [get_Build](./get_build/)() const | 빌드 번호를 반환합니다. |
| int [get_Major](./get_major/)() const | 주 버전을 반환합니다. |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | 리비전 번호의 상위 16비트 값을 반환합니다. |
| int [get_Minor](./get_minor/)() const | 부 버전을 반환합니다. |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | 리비전 번호의 하위 16비트 값을 반환합니다. |
| int [get_Revision](./get_revision/)() const | 리비전 번호를 반환합니다. |
| int [GetHashCode](./gethashcode/)() const | 현재 객체에 대한 해시 코드를 반환합니다. |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | 버전 번호의 문자열 표현을 [Version](./) 클래스의 동등한 인스턴스로 변환합니다. |
| [String](../string/) [ToString](./tostring/)() const | 현재 객체가 나타내는 버전 번호의 문자열 표현을 반환합니다. |
| [String](../string/) [ToString](./tostring/)(int) const | 현재 객체가 나타내는 버전 번호의 지정된 섹션 수에 대한 문자열 표현을 반환합니다. |
| [Version](./version/)(int, int, int, int) | 지정된 주, 부, 빌드 및 리비전 값을 나타내는 인스턴스를 생성합니다. |
| [Version](./version/)(int, int, int) | 지정된 주, 부 및 빌드 값을 나타내는 인스턴스를 생성합니다. |
| [Version](./version/)(int, int) | 지정된 주와 값을 나타내는 인스턴스를 생성합니다. |
| [Version](./version/)(const [String](../string/)\&) | 문자열로 표현된 버전 번호를 나타내는 인스턴스를 생성합니다. |
| [Version](./version/)() | 버전 번호 0.0.-1.-1을 나타내는 인스턴스를 생성합니다. |

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)