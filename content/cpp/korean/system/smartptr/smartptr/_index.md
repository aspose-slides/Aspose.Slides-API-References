---
title: SmartPtr()
second_title: Aspose.Slides for C++ API 참조
description: 필요한 모드의 SmartPtr 객체를 생성합니다.
type: docs
weight: 1
url: /ko/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) 생성자

필요한 모드의 [SmartPtr](../) 객체를 생성합니다.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | 포인터 모드. |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) 생성자

필요한 모드의 null-pointer [SmartPtr](../) 객체를 생성합니다.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| mode | std::nullptr_t | 포인터 모드. |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) 생성자

지정된 객체를 가리키는 [SmartPtr](../) 를 생성하거나 raw 포인터를 [SmartPtr](../) 로 변환합니다.

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | 피오브젝트. |
| mode | [SmartPtrMode](../../smartptrmode/) | 포인터 모드. |

## SmartPtr::SmartPtr(const SmartPtr_&, SmartPtrMode) 생성자

복사 생성으로 [SmartPtr](../) 객체를 만듭니다. 이후 두 포인터는 동일한 객체를 가리킵니다.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | 복사할 포인터. |
| mode | [SmartPtrMode](../../smartptrmode/) | 포인터 모드. |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>&, SmartPtrMode) 생성자

복사 생성으로 [SmartPtr](../) 객체를 만듭니다. 이후 두 포인터는 동일한 객체를 가리킵니다. 허용되는 경우 타입 변환을 수행합니다.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Q | x가 가리키는 객체의 타입. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | 복사할 포인터. |
| mode | [SmartPtrMode](../../smartptrmode/) | 포인터 모드. |

## SmartPtr::SmartPtr(SmartPtr_&&, SmartPtrMode) 생성자

이동 생성으로 [SmartPtr](../) 객체를 만듭니다. 사실상 두 포인터가 동일 모드인 경우 스왑합니다. 호출 후 x는 사용 불가능할 수 있습니다.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | 이동할 포인터. |
| mode | [SmartPtrMode](../../smartptrmode/) | 포인터 모드. |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>&, SmartPtrMode) 생성자

다른 타입의 새로운 배열을 생성하여 참조된 배열의 타입을 변환합니다. C#에서 지원되는 배열 타입 캐스트가 C++에서는 지원되지 않을 때 유용합니다.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Y | 원본 배열의 타입. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | 복사할 배열의 포인터이지만 요소 타입이 다른 경우. |
| mode | [SmartPtrMode](../../smartptrmode/) | 포인터 모드. |

## SmartPtr::SmartPtr(const Y&) 생성자

빈 배열을 초기화합니다. 일부 C# 코드 구문을 변환하는 데 사용됩니다.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Y | EmptyArrayInitializer 타입의 자리표시자. |

## SmartPtr::SmartPtr(const SmartPtr\<P\>&, Pointee_ *, SmartPtrMode) 생성자

[SmartPtr](../) 를 생성합니다. 이 객체는 ptr의 초기 값과 소유권 정보를 공유하지만, 관련이 없고 관리되지 않은 포인터 p를 보유합니다.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | 소유권을 공유할 다른 스마트 포인터. |
| p | [Pointee_](../pointee_/) * | 관리할 객체의 포인터. |
| mode | [SmartPtrMode](../../smartptrmode/) | 포인터 모드. |
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream"

// 이 클래스는 출력될 필드를 포함하고 있습니다.
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// 이 클래스는 Foo 클래스의 인스턴스를 포함하고 있습니다.
class Bar : public System::Object
{
public:
  Foo data;
};

// Foo 클래스 인스턴스의 문자열을 출력하는 데 사용됩니다.
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// 객체를 가리키는 공유 포인터의 수를 출력합니다.
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // Bar 클래스 인스턴스에 대한 SharedPtr을 생성합니다.
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // Bar 클래스 인스턴스의 필드를 가리키는 SharedPtr을 생성합니다.
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // 'bar' 포인터를 nullptr로 설정합니다.
  bar.reset();
  PrintSharedCount(bar);
  // bar->data는 여전히 존재하고 'foo' 포인터는 유효합니다.
  PrintMessage(foo);

  return 0;
}
/*
이 코드 예제는 다음 출력 결과를 생성합니다:
Number of shared pointers: 1
Number of shared pointers: 2
Number of shared pointers: 0
Hello, world!
*/
``` |

## 참고

* 열거형 [SmartPtrMode](../../smartptrmode/)
* 타입정의 [Pointee_](../pointee_/)
* 타입정의 [SmartPtr_](../smartptr_/)
* 클래스 [SmartPtr](../)
* 클래스 [Array](../../array/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)