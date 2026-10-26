---
title: Read()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 입력 스트림에서 단일 문자를 읽습니다.
type: docs
weight: 66
url: /ko/system.io/binaryreader/read/
---
## BinaryReader::Read() 메서드


입력 스트림에서 단일 문자를 읽습니다.

```cpp
virtual int System::IO::BinaryReader::Read()
```


### 반환값

UTF-16 인코딩으로 인코딩된 문자를 반환합니다; 읽은 문자가 UTF-16 인코딩에서 두 개의 코드포인트로 표현되는 경우 고위 서러게이트만 반환됩니다.

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) 메서드


입력 스트림에서 지정된 바이트 수를 읽어 지정된 바이트 배열에 기록합니다.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 읽은 바이트를 기록할 바이트 배열 |
| index | int | 0 기반 위치로 **buffer**에 기록을 시작하는 위치 |
| count | int | 읽을 바이트 수 |

### 반환값

읽은 바이트 수

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) 메서드


입력 스트림에서 지정된 문자 수를 읽어 UTF-16 인코딩으로 변환하고, 결과 UTF-16 문자를 지정된 위치에서 시작하는 지정된 문자 배열에 기록합니다.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 입력 스트림에서 읽은 문자를 기록할 UTF-16 문자 배열 |
| index | int | 0 기반 인덱스로 **buffer**에 기록을 시작하는 위치 |
| count | int | 스트림에서 읽을 문자 수 |

### 반환값

입력 스트림에서 읽은 문자 수

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [BinaryReader](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)