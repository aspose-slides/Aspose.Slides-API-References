---
title: Boolean
second_title: Aspose.Slides for C++ API 레퍼런스
description: System.Boolean .Net 타입의 정적 멤버를 보유하는 클래스.
type: docs
weight: 79
url: /ko/system/boolean/
---
## Boolean 클래스

정적 멤버를 보유하는 [System.Boolean](./) .[Net](../../system.net/) 타입의 클래스.

```cpp
class Boolean
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | 지정된 문자열을 bool 타입 값으로 변환합니다. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | 지정된 문자열을 bool 타입 값으로 변환합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/)는 'false' 부울 값의 표현입니다. |
| static [TrueString](./truestring/) | [String](../string/)는 'true' 부울 값의 표현입니다. |
## 비고



```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // 불리언 변수를 생성합니다.
  bool isWeekend = false;

  // 입력 문자열을 파싱하고 결과를 출력합니다.
  if (Boolean::TryParse(u"True", isWeekend))
  {
    std::cout << "Is weekend: " << (isWeekend ? "Yes" : "No");
  }
  else
  {
    std::cerr << "Something went wrong" << std::endl;
  }

  return 0;
}
/*
이 코드는 다음과 같은 출력 결과를 생성합니다:
Is weekend: Yes
*/
```

## 참조

* Namespace [System](../)
* Library [Aspose.Slides](../../)