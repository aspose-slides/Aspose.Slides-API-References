---
title: Write()
second_title: Aspose.Slides C++ API 레퍼런스
description: 지정된 문자를 스트림에 씁니다.
type: docs
weight: 40
url: /ko/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) 메서드

지정된 문자를 스트림에 씁니다.

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | char_t | 쓰기 위한 값 |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) 메서드

지정된 문자 배열에서 지정된 문자 부분 범위를 스트림에 씁니다.

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 쓰기를 위한 문자를 포함하는 배열 |
| index | **int32_t** | 쓰기 부분 범위가 시작되는 **buffer** 안의 0 기반 인덱스 |
| count | **int32_t** | 쓰기 부분 범위에 포함된 문자 수 |

## StringWriter::Write(const String\&) 메서드

지정된 문자열을 스트림에 씁니다.

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 쓰기 위한 문자열 |

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [StringWriter](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::IO](../../)
* Library [Aspose.Slides](../../../)