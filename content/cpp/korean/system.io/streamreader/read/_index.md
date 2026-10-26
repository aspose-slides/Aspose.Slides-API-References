---
title: Read()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 스트림에서 단일 문자를 읽습니다.
type: docs
weight: 40
url: /ko/system.io/streamreader/read/
---
## StreamReader::Read() 메서드


스트림에서 단일 문자를 읽습니다.

```cpp
virtual int System::IO::StreamReader::Read() override
```


### 반환값

UTF-16 인코딩으로 인코딩된 문자를 읽습니다; 읽은 문자가 UTF-16 인코딩에서 두 개의 코드 포인트로 표현되는 경우 상위 서러게이트만 반환됩니다.

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) 메서드


스트림에서 지정된 수의 문자를 읽고, 이를 UTF-16 인코딩으로 변환한 뒤, 지정된 위치부터 시작하는 지정된 문자 배열에 결과 UTF-16 문자를 씁니다.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 스트림에서 읽은 문자를 기록할 UTF-16 문자 배열 |
| index | int | 쓰기를 시작할 **buffer**의 0 기반 인덱스 |
| count | int | 스트림에서 읽을 문자 수 |

### 반환값

스트림에서 읽은 문자 수

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [StreamReader](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)