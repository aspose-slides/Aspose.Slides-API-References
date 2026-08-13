---
title: UnmanagedMemoryStream
second_title: Aspose.Slides for C++ API 레퍼런스
description: "제어되지 않은 메모리에 대한 액세스를 제공합니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 이 유형의 인스턴스를 만들거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 일으킬 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달하십시오."
type: docs
weight: 456
url: /ko/system.io/unmanagedmemorystream/
---
## UnmanagedMemoryStream 클래스

제어되지 않은 메모리에 대한 액세스를 제공합니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수만을 사용하여 할당해야 합니다. 스택에 이 타입의 인스턴스를 만들거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래할 수 있습니다. [System::SmartPtr](../../system/smartptr/) 포인터로 이 클래스를 항상 래핑하고, 이 포인터를 인수로 함수에 전달하십시오.

```cpp
class UnmanagedMemoryStream : public System::IO::Stream
```

## 메서드

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 비동기 읽기 작업을 시작합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 비동기 쓰기 작업을 시작합니다. |
| virtual void [Close](../stream/close/)() | 스트림을 닫습니다. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | 바이트를 지정된 스트림에 복사합니다. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | 지정된 버퍼 크기를 사용하여 바이트를 지정된 스트림에 복사합니다. |
| void [Dispose](../stream/dispose/)() override | 현재 객체가 사용한 모든 리소스를 해제하고 스트림을 닫습니다. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 지정된 비동기 읽기 작업이 완료될 때까지 기다립니다. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 비동기 쓰기 작업을 종료합니다. 지정된 비동기 쓰기 작업이 완료될 때까지 기다립니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| void [Flush](./flush/)() override | 아무것도 수행하지 않습니다. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 이 스트림의 모든 버퍼를 비동기적으로 비우고, 버퍼링된 데이터를 기본 장치에 기록하도록 하며, 취소 요청을 모니터링합니다. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | 이 스트림의 모든 버퍼를 비동기적으로 비우고, 버퍼링된 데이터를 기본 장치에 기록하도록 하며, 취소 요청을 모니터링합니다. |
| **bool** [get_CanRead](./get_canread/)() const override | 스트림이 읽기 가능한지 확인합니다. |
| **bool** [get_CanSeek](./get_canseek/)() const override | 스트림이 시킹을 지원하는지 확인합니다. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | 현재 스트림이 타임아웃될 수 있는지 여부를 결정하는 값을 가져옵니다. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | 스트림이 쓰기 가능한지 확인합니다. |
| virtual **int64_t** [get_Capacity](./get_capacity/)() const | 기본 메모리 버퍼의 현재 용량을 반환합니다. |
| **int64_t** [get_Length](./get_length/)() const override | 스트림의 길이를 바이트 단위로 반환합니다. |
| **int64_t** [get_Position](./get_position/)() const override | 스트림의 현재 위치를 반환합니다. |
| **uint8_t** * [get_PositionPointer](./get_positionpointer/)() | 구현되지 않음. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | 타임아웃되기 전에 스트림이 읽기를 시도할 시간을 밀리초 단위로 가져옵니다. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | 타임아웃되기 전에 스트림이 쓰기를 시도할 시간을 밀리초 단위로 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 하위 클래스의 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 하위 클래스의 복사 구성을 가능하게 합니다. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 스트림에서 지정된 바이트 수를 읽고 지정된 바이트 배열에 씁니다. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 스트림에서 지정된 바이트 수를 읽고 지정된 바이트 배열에 씁니다. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | 스트림에서 지정된 바이트 수를 읽고 지정된 바이트 배열에 씁니다. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | 스트림에서 지정된 바이트 수를 읽고 지정된 바이트 span에 씁니다. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 현재 스트림에서 바이트 시퀀스를 비동기적으로 읽고, 읽은 바이트 수만큼 스트림 내 위치를 진행시키며, 취소 요청을 모니터링합니다. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 현재 스트림에서 바이트 시퀀스를 비동기적으로 읽고, 읽은 바이트 수만큼 스트림 내 위치를 진행시키며, 취소 요청을 모니터링합니다. |
| virtual int [ReadByte](../stream/readbyte/)() | 스트림에서 단일 바이트를 읽고 읽은 바이트 값에 해당하는 32비트 정수 값을 반환합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조에 따라 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조에 따라 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | 현재 객체가 나타내는 스트림 위치를 설정합니다. |
| void [set_Position](./set_position/)(**int64_t**) override | 스트림의 위치를 설정합니다. |
| void [set_PositionPointer](./set_positionpointer/)(**uint8_t** *) | 구현되지 않음. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | 현재 스트림이 타임아웃될 수 있는지 여부를 결정하는 값을 설정합니다. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | 타임아웃되기 전에 스트림이 읽기를 시도할 시간을 밀리초 단위로 설정합니다. |
| void [SetLength](./setlength/)(**int64_t**) override | 구현되지 않음. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
|  [UnmanagedMemoryStream](./unmanagedmemorystream/)(**uint8_t** *, **int64_t**) | [UnmanagedMemoryStream](./)의 새 인스턴스를 생성합니다. |
|  [UnmanagedMemoryStream](./unmanagedmemorystream/)(**uint8_t** *, **int64_t**, **int64_t**, [FileAccess](../fileaccess/)) | [UnmanagedMemoryStream](./)의 새 인스턴스를 생성합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 구현되지 않음. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 구현되지 않음. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | 지정된 바이트 배열에서 지정된 바이트 서브레인지를 스트림에 씁니다. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | 지정된 바이트 span에서 지정된 바이트 서브레인지를 스트림에 씁니다. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 현재 스트림에 바이트 시퀀스를 비동기적으로 쓰고, 쓰여진 바이트 수만큼 스트림 내 현재 위치를 진행시키며, 취소 요청을 모니터링합니다. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 현재 스트림에 바이트 시퀀스를 비동기적으로 쓰고, 쓰여진 바이트 수만큼 스트림 내 현재 위치를 진행시키며, 취소 요청을 모니터링합니다. |
| virtual void [WriteByte](../stream/writebyte/)(**uint8_t**) | 지정된 부호 없는 8비트 정수 값을 스트림에 씁니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 필드

| Field | Description |
| --- | --- |
| static [Null](../stream/null/) | 기본 저장소가 없는 스트림. |

## 참조

* 클래스 [Stream](../stream/)
* 네임스페이스 [System::IO](../)
* 라이브러리 [Aspose.Slides](../../)