---
title: Process
second_title: Aspose.Slides for C++ API 레퍼런스
description: "프로세스 정보와 조작을 캡슐화합니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 직접 인스턴스를 만들거나 operator new를 사용하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 래핑하고, 이 포인터를 함수 인자로 전달하십시오."
type: docs
weight: 27
url: /ko/system.diagnostics/process/
---
## Process class

프로세스 정보와 조작을 캡슐화합니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 직접 인스턴스를 만들거나 operator new를 사용하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 래핑하고, 이 포인터를 함수 인자로 전달하십시오.

```cpp
class Process : public System::Object
```

## 메서드

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 서로 같다고 간주되는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 이 비교에서는 다르지 않게 처리됩니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 서로 같다고 간주되는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 이 비교에서는 다르지 않게 처리됩니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| **bool** [get_EnableRaisingEvents](./get_enableraisingevents/)() const | 프로세스가 종료될 때 Exited 이벤트를 발생시킬지 여부를 가져옵니다. |
| int [get_ExitCode](./get_exitcode/)() const | 프로세스 종료 코드를 가져옵니다. |
| **int64_t** [get_PrivateMemorySize64](./get_privatememorysize64/)() const | 프로세스 개인 메모리 집합 크기를 가져옵니다. |
| [String](../../system/string/) [get_ProcessName](./get_processname/)() const | 프로세스 이름을 가져옵니다. |
| [SharedPtr](../../system/sharedptr/)\<[System::IO::StreamReader](../../system.io/streamreader/)\> [get_StandardError](./get_standarderror/)() const | 프로세스 오류 출력에서 읽기 위한 리더를 제공합니다. 구현되지 않음. |
| [SharedPtr](../../system/sharedptr/)\<[System::IO::StreamReader](../../system.io/streamreader/)\> [get_StandardOutput](./get_standardoutput/)() const | 프로세스 표준 출력에서 읽기 위한 리더를 제공합니다. 구현되지 않음. |
| [SharedPtr](../../system/sharedptr/)\<[ProcessStartInfo](../processstartinfo/)\> [get_StartInfo](./get_startinfo/)() const | 프로세스 시작 정보를 가져옵니다. |
| **int64_t** [get_WorkingSet64](./get_workingset64/)() const | 프로세스 메모리 작업 집합 크기를 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| static [SharedPtr](../../system/sharedptr/)\<[Process](./)\> [GetCurrentProcess](./getcurrentprocess/)() | 현재 프로세스에 대한 정보를 가져옵니다. [Windows](../../system.windows/) 전용. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해시를 가능하게 합니다. |
| [String](../../system/string/) [GetOutputText](./getoutputtext/)() const | 프로세스 출력 텍스트를 가져옵니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 구문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_EnableRaisingEvents](./set_enableraisingevents/)(**bool**) | 프로세스가 종료될 때 Exited 이벤트를 발생시킬지 여부를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유 포인터 대신 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운트 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되고, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되고, 스마트 포인터나 ThisProtector를 사용하십시오. |
| **bool** [Start](./start/)() | 미리 정의된 매개변수로 프로세스를 시작합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[Process](./)\> [Start](./start/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 지정된 경로와 인수로 프로세스를 시작합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[Process](./)\> [Start](./start/)(const [SharedPtr](../../system/sharedptr/)\<[ProcessStartInfo](../processstartinfo/)\>\&) | 지정된 경로와 인수로 프로세스를 시작합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 구문의 잠금을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자를 사용하십시오. |
| **bool** [WaitForExit](./waitforexit/)(int) | 프로세스 종료를 기다립니다. 구현되지 않음. |
| void [WaitForExit](./waitforexit/)() | 프로세스가 종료될 때까지 기다리며, 종료될 때까지 반환하지 않습니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되고, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되고, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
| virtual  [~Process](./~process/)() | 소멸자. |

## 참고

* 클래스 [Object](../../system/object/)
* 네임스페이스 [System::Diagnostics](../)
* 라이브러리 [Aspose.Slides](../../)