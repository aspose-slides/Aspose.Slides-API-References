---
title: Comparison
second_title: Aspose.Slides for C++ API 참조
description: "같은 타입의 두 객체를 비교하는 메서드에 대한 포인터를 나타냅니다. 이 타입은 스택에 할당하고 값을 복사하거나 참조로 함수에 전달해야 합니다. 이 타입의 객체를 관리하기 위해 System::SmartPtr 클래스를 사용하지 마세요."
type: docs
weight: 183
url: /ko/system/comparison/
---
## Comparison 클래스

같은 유형의 두 객체를 비교하는 메서드에 대한 포인터를 나타냅니다. 이 유형은 스택에 할당하고 값을 복사하거나 참조로 함수에 전달해야 합니다. [System::SmartPtr](../smartptr/) 클래스를 사용하여 이 유형의 객체를 관리하지 마십시오.

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 메서드가 비교하는 객체의 유형 |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| **bool** [operator()](./operator_call/)(T, T) | 현재 객체가 가리키는 호출 가능한 객체를 호출합니다. |

## 비고



```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

// 동적 배열을 나타내는 템플릿 클래스입니다.
template <typename T>
class MyArray
{
  // 배열 데이터를 저장하는 데 사용됩니다.
  std::vector<T> m_data;

public:
  // 우리 동적 배열의 새 인스턴스를 생성합니다.
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  // 배열 데이터를 정렬하는 데 사용됩니다. 이 메서드는 다음의 인스턴스를 받아들입니다.
  // 'System::Comparison' 템플릿 클래스.
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  // 우리 동적 배열이 저장하는 요소 개수를 반환합니다.
  size_t get_Size()
  {
    return m_data.size();
  }

  // 지정된 인덱스의 요소를 가져오는 데 사용됩니다.
  T& operator[](int index)
  {
    if (index < 0 || index >= m_data.size())
    {
      throw IndexOutOfRangeException(u"index");
    }
    return m_data[index];
  }
};

int main() {
  // 지정된 요소로 MyArray 클래스의 인스턴스를 생성합니다.
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  // 동적 배열의 요소를 오름차순으로 정렬합니다.
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  // 동적 배열의 요소를 출력합니다.
  for (auto i = 0; i < arr.get_Size(); ++i)
  {
    Console::WriteLine(arr[i]);
  }

  return 0;
}
/*
이 코드 예제는 다음과 같은 출력을 생성합니다:
a
b
c
d
e
*/
```

## 관련 항목

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)