---
title: Console
second_title: Aspose.Slides for C++ API 레퍼런스
description: 표준 출력 스트림에 데이터를 출력하는 메서드를 제공합니다. 이는 인스턴스 서비스를 갖지 않는 정적 타입입니다. 어떠한 방법으로도 인스턴스를 생성해서는 안 됩니다.
type: docs
weight: 196
url: /ko/system/console/
---
## Console 클래스

표준 출력 스트림에 데이터를 출력하는 메서드를 제공합니다. 이는 인스턴스 서비스를 갖지 않는 정적 타입입니다. 어떠한 방법으로도 인스턴스를 생성해서는 안 됩니다.

```cpp
class Console
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static void [Beep](./beep/)() | 구현되지 않음. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | 표준 오류 스트림을 나타내는 객체를 가리키는 공유 포인터를 반환합니다. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | 표준 입력 스트림을 나타내는 객체를 가리키는 공유 포인터를 반환합니다. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | 표준 출력 스트림을 나타내는 객체를 가리키는 공유 포인터를 반환합니다. |
| static void [Mute](./mute/)(**bool**) | 표준 출력 스트림을 음소거하거나 음소거 해제합니다. |
| static void [ReadKey](./readkey/)() | 구현되지 않음. |
| static void [set_Title](./set_title/)(const [String](../string/)\&) | 콘솔 창 캡션을 설정합니다. |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | 지정된 객체를 클래스의 Error 속성에 할당합니다. |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | In 속성을 지정된 TextReader 객체로 설정합니다. |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | 지정된 객체를 클래스의 Out 속성에 할당합니다. |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 지정된 객체의 문자열 표현을 표준 출력 스트림에 출력합니다. |
| static void [Write](./write/)(**bool**) | bool 값의 문자열 표현을 표준 출력 스트림에 출력합니다. |
| static void [Write](./write/)(char_t) | 지정된 문자 값을 표준 출력 스트림에 출력합니다. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | 지정된 문자 배열의 문자열 표현을 표준 출력 스트림에 출력합니다. |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | [Decimal](../decimal/) 값의 문자열 표현을 표준 출력 스트림에 출력합니다. |
| static void [Write](./write/)(**double**) | double 정밀 부동소수점 값의 문자열 표현을 표준 출력 스트림에 출력합니다. |
| static void [Write](./write/)(**float**) | single 정밀 부동소수점 값의 문자열 표현을 표준 출력 스트림에 출력합니다. |
| static void [Write](./write/)(**int32_t**) | 32비트 정수 값의 문자열 표현을 표준 출력 스트림에 출력합니다. |
| static void [Write](./write/)(**int64_t**) | 64비트 정수 값의 문자열 표현을 표준 출력 스트림에 출력합니다. |
| static void [Write](./write/)(const [String](../string/)\&) | 지정된 문자열 객체를 표준 출력 스트림에 출력합니다. |
| static void [Write](./write/)(const char_t *) | 지정된 C 문자열을 표준 출력 스트림에 출력합니다. |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | [TypeInfo](../typeinfo/) 값의 문자열 표현을 표준 출력 스트림에 출력합니다. |
| static void [Write](./write/)(**uint32_t**) | 부호 없는 32비트 정수 값의 문자열 표현을 표준 출력 스트림에 출력합니다. |
| static void [Write](./write/)(**uint64_t**) | 부호 없는 64비트 정수 값의 문자열 표현을 표준 출력 스트림에 출력합니다. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | 지정된 문자 배열의 지정된 범위에 대한 문자열 표현을 표준 출력 스트림에 출력합니다. |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | 지정된 형식에 따라 지정된 인수들의 문자열 표현을 표준 출력 스트림에 출력합니다. |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | 현재 줄 구분자를 표준 출력 스트림에 출력합니다. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 지정된 객체의 문자열 표현을 현재 줄 구분자와 함께 표준 출력 스트림에 출력합니다. |
| static void [WriteLine](./writeline/)(**bool**) | bool 값의 문자열 표현을 현재 줄 구분자와 함께 표준 출력 스트림에 출력합니다. |
| static void [WriteLine](./writeline/)(char_t) | 지정된 문자 값을 현재 줄 구분자와 함께 표준 출력 스트림에 출력합니다. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | 지정된 문자 배열의 문자열 표현을 현재 줄 구분자와 함께 표준 출력 스트림에 출력합니다. |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | [Decimal](../decimal/) 값의 문자열 표현을 현재 줄 구분자와 함께 표준 출력 스트림에 출력합니다. |
| static void [WriteLine](./writeline/)(**double**) | double 정밀 부동소수점 값의 문자열 표현을 현재 줄 구분자와 함께 표준 출력 스트림에 출력합니다. |
| static void [WriteLine](./writeline/)(**float**) | single 정밀 부동소수점 값의 문자열 표현을 현재 줄 구분자와 함께 표준 출력 스트림에 출력합니다. |
| static void [WriteLine](./writeline/)(**int32_t**) | 32비트 정수 값의 문자열 표현을 현재 줄 구분자와 함께 표준 출력 스트림에 출력합니다. |
| static void [WriteLine](./writeline/)(**int64_t**) | 64비트 정수 값의 문자열 표현을 현재 줄 구분자와 함께 표준 출력 스트림에 출력합니다. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | 지정된 문자열 객체를 현재 줄 구분자와 함께 표준 출력 스트림에 출력합니다. |
| static void [WriteLine](./writeline/)(const char_t *) | 지정된 C 문자열을 현재 줄 구분자와 함께 표준 출력 스트림에 출력합니다. |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | [TypeInfo](../typeinfo/) 값의 문자열 표현을 현재 줄 구분자와 함께 표준 출력 스트림에 출력합니다. |
| static void [WriteLine](./writeline/)(**uint32_t**) | 부호 없는 32비트 정수 값의 문자열 표현을 현재 줄 구분자와 함께 표준 출력 스트림에 출력합니다. |
| static void [WriteLine](./writeline/)(**uint64_t**) | 부호 없는 64비트 정수 값의 문자열 표현을 현재 줄 구분자와 함께 표준 출력 스트림에 출력합니다. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | 지정된 문자 배열의 지정된 범위에 대한 문자열 표현을 현재 줄 구분자와 함께 표준 출력 스트림에 출력합니다. |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | 지정된 Exception 객체의 문자열 표현을 현재 줄 구분자와 함께 표준 출력 스트림에 출력합니다. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | 지정된 형식에 따라 지정된 인수들의 문자열 표현을 현재 줄 구분자와 함께 표준 출력 스트림에 출력합니다. |
| static void [WriteLine](./writeline/)(const char *) |  |

## 비고

```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // 인사말을 출력합니다.
  Console::WriteLine(u"Hello, world!");

  // 'std::array' 클래스의 인스턴스를 생성합니다.
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // 배열의 요소들을 출력합니다.
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
이 코드 예제는 다음과 같은 출력을 생성합니다:
Hello, world!
1 2 3 4 5
*/
```

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)