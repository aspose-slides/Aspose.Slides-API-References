---
title: Write()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 지정된 부호 없는 8비트 정수 값을 출력 스트림에 씁니다.
type: docs
weight: 92
url: /ko/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) 메서드


지정된 부호 없는 8비트 정수 값을 출력 스트림에 씁니다.

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **uint8_t** | 작성할 값 |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) 메서드


지정된 바이트 배열에서 지정된 바이트 서브범위를 출력 스트림에 씁니다.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 쓰기 위한 바이트를 포함하는 배열 |
| index | int | 쓰기 서브범위가 시작되는 **buffer** 내의 0 기반 인덱스 |
| count | int | 쓰기 서브범위의 요소 수; -1은 서브범위가 **buffer** 배열의 끝까지 이어짐을 의미합니다 |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) 메서드


지정된 문자 배열에서 지정된 UTF-16 문자 서브범위를 출력 스트림에 씁니다.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 쓰기 위한 문자를 포함하는 배열 |
| index | int | 쓰기 서브범위가 시작되는 **buffer** 내의 0 기반 인덱스 |
| count | int | 쓰기 서브범위의 문자 수; -1은 서브범위가 **buffer** 배열의 끝까지 이어짐을 의미합니다 |

## BinaryWriter::Write(bool) 메서드


**value**가 true이면 값이 0이고, false이면 값이 1인 단일 바이트를 출력 스트림에 씁니다.

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **bool** | 출력 스트림에 쓸 바이트 값을 지정하는 부울 값 |

## BinaryWriter::Write(char16_t) 메서드


지정된 16비트 문자 값을 출력 스트림에 씁니다.

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | char16_t | 쓰기 위한 값 |

## BinaryWriter::Write(int16_t) 메서드


지정된 16비트 정수 값을 출력 스트림에 씁니다.

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **int16_t** | 쓰기 위한 값 |

## BinaryWriter::Write(int) 메서드


지정된 32비트 정수 값을 출력 스트림에 씁니다.

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int | 쓰기 위한 값 |

## BinaryWriter::Write(int64_t) 메서드


지정된 64비트 정수 값을 출력 스트림에 씁니다.

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **int64_t** | 쓰기 위한 값 |

## BinaryWriter::Write(uint16_t) 메서드


지정된 부호 없는 16비트 정수 값을 출력 스트림에 씁니다.

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **uint16_t** | 쓰기 위한 값 |

## BinaryWriter::Write(uint32_t) 메서드


지정된 부호 없는 32비트 정수 값을 출력 스트림에 씁니다.

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **uint32_t** | 쓰기 위한 값 |

## BinaryWriter::Write(uint64_t) 메서드


지정된 부호 없는 64비트 정수 값을 출력 스트림에 씁니다.

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **uint64_t** | 쓰기 위한 값 |

## BinaryWriter::Write(float) 메서드


지정된 단정밀도 부동소수점 값을 출력 스트림에 씁니다.

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **float** | 쓰기 위한 값 |

## BinaryWriter::Write(double) 메서드


지정된 배정밀도 부동소수점 값을 출력 스트림에 씁니다.

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **double** | 쓰기 위한 값 |

## BinaryWriter::Write(const Decimal\&) 메서드


지정된 [Decimal](../../../system/decimal/) 값의 바이트 표현을 출력 스트림에 씁니다.

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | 쓰기 위한 값 |

## BinaryWriter::Write(const String\&) 메서드


현재 인코딩으로 길이 앞에 붙은 문자열을 출력 스트림에 씁니다.

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 쓰기 위한 문자열 |

## BinaryWriter::Write(const char_t *) 메서드


현재 인코딩으로 길이 앞에 붙은 문자열을 출력 스트림에 씁니다.

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const char_t * | 쓰기 위한 C-문자열 |

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [BinaryWriter](../)
* 클래스 [Decimal](../../../system/decimal/)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)