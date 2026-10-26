---
title: Thread
second_title: Aspose.Slides for C++ API 레퍼런스
description: "Thread 구현. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용해 이 타입의 인스턴스를 만들지 마십시오. 그렇지 않으면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하십시오."
type: docs
weight: 209
url: /ko/system.threading/thread/
---
## Thread 클래스


[Thread](./) 구현. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Thread : public System::Object
```

## 메서드

| Method | Description |
| --- | --- |
| void [Abort](./abort/)() | 스레드를 중단합니다. 구현되지 않음. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 객체를 C# [Object.Equals](../../system/object/equals/) 의미로 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# 스타일 부동소수점 비교를 에뮬레이트합니다. 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값(包括 NaN)과도 같지 않지만, 여기서는 동일하게 간주됩니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# 스타일 부동소수점 비교를 에뮬레이트합니다. 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값(包括 NaN)과도 같지 않지만, 여기서는 동일하게 간주됩니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentCulture](./get_currentculture/)() | 스레드 문화권을 가져옵니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Thread](./)\> [get_CurrentThread](./get_currentthread/)() | 현재 스레드를 설명하는 객체를 가져옵니다. |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentUICulture](./get_currentuiculture/)() | 스레드가 사용하는 사용자 인터페이스 문화권을 가져옵니다. |
| **bool** [get_IsAlive](./get_isalive/)() | 스레드가 살아 있는지 확인합니다. |
| **bool** [get_IsBackground](./get_isbackground/)() | 스레드가 백그라운드인지 확인합니다. |
| **bool** [get_IsThreadPoolThread](./get_isthreadpoolthread/)() | 스레드가 스레드 풀에 의해 소유되는지 확인합니다. |
| int [get_ManagedThreadId](./get_managedthreadid/)() const | 스레드 식별자를 가져옵니다. OS로부터 얻을 수 있지만, OS 스레드 식별자가 int 한도를 초과하면 스레드 ID가 충돌할 수 있습니다. |
| [System::String](../../system/string/) [get_Name](./get_name/)() | 스레드 이름을 가져옵니다. |
| [ThreadState](../threadstate/) [get_ThreadState](./get_threadstate/)() | 스레드 상태를 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| static int [GetCurrentThreadId](./getcurrentthreadid/)() | 현재 스레드의 식별자를 가져옵니다. |
| int [GetHashCode](./gethashcode/)() const override |  |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| void [Interrupt](./interrupt/)() | 스레드를 중단합니다. 구현되지 않음. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Join](./join/)() | 관리되는 스레드에 조인합니다. 필요시 무제한 대기를 수행합니다. |
| **bool** [Join](./join/)(int) | 관리되는 스레드에 조인합니다. 제한된 대기를 수행합니다. |
| **bool** [Join](./join/)([TimeSpan](../../system/timespan/)) | 관리되는 스레드에 조인합니다. 제한된 대기를 수행합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠금합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
| static void [MemoryBarrier](./memorybarrier/)() | 메모리 접근을 동기화합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Thread](./)\& [operator=](./operator_equal/)(const [Thread](./)\&) | 다른 스레드에서 TLS 데이터를 복사합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_CurrentCulture](./set_currentculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 스레드 문화권을 설정합니다. |
| void [set_CurrentUICulture](./set_currentuiculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 스레드가 사용하는 사용자 인터페이스 문화권을 설정합니다. |
| void [set_IsBackground](./set_isbackground/)(**bool**) | 스레드를 백그라운드 또는 포그라운드로 설정합니다. |
| void [set_Name](./set_name/)(const [System::String](../../system/string/)\&) | 스레드 이름을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| static void [Sleep](./sleep/)(int) | 지정된 시간 제한 동안 현재 스레드를 중지합니다. |
| static void [Sleep](./sleep/)([TimeSpan](../../system/timespan/)) | 지정된 시간 제한 동안 현재 스레드를 중지합니다. |
| static void [SpinWait](./spinwait/)(int) | 특정 루프 반복 횟수만큼 대기합니다. |
| void [Start](./start/)() | null 인수 객체를 사용해 스레드를 시작합니다. |
| void [Start](./start/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | 스레드를 시작합니다. |
|  [Thread](./thread/)() | 생성자. |
|  [Thread](./thread/)([ThreadStart](../threadstart/)) | 생성자. |
|  [Thread](./thread/)([ParameterizedThreadStart](../parameterizedthreadstart/)) | 생성자. |
|  [Thread](./thread/)([Thread](./)\&) | 복사 생성자. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 구현하여 잠금 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| static **bool** [Yield](./yield/)() | 스레드를 양보합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
| virtual  [~Thread](./~thread/)() | 소멸자. |

## 비고



```cpp
#include "system/threading/thread.h"
#include "system/smart_ptr.h"

int main()
{
  auto thread = System::MakeObject<System::Threading::Thread>([]()
  {
    std::cout << "Child thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;
    System::Threading::Thread::Sleep(200);
  });

  std::cout << "Main thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;

  thread->Start();
  thread->Join();

  return 0;
}
/*
이 코드 예제는 다음 출력을 생성합니다:
메인 스레드 ID: 2
자식 스레드 ID: 1
*/
```

## 참고

* 클래스 [Object](../../system/object/)
* 네임스페이스 [System::Threading](../)
* 라이브러리 [Aspose.Slides](../../)