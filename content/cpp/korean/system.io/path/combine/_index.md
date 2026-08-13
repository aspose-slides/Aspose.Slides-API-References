---
title: Combine()
second_title: Aspose.Slides for C++ API 참조
description: 필요에 따라 세그먼트 사이에 디렉터리 구분자를 삽입하여 지정된 경로 세그먼트를 하나의 경로로 결합합니다.
type: docs
weight: 14
url: /ko/system.io/path/combine/
---
## Path::Combine(const ArrayPtr\<String\>\&) 메서드

지정된 경로 세그먼트를 하나의 경로로 결합하며, 필요한 경우 세그먼트 사이에 디렉터리 구분자를 삽입합니다.

```cpp
static String System::IO::Path::Combine(const ArrayPtr<String> &paths)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| paths | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | 결합할 경로 세그먼트를 포함하는 배열 |

### 반환 값

결합된 경로

## Path::Combine(const String\&, const String\&) 메서드

두 개의 지정된 경로 세그먼트를 하나의 경로로 결합하며, 필요한 경우 세그먼트 사이에 디렉터리 구분자를 삽입합니다.

```cpp
static String System::IO::Path::Combine(const String &path1, const String &path2)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path1 | const [String](../../../system/string/)\& | 첫 번째 경로 세그먼트 |
| path2 | const [String](../../../system/string/)\& | 두 번째 경로 세그먼트 |

### 반환 값

결합된 경로

## Path::Combine(const String\&, const String\&, const String\&) 메서드

세 개의 지정된 경로 세그먼트를 하나의 경로로 결합하며, 필요한 경우 세그먼트 사이에 디렉터리 구분자를 삽입합니다.

```cpp
static String System::IO::Path::Combine(const String &path1, const String &path2, const String &path3)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path1 | const [String](../../../system/string/)\& | 첫 번째 경로 세그먼트 |
| path2 | const [String](../../../system/string/)\& | 두 번째 경로 세그먼트 |
| path3 | const [String](../../../system/string/)\& | 세 번째 경로 세그먼트 |

### 반환 값

결합된 경로

## Path::Combine(const String\&, const String\&, const String\&, const String\&) 메서드

네 개의 지정된 경로 세그먼트를 하나의 경로로 결합하며, 필요한 경우 세그먼트 사이에 디렉터리 구분자를 삽입합니다.

```cpp
static String System::IO::Path::Combine(const String &path1, const String &path2, const String &path3, const String &path4)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path1 | const [String](../../../system/string/)\& | 첫 번째 경로 세그먼트 |
| path2 | const [String](../../../system/string/)\& | 두 번째 경로 세그먼트 |
| path3 | const [String](../../../system/string/)\& | 세 번째 경로 세그먼트 |
| path4 | const [String](../../../system/string/)\& | 네 번째 경로 세그먼트 |

### 반환 값

결합된 경로

## 참고

* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [Path](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)