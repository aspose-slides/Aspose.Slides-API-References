---
title: Read()
second_title: Aspose.Slides for C++ API 참조
description: 스트림에서 단일 문자를 읽습니다.
type: docs
weight: 40
url: /ko/system.io/stringreader/read/
---
## StringReader::Read() 메서드

스트림에서 단일 문자를 읽습니다.

```cpp
virtual int System::IO::StringReader::Read() override
```

### 반환값

읽은 문자이며, 문자를 읽지 못한 경우 -1을 반환합니다.

## StringReader::Read(ArrayPtr\<char_t\>, int, int) 메서드

지정된 위치에서 시작하여 지정된 문자 배열에 스트림으로부터 지정된 개수의 문자를 읽습니다.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 스트림에서 읽은 문자를 기록할 문자 배열 |
| index | int | **buffer**에 쓰기 시작하는 0 기반 인덱스 |
| count | int | 스트림에서 읽을 문자 수 |

### 반환값

스트림에서 읽은 문자 수

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)