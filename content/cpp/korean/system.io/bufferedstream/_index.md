---
title: BufferedStream
second_title: Aspose.Slides for C++ API 참조
description: "다른 스트림 위에 버퍼링 레이어를 추가합니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여만 할당해야 합니다. 스택에 이 타입의 인스턴스를 만들거나 operator new를 사용하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 인수로 함수에 전달하여 사용하십시오."
type: docs
weight: 118
url: /ko/system.io/bufferedstream/
---
## BufferedStream 클래스

다른 스트림 위에 버퍼링 레이어를 추가합니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 이 타입의 인스턴스를 만들거나 operator new를 사용해서는 안 됩니다. 그렇게 하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 인수로 함수에 전달하여 사용하십시오.

```cpp
class BufferedStream : public System::IO::Stream
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 비동기 읽기 작업을 시작합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 비동기 쓰기 작업을 시작합니다. |
|  [BufferedStream](./bufferedstream/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | 지정된 스트림을 래핑하고 4096바이트 길이의 버퍼를 사용하는 [BufferedStream](./) 객체를 생성합니다. |
|  [BufferedStream](./bufferedstream/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, int) | 지정된 스트림을 래핑하고 지정된 크기의 버퍼를 사용하는 [BufferedStream](./) 객체를 생성합니다. |
| virtual void [Close](../stream/close/)() | 스트림을 닫습니다. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | 바이트를 지정된 스트림에 복사합니다. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | 지정된 버퍼 크기를 사용하여 바이트를 지정된 스트림에 복사합니다. |
| void [Dispose](../stream/dispose/)() override | 현재 객체가 사용한 모든 리소스를 해제하고 스트림을 닫습니다. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 지정된 비동기 읽기 작업이 완료될 때까지 대기합니다. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | 비동기 쓰기 작업을 종료합니다. 지정된 비동기 쓰기 작업이 완료될 때까지 대기합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 취급합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 취급합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| void [Flush](./flush/)() override | 버퍼의 내용을 기본 스트림에 씁니다. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 이 스트림의 모든 버퍼를 비동기적으로 비우고, 버퍼링된 데이터를 기본 장치에 기록하도록 하고, 취소 요청을 모니터링합니다. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | 이 스트림의 모든 버퍼를 비동기적으로 비우고, 버퍼링된 데이터를 기본 장치에 기록하도록 하고, 취소 요청을 모니터링합니다. |
| **bool** [get_CanRead](./get_canread/)() const override | 스트림이 읽기 가능한지 확인합니다. |
| **bool** [get_CanSeek](./get_canseek/)() const override | 스트림이 탐색을 지원하는지 확인합니다. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | 현재 스트림이 시간 초과될 수 있는지 여부를 결정하는 값을 가져옵니다. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | 스트림이 쓰기 가능한지 확인합니다. |
| **int64_t** [get_Length](./get_length/)() const override | 스트림의 길이를 반환합니다. |
| **int64_t** [get_Position](./get_position/)() const override | 스트림의 현재 위치를 반환합니다. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | 시간 초과가 발생하기 전에 스트림이 읽기를 시도할 최대 시간을 밀리초 단위로 가져옵니다. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | 시간 초과가 발생하기 전에 스트림이 쓰기를 시도할 최대 시간을 밀리초 단위로 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 구현입니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 구현입니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자의 유사 구현입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 구현입니다. 사용자 정의 타입의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 기본 스트림에서 지정된 바이트 수를 읽어 지정된 바이트 배열에 씁니다. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 기본 스트림에서 지정된 바이트 수를 읽어 지정된 바이트 배열에 씁니다. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | 스트림에서 지정된 바이트 수를 읽어 지정된 바이트 배열에 씁니다. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | 스트림에서 지정된 바이트 수를 읽어 지정된 바이트 스팬에 씁니다. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 현재 스트림에서 바이트 시퀀스를 비동기적으로 읽고, 읽은 바이트 수만큼 스트림 내 위치를 이동하며, 취소 요청을 모니터링합니다. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 현재 스트림에서 바이트 시퀀스를 비동기적으로 읽고, 읽은 바이트 수만큼 스트림 내 위치를 이동하며, 취소 요청을 모니터링합니다. |
| int [ReadByte](./readbyte/)() override | 기본 스트림에서 단일 바이트를 읽고, 읽은 바이트 값에 해당하는 32비트 정수 값을 반환합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | 현재 객체가 나타내는 스트림의 위치를 설정합니다. |
| void [set_Position](./set_position/)(**int64_t**) override | 버퍼를 기본 스트림에 플러시한 다음 스트림 위치를 설정합니다. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | 현재 스트림이 시간 초과될 수 있는지 여부를 결정하는 값을 설정합니다. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | 시간 초과가 발생하기 전에 스트림이 읽기를 시도할 최대 시간을 밀리초 단위로 설정합니다. |
| void [SetLength](./setlength/)(**int64_t**) override | 현재 객체가 나타내는 스트림의 길이를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 강한 포인터 대신 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 구현입니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 지정된 바이트 배열에서 지정된 바이트 하위 범위를 기본 스트림에 씁니다. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | 지정된 바이트 배열에서 지정된 바이트 하위 범위를 기본 스트림에 씁니다. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | 지정된 바이트 배열에서 지정된 바이트 하위 범위를 스트림에 씁니다. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | 지정된 바이트 스팬에서 지정된 바이트 하위 범위를 스트림에 씁니다. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | 현재 스트림에 바이트 시퀀스를 비동기적으로 쓰고, 쓰여진 바이트 수만큼 스트림 내 현재 위치를 이동하며, 취소 요청을 모니터링합니다. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 현재 스트림에 바이트 시퀀스를 비동기적으로 쓰고, 쓰여진 바이트 수만큼 스트림 내 현재 위치를 이동하며, 취소 요청을 모니터링합니다. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | 지정된 부호 없는 8비트 정수 값을 기본 스트림에 씁니다. |
| virtual  [~BufferedStream](./~bufferedstream/)() | 소멸자. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| static [Null](../stream/null/) | 기본 저장소가 없는 스트림. |
## 관련 항목

* 클래스 [Stream](../stream/)
* 네임스페이스 [System::IO](../)
* 라이브러리 [Aspose.Slides](../../)