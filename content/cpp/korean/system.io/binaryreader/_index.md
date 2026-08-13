---
title: BinaryReader
second_title: Aspose.Slides for C++ API 레퍼런스
description: "특정 인코딩으로 기본 데이터 형식을 바이너리 데이터로 읽는 리더를 나타냅니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여만 할당해야 합니다. 스택에 이 타입의 인스턴스를 만들거나 operator new를 사용하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고 해당 포인터를 함수 인자로 전달하여 사용하십시오."
type: docs
weight: 92
url: /ko/system.io/binaryreader/
---
## BinaryReader 클래스

특정 인코딩으로 기본 데이터 형식을 바이너리 데이터로 읽는 리더를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 이 유형의 인스턴스를 만들거나 operator new를 사용해서는 안 됩니다. 그 경우 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하여 사용하십시오.

```cpp
class BinaryReader : public System::IDisposable
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | [BinaryReader](./) 클래스의 인스턴스를 생성하며, 지정된 스트림에서 UTF-8 인코딩을 사용해 데이터를 읽습니다. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | [BinaryReader](./) 클래스의 인스턴스를 생성하며, 지정된 스트림에서 지정된 인코딩을 사용해 데이터를 읽습니다. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&, **bool**) | [BinaryReader](./) 클래스의 인스턴스를 생성하며, 지정된 스트림에서 지정된 인코딩을 사용해 데이터를 읽습니다. |
| virtual void [Close](./close/)() | 현재 [BinaryReader](./) 객체와 기본 입력 스트림을 닫습니다. |
| void [Dispose](./dispose/)() override | 현재 객체가 사용한 모든 리소스를 해제하고 기본 스트림을 닫습니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미론을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일의 부동소수점 비교를 흉내내어 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일의 부동소수점 비교를 흉내내어 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() | 입력 스트림을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무 것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자입니다. 실제로는 아무 것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| virtual int [PeekChar](./peekchar/)() | 스트림의 읽기 커서를 변경하지 않고 입력 스트림에서 단일 문자를 읽습니다. |
| virtual int [Read](./read/)() | 입력 스트림에서 단일 문자를 읽습니다. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 입력 스트림에서 지정된 바이트 수를 읽어 지정된 바이트 배열에 기록합니다. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | 입력 스트림에서 지정된 문자 수를 읽어 UTF-16 인코딩으로 변환하고, 지정된 위치에서 시작하는 지정된 문자 배열에 결과 UTF-16 문자를 기록합니다. |
| virtual **bool** [ReadBoolean](./readboolean/)() | 입력 스트림에서 단일 바이트를 읽어 논리값으로 반환합니다. |
| virtual **uint8_t** [ReadByte](./readbyte/)() | 입력 스트림에서 단일 바이트를 읽습니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadBytes](./readbytes/)(int) | 입력 스트림에서 지정된 바이트 수를 읽습니다. |
| virtual char_t [ReadChar](./readchar/)() | 입력 스트림에서 단일 문자를 읽습니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [ReadChars](./readchars/)(int) | 입력 스트림에서 지정된 문자 수를 읽어 UTF-16 인코딩으로 반환합니다. |
| virtual [Decimal](../../system/decimal/) [ReadDecimal](./readdecimal/)() | 구현되지 않음. |
| virtual **double** [ReadDouble](./readdouble/)() | 입력 스트림에서 8바이트를 읽어 double-precision 부동소수점 값으로 반환합니다. |
| virtual **int16_t** [ReadInt16](./readint16/)() | 입력 스트림에서 2바이트를 읽어 16비트 정수 값으로 반환합니다. |
| virtual int [ReadInt32](./readint32/)() | 입력 스트림에서 4바이트를 읽어 32비트 정수 값으로 반환합니다. |
| virtual **int64_t** [ReadInt64](./readint64/)() | 입력 스트림에서 8바이트를 읽어 64비트 정수 값으로 반환합니다. |
| virtual **int8_t** [ReadSByte](./readsbyte/)() | 입력 스트림에서 단일 바이트를 읽어 부호 있는 8비트 정수 값으로 반환합니다. |
| virtual **float** [ReadSingle](./readsingle/)() | 입력 스트림에서 4바이트를 읽어 single-precision 부동소수점 값으로 반환합니다. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | 현재 스트림에서 문자열을 읽습니다. 문자열은 길이가 앞에 붙으며, 길이는 7비트씩 인코딩된 정수로 표현됩니다. |
| virtual **uint16_t** [ReadUInt16](./readuint16/)() | 입력 스트림에서 2바이트를 읽어 부호 없는 16비트 정수 값으로 반환합니다. |
| virtual **uint32_t** [ReadUInt32](./readuint32/)() | 입력 스트림에서 4바이트를 읽어 부호 없는 32비트 정수 값으로 반환합니다. |
| virtual **uint64_t** [ReadUInt64](./readuint64/)() | 입력 스트림에서 8바이트를 읽어 부호 없는 64비트 정수 값으로 반환합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유 대신 약한 포인터로 설정합니다. 컨테이너 내부 포인터를 약한 모드로 전환할 수 있게 합니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~BinaryReader](./~binaryreader/)() | 소멸자. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴하고 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [IDisposable](../../system/idisposable/)
* 네임스페이스 [System::IO](../)
* 라이브러리 [Aspose.Slides](../../)