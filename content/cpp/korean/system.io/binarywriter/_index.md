---
title: BinaryWriter
second_title: Aspose.Slides for C++ API 레퍼런스
description: "원시 타입 값을 바이트 스트림에 기록하는 라이터를 나타냅니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용하여 이 유형의 인스턴스를 생성하면 런타임 오류 및/또는 어설션 결함이 발생하므로 절대 생성하지 마십시오. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 인자로 함수에 전달하도록 사용하십시오."
type: docs
weight: 105
url: /ko/system.io/binarywriter/
---
## BinaryWriter 클래스

원시 타입 값들을 바이트 스트림에 기록하는 라이터를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수만을 사용해 할당해야 합니다. 스택에 또는 operator new를 사용해 이 유형의 인스턴스를 생성하면 런타임 오류 및/또는 어설션 오류가 발생하므로 절대로 생성하지 마십시오. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 인자로 함수에 전달하도록 사용하십시오.

```cpp
class BinaryWriter : public System::IDisposable
```

## 메서드

| Method | 설명 |
| --- | --- |
|  [BinaryWriter](./binarywriter/)(const [StreamPtr](../../system/streamptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | [BinaryWriter](./) 클래스를 인스턴스화하여 지정된 인코딩을 사용해 지정된 스트림에 데이터를 기록합니다. |
| void [Close](./close/)() | 현재 [BinaryWriter](./) 객체와 기본 출력 스트림을 닫습니다. |
| void [Dispose](./dispose/)() override | 현재 객체가 사용한 모든 리소스를 해제하고 기본 스트림을 닫습니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용해 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| void [Flush](./flush/)() | 출력 스트림을 플러시합니다. |
| [StreamPtr](../../system/streamptr/) [get_BaseStream](./get_basestream/)() | 출력 스트림을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 동일합니다. 사용자 정의 객체의 해싱을 지원합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 동일합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 동일합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 동일합니다. 사용자 정의 타입 복제를 지원합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| **int64_t** [Seek](./seek/)(int, [System::IO::SeekOrigin](../seekorigin/)) | 현재 객체가 나타내는 스트림 위치를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 동일합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual void [Write](./write/)(**uint8_t**) | 지정된 부호 없는 8비트 정수 값을 출력 스트림에 기록합니다. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | 지정된 바이트 배열에서 지정된 바이트 범위를 출력 스트림에 기록합니다. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | 지정된 문자 배열에서 지정된 UTF-16 문자 범위를 출력 스트림에 기록합니다. |
| virtual void [Write](./write/)(**bool**) | **value**가 'true'이면 값 0을, 'false'이면 값 1을 가진 단일 바이트를 출력 스트림에 기록합니다. |
| virtual void [Write](./write/)(char16_t) | 지정된 16비트 와이드 문자 값을 출력 스트림에 기록합니다. |
| virtual void [Write](./write/)(**int16_t**) | 지정된 16비트 정수 값을 출력 스트림에 기록합니다. |
| virtual void [Write](./write/)(int) | 지정된 32비트 정수 값을 출력 스트림에 기록합니다. |
| virtual void [Write](./write/)(**int64_t**) | 지정된 64비트 정수 값을 출력 스트림에 기록합니다. |
| virtual void [Write](./write/)(**uint16_t**) | 지정된 부호 없는 16비트 정수 값을 출력 스트림에 기록합니다. |
| virtual void [Write](./write/)(**uint32_t**) | 지정된 부호 없는 32비트 정수 값을 출력 스트림에 기록합니다. |
| virtual void [Write](./write/)(**uint64_t**) | 지정된 부호 없는 64비트 정수 값을 출력 스트림에 기록합니다. |
| virtual void [Write](./write/)(**float**) | 지정된 단정도 부동소수점 값을 출력 스트림에 기록합니다. |
| virtual void [Write](./write/)(**double**) | 지정된 배정도 부동소수점 값을 출력 스트림에 기록합니다. |
| virtual void [Write](./write/)(const [Decimal](../../system/decimal/)\&) | 지정된 [Decimal](../../system/decimal/) 값의 바이트 표현을 출력 스트림에 기록합니다. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | 현재 인코딩으로 길이 접두사가 붙은 문자열을 출력 스트림에 기록합니다. |
| virtual void [Write](./write/)(const char_t *) | 현재 인코딩으로 길이 접두사가 붙은 문자열을 출력 스트림에 기록합니다. |
|  [~BinaryWriter](./~binarywriter/)() | 소멸자. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [IDisposable](../../system/idisposable/)
* 네임스페이스 [System::IO](../)
* 라이브러리 [Aspose.Slides](../../)