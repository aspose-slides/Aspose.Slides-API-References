---
title: Read()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 스트림에서 단일 문자를 읽습니다.
type: docs
weight: 40
url: /ko/system.io/textreader/read/
---
## TextReader::Read() 메서드


스트림에서 단일 문자를 읽습니다.

```cpp
virtual int System::IO::TextReader::Read()
```


### 반환 값

UTF-16 인코딩으로 인코딩된 문자를 읽습니다; 읽은 문자가 UTF-16 인코딩에서 두 개의 코드포인트로 표현되는 경우 높은 서러게이트만 반환됩니다.

## TextReader::Read(ArrayPtr\<char_t\>, int, int) 메서드


스트림에서 지정된 수의 문자를 읽고, 지정된 위치에서 시작하는 지정된 문자 배열에 씁니다.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```


### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 스트림에서 읽은 문자를 기록할 UTF-16 문자 배열 |
| index | int | **buffer**에서 쓰기를 시작할 0 기반 인덱스 |
| count | int | 스트림에서 읽을 문자 수 |

### 반환 값

스트림에서 읽은 문자 수

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [TextReader](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)