---
title: Version()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 major, minor, build 및 revsion 값을 나타내는 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system/version/version/
---
## Version::Version(int, int, int, int) 생성자

지정된 major, minor, build 및 revsion 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::Version::Version(int major, int minor, int build, int revision)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| major | int | 주 버전 번호 |
| minor | int | 보조 버전 번호 |
| build | int | build 번호 |
| revision | int | revision 번호 |

## Version::Version(int, int, int) 생성자

지정된 major, minor 및 build 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::Version::Version(int major, int minor, int build)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| major | int | 주 버전 번호 |
| minor | int | 보조 버전 번호 |
| build | int | build 번호 |

## Version::Version(int, int) 생성자

지정된 major 및 값을 나타내는 인스턴스를 생성합니다.

```cpp
System::Version::Version(int major, int minor)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| major | int | 주 버전 번호 |
| minor | int | 보조 버전 번호 |

## Version::Version(const String\&) 생성자

문자열로 표현된 version 번호를 나타내는 인스턴스를 생성합니다.

```cpp
System::Version::Version(const String &version)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| version | const [String](../../string/)\& | version 번호를 포함하는 문자열 |

## Version::Version() 생성자

version 번호 0.0.-1.-1을 나타내는 인스턴스를 생성합니다.

```cpp
System::Version::Version()
```

## 참조

* 클래스 [Version](../)
* 클래스 [String](../../string/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)