---
title: ContentDispositionHeaderValue
second_title: Aspose.Slides for C++ API 레퍼런스
description: "'Content-Disposition' 헤더의 값을 나타냅니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 인스턴스를 직접 생성하거나 operator new를 사용하지 마세요. 그렇지 않으면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하십시오."
type: docs
weight: 27
url: /ko/system.net.http.headers/contentdispositionheadervalue/
---
## ContentDispositionHeaderValue 클래스

'Content-Disposition' 헤더의 값을 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 인스턴스를 직접 생성하거나 operator new를 사용하지 마세요. 그렇지 않으면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸서 함수 인수로 전달하십시오.

```cpp
class ContentDispositionHeaderValue : public System::ICloneable
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  [ContentDispositionHeaderValue](./contentdispositionheadervalue/)() | 새 인스턴스를 생성합니다. |
|  [ContentDispositionHeaderValue](./contentdispositionheadervalue/)([String](../../system/string/)) | 새 인스턴스를 생성합니다. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 (NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 (NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_CreationDate](./get_creationdate/)() | 파일 생성 날짜를 가져옵니다. |
| [String](../../system/string/) [get_DispositionType](./get_dispositiontype/)() | 배치 유형을 가져옵니다. |
| [String](../../system/string/) [get_FileName](./get_filename/)() | 메시지 페이로드를 저장하기 위한 파일 이름을 구성하는 방법을 결정하는 값을 가져옵니다. 엔터티가 분리되어 별도의 파일에 저장될 때 사용됩니다. |
| [String](../../system/string/) [get_FileNameStar](./get_filenamestar/)() | 메시지 페이로드를 저장하기 위한 파일 이름을 구성하는 방법을 결정하는 값을 가져옵니다. 엔터티가 분리되어 별도의 파일에 저장될 때 사용됩니다. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_ModificationDate](./get_modificationdate/)() | 파일 수정 날짜를 가져옵니다. |
| [String](../../system/string/) [get_Name](./get_name/)() | 콘텐츠 본문의 일부에 대한 이름을 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Parameters](./get_parameters/)() | ‘Content-Disposition’ 헤더의 매개변수 컬렉션을 반환합니다. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_ReadDate](./get_readdate/)() | 파일이 마지막으로 읽힌 날짜를 가져옵니다. |
| [Nullable](../../system/nullable/)\<**int64_t**\> [get_Size](./get_size/)() | 대략적인 파일 크기를 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| static **int32_t** [GetDispositionTypeLength](./getdispositiontypelength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 지정된 인덱스부터 전달된 문자열을 [ContentDispositionHeaderValue](./) 클래스의 인스턴스로 변환합니다. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입을 복제할 수 있습니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스의 복사 생성을 가능하게 합니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[ContentDispositionHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | 전달된 문자열을 [ContentDispositionHeaderValue](./) 클래스의 인스턴스로 변환합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체와 nullptr를 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_CreationDate](./set_creationdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | 파일 생성 날짜를 설정합니다. |
| void [set_DispositionType](./set_dispositiontype/)([String](../../system/string/)) | 배치 유형을 설정합니다. |
| void [set_FileName](./set_filename/)([String](../../system/string/)) | 메시지 페이로드를 저장하기 위한 파일 이름을 구성하는 방법을 결정하는 값을 설정합니다. 엔터티가 분리되어 별도의 파일에 저장될 때 사용됩니다. |
| void [set_FileNameStar](./set_filenamestar/)([String](../../system/string/)) | 메시지 페이로드를 저장하기 위한 파일 이름을 구성하는 방법을 결정하는 값을 설정합니다. 엔터티가 분리되어 별도의 파일에 저장될 때 사용됩니다. |
| void [set_ModificationDate](./set_modificationdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | 파일 수정 날짜를 설정합니다. |
| void [set_Name](./set_name/)([String](../../system/string/)) | 콘텐츠 본문의 일부에 대한 이름을 설정합니다. |
| void [set_ReadDate](./set_readdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | 파일이 마지막으로 읽힌 날짜를 설정합니다. |
| void [set_Size](./set_size/)([Nullable](../../system/nullable/)\<**int64_t**\>) | 대략적인 파일 크기를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 weak 포인터(공유가 아닌)로 설정합니다. 컨테이너에서 포인터를 weak 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ContentDispositionHeaderValue](./)\>\&) | 전달된 문자열을 [ContentDispositionHeaderValue](./) 클래스의 인스턴스로 변환하려 시도합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [ICloneable](../../system/icloneable/)
* 네임스페이스 [System::Net::Http::Headers](../)
* 라이브러리 [Aspose.Slides](../../)