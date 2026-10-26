---
title: Cookie
second_title: Aspose.Slides for C++ API 참조
description: "HTTP 쿠키를 나타냅니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용해 이 유형의 인스턴스를 만들지 마십시오. 이렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고 이 포인터를 함수에 인수로 전달하십시오."
type: docs
weight: 1
url: /ko/system.net/cookie/
---
## Cookie 클래스

HTTP 쿠키를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용해 이 유형의 인스턴스를 만들지 마십시오. 이렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고 이 포인터를 함수에 인수로 전달하십시오.

```cpp
class Cookie : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | 현재 인스턴스의 복사본을 생성합니다. |
| [Cookie](./cookie/)() | 새 인스턴스를 생성합니다. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | 새 인스턴스를 생성합니다. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 새 인스턴스를 생성합니다. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 새 인스턴스를 생성합니다. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | ‘Comment’ 속성 값을 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | ‘CommentURL’ 속성 값을 가져옵니다. |
| **bool** [get_Discard](./get_discard/)() const | ‘Discard’ 속성 값을 가져옵니다. |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | ‘Domain’ 속성 값을 가져옵니다. |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | 도메인이 암시적인지 여부를 나타내는 값을 가져옵니다. |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | 도메인 키를 반환합니다. |
| **bool** [get_Expired](./get_expired/)() | 쿠키가 만료되었는지 여부를 나타내는 값을 가져옵니다. |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | ‘Expires’ 속성 값을 가져옵니다. |
| **bool** [get_HttpOnly](./get_httponly/)() const | ‘HttpOnly’ 속성 값을 가져옵니다. |
| [String](../../system/string/) [get_Name](./get_name/)() const | 쿠키의 이름을 가져옵니다. |
| [String](../../system/string/) [get_Path](./get_path/)() const | ‘Path’ 속성 값을 가져옵니다. |
| **bool** [get_Plain](./get_plain/)() const | 쿠키 사양이 ‘Plain’인지 여부를 나타내는 값을 반환합니다. |
| [String](../../system/string/) [get_Port](./get_port/)() const | ‘Port’ 속성 값을 가져옵니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | ‘Port’ 속성 값들의 컬렉션을 반환합니다. |
| **bool** [get_Secure](./get_secure/)() const | ‘Secure’ 속성 값을 가져옵니다. |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | 쿠키가 생성된 시간을 반환합니다. |
| [String](../../system/string/) [get_Value](./get_value/)() const | 쿠키의 값을 가져옵니다. |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | 쿠키 사양을 가져옵니다. |
| **int32_t** [get_Version](./get_version/)() const | ‘[Version](../../system/version/)’ 속성 값을 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 구현입니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 구현입니다. |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | 이 메서드는 다른 메서드에 의해 메서드 이름을 설정하기 위해 호출됩니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스인지 확인합니다. C# ‘is’ 연산자의 유사 구현입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문장의 잠금 기능을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 구현입니다. 사용자 정의 타입 복제를 가능하게 합니다. |
| [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체와 nullptr를 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | ‘Comment’ 속성 값을 설정합니다. |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | ‘CommentURL’ 속성 값을 설정합니다. |
| void [set_Discard](./set_discard/)(**bool**) | ‘Discard’ 속성 값을 설정합니다. |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | ‘Domain’ 속성 값을 설정합니다. |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | 도메인이 암시적인지 여부를 나타내는 값을 설정합니다. |
| void [set_Expired](./set_expired/)(**bool**) | 쿠키가 만료되었는지 여부를 나타내는 값을 설정합니다. |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | ‘Expires’ 속성 값을 설정합니다. |
| void [set_HttpOnly](./set_httponly/)(**bool**) | ‘HttpOnly’ 속성 값을 설정합니다. |
| void [set_Name](./set_name/)([String](../../system/string/)) | 쿠키 이름을 설정합니다. |
| void [set_Path](./set_path/)([String](../../system/string/)) | ‘Path’ 속성 값을 설정합니다. |
| void [set_Port](./set_port/)([String](../../system/string/)) | ‘Port’ 속성 값을 설정합니다. |
| void [set_Secure](./set_secure/)(**bool**) | ‘Secure’ 속성 값을 설정합니다. |
| void [set_Value](./set_value/)([String](../../system/string/)) | 쿠키 값을 설정합니다. |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | 쿠키 사양을 설정합니다. |
| void [set_Version](./set_version/)(**int32_t**) | ‘[Version](../../system/version/)’ 속성 값을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 강한 포인터가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | 현재 인스턴스를 문자열 표현으로 직렬화합니다. |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 구현입니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문장의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | 기본 속성 값을 확인하고 설정합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 필드

| 필드 | 설명 |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | ‘Comment’ 속성 이름입니다. |
| static [CommentUrlAttributeName](./commenturlattributename/) | ‘CommentURL’ 속성 이름입니다. |
| static [DiscardAttributeName](./discardattributename/) | ‘Discard’ 속성 이름입니다. |
| static [DomainAttributeName](./domainattributename/) | ‘Domain’ 속성 이름입니다. |
| static [EqualsLiteral](./equalsliteral/) | 속성의 이름과 값을 구분하는 데 사용되는 구분자입니다. |
| static [ExpiresAttributeName](./expiresattributename/) | ‘Expires’ 속성 이름입니다. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | ‘HttpOnly’ 속성 이름입니다. |
| static [MaxAgeAttributeName](./maxageattributename/) | ‘Max-Age’ 속성 이름입니다. |
| static [MaxSupportedVersion](./maxsupportedversion/) | 지원되는 최대 버전입니다. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | 지원되는 최대 버전의 문자열 표현입니다. |
| static [PathAttributeName](./pathattributename/) | ‘Path’ 속성 이름입니다. |
| static [PortAttributeName](./portattributename/) | ‘Port’ 속성 이름입니다. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | ‘Port’ 속성 값들의 구분자를 포함하는 배열입니다. |
| static [QuotesLiteral](./quotesliteral/) | 속성 부분을 감싸는 데 사용되는 기호입니다. |
| static [ReservedToName](./reservedtoname/) | 쿠키 이름에 예약된 값입니다. |
| static [ReservedToValue](./reservedtovalue/) | 쿠키 값에 예약된 값입니다. |
| static [SecureAttributeName](./secureattributename/) | ‘Secure’ 속성 이름입니다. |
| static [SeparatorLiteral](./separatorliteral/) | 속성 구분자입니다. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | 특수 속성 이름들의 접두사입니다. |
| static [VersionAttributeName](./versionattributename/) | ‘[Version](../../system/version/)’ 속성 이름입니다. |

## 참조

* 클래스 [Object](../../system/object/)
* 네임스페이스 [System::Net](../)
* 라이브러리 [Aspose.Slides](../../)