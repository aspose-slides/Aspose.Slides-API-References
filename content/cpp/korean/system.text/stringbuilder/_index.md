---
title: StringBuilder
second_title: "Aspose.Slides for C++ API 레퍼런스"
description: "문자열을 부분별로 누적하기 위한 버퍼입니다. 이 유형은 값 타입으로 스택에 할당하거나 System::MakeObject() 함수를 사용해 힙에 할당할 수 있습니다. 객체가 할당된 후에는 두 사용 사례를 절대로 혼합하지 마십시오: 스택에 할당된 객체에 대한 SmartPtr 포인터를 갖는 것은 엄격히 금지됩니다."
type: docs
weight: 326
url: /ko/system.text/stringbuilder/
---
## StringBuilder 클래스

[Buffer](../../system/buffer/) 문자열을 부분별로 누적하기 위해. 이 유형은 값 타입으로 스택에 할당하거나 [System::MakeObject()](../../system/makeobject/) 함수를 사용해 힙에 할당할 수 있습니다. 객체가 할당된 후에는 두 사용 사례를 절대로 혼합하지 마십시오: 스택에 할당된 객체에 대한 [SmartPtr](../../system/smartptr/) 포인터를 갖는 것은 엄격히 금지됩니다.

```cpp
class StringBuilder : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | builder에 문자를 추가합니다. |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | builder에 문자를 추가합니다. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | builder에 문자 배열을 추가합니다. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | builder에 문자 배열 조각을 추가합니다. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | builder에 문자열을 추가합니다. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | builder에 문자열 조각을 추가합니다. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | 객체의 문자열 표현을 builder에 추가합니다. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | builder의 내용을 builder에 추가합니다. |
| [StringBuilder](./) * [Append](./append/)(**float**) | builder에 부동 소수점 값을 추가합니다. |
| [StringBuilder](./) * [Append](./append/)(**double**) | builder에 부동 소수점 값을 추가합니다. |
| [StringBuilder](./) * [Append](./append/)(int) | builder에 정수 값을 추가합니다. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | builder에 산술 값을 추가합니다. |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | builder에 열거형 값의 문자열 표현을 추가합니다. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | builder에 서식화된 문자열을 추가합니다. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | builder에 서식화된 문자열을 추가합니다. |
| [StringBuilder](./) * [AppendLine](./appendline/)() | builder에 새 줄 문자를 추가합니다. |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | builder에 문자열과 새 줄 문자를 이어서 추가합니다. |
| [StringBuilder](./) * [Clear](./clear/)() | builder의 모든 문자를 제거합니다. |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | builder의 데이터를 기존 배열 위치에 복사합니다. |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | [System.Text.StringBuilder](./)의 이 인스턴스 용량이 지정된 값 이상인지 보장합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계로 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일의 부동 소수점 비교를 흉내내어 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일의 부동 소수점 비교를 흉내내어 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용. |
| int [get_Capacity](./get_capacity/)() const | 문자열 builder의 현재 용량을 가져옵니다. |
| int [get_Length](./get_length/)() const | builder에 현재 포함된 문자열의 길이를 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| char_t [idx_get](./idx_get/)(int) const | 지정된 위치의 문자를 가져옵니다. |
| void [idx_set](./idx_set/)(int, char_t) | 지정된 위치에 문자를 설정합니다. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | builder의 고정 위치에 문자열을 삽입합니다. |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | builder의 고정 위치에 반복 문자열을 삽입합니다. |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | builder의 고정 위치에 문자를 삽입합니다. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | builder의 고정 위치에 문자를 삽입합니다. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | builder의 고정 위치에 값을 삽입합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# ‘is’ 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고, 새 객체를 초기화하고 하위 클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않고, 새 객체를 초기화하고 하위 클래스 복사 생성을 가능하게 합니다. |
| char_t [operator[]](./operator[]/)(int) const | 지정된 위치의 문자를 가져옵니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화. |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | builder에서 조각을 제거합니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | builder를 통해 부분 문자열을 교체합니다. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | builder의 범위를 통해 부분 문자열을 교체합니다. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | builder를 통해 문자를 교체합니다. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | builder의 범위를 통해 문자를 교체합니다. |
| void [set_Capacity](./set_capacity/)(int) | 문자열 builder의 현재 용량을 설정합니다. |
| void [set_Length](./set_length/)(int) | 문자열 builder를 지정된 길이로 잘라내거나 확장합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유 대신)로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
|  [StringBuilder](./stringbuilder/)() | 생성자. |
|  [StringBuilder](./stringbuilder/)(int) | 생성자. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | 생성자. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | 생성자. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | 생성자. |
| [String](../../system/string/) [ToString](./tostring/)() const override | builder에 현재 포함된 문자열을 가져옵니다. |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | builder에 현재 포함된 부분 문자열을 가져옵니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
|  [~StringBuilder](./~stringbuilder/)() | 소멸자. |
## 참고

* 클래스 [Object](../../system/object/)
* 네임스페이스 [System::Text](../)
* 라이브러리 [Aspose.Slides](../../)