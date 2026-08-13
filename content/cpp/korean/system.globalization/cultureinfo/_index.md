---
title: CultureInfo
second_title: Aspose.Slides for C++ API 참조
description: "문화별 값과 알고리즘의 모음입니다. Setter 연산은 읽기 전용이 아닌 객체에서만 사용할 수 있습니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용해서만 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용해 인스턴스를 만들면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하십시오."
type: docs
weight: 53
url: /ko/system.globalization/cultureinfo/
---
## CultureInfo 클래스

Collection of culture-specific values and algorithms. Setter operations are only enabled on non-read-only objects. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CultureInfo : public virtual System::Object,
                    public System::IFormatProvider,
                    public System::ICloneable
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| void [ClearCachedData](./clearcacheddata/)() | 캐시된 문화 정보를 새로 고칩니다. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | 문화 정보를 복제합니다. |
| static [CultureInfoPtr](../cultureinfoptr/) [CreateSpecificCulture](./createspecificculture/)(const [String](../../system/string/)\&) | 이름으로 문화를 생성합니다. |
| explicit  [CultureInfo](./cultureinfo/)(int) | RTTI 정보 |
|  [CultureInfo](./cultureinfo/)(int, **bool**) | 생성자. |
| explicit  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&) | 생성자. |
|  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&, **bool**) | 생성자. |
|  [CultureInfo](./cultureinfo/)(std::nullptr_t) | 항상 ArgumentNullException을 throw합니다. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 객체를 비교합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 동일하게 취급되는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 여기서는 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 동일하게 취급되는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 여기서는 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용. |
| virtual [CalendarPtr](../calendarptr/) [get_Calendar](./get_calendar/)() const | 문화에서 사용하는 달력을 가져옵니다. |
| virtual [CompareInfoPtr](../compareinfoptr/) [get_CompareInfo](./get_compareinfo/)() const | 문화 규칙을 따르는 문자열 비교자를 가져옵니다. |
| [CultureTypes](../culturetypes/) [get_CultureTypes](./get_culturetypes/)() const | 현재 문화를 설명하는 문화 유형들의 비트 연산 결과를 가져옵니다. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentCulture](./get_currentculture/)() | 현재 스레드에 설정된 문화를 가져옵니다. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentUICulture](./get_currentuiculture/)() | 현재 스레드의 UI 문화를 가져옵니다. |
| virtual [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_DateTimeFormat](./get_datetimeformat/)() const | 날짜 형식 정보를 가져옵니다. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentCulture](./get_defaultthreadcurrentculture/)() | 현재 애플리케이션 도메인에서 기본 문화를 가져옵니다. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentUICulture](./get_defaultthreadcurrentuiculture/)() | 현재 애플리케이션 도메인에서 기본 UI 문화를 가져옵니다. |
| virtual [String](../../system/string/) [get_DisplayName](./get_displayname/)() const | 문화 표시 이름을 가져옵니다. |
| virtual [String](../../system/string/) [get_EnglishName](./get_englishname/)() const | 문화의 영문 이름을 가져옵니다. |
| [String](../../system/string/) [get_IetfLanguageTag](./get_ietflanguagetag/)() const | 언어의 RFC 4646 이름을 가져옵니다. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InstalledUICulture](./get_installeduiculture/)() | 운영 체제에 설치된 문화를 가져옵니다. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InvariantCulture](./get_invariantculture/)() | 불변 문화를 가져옵니다. |
| virtual **bool** [get_IsNeutralCulture](./get_isneutralculture/)() const | 문화가 중립인지 확인합니다. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | 문화 객체가 읽기 전용인지 확인합니다. |
| virtual int [get_KeyboardLayoutId](./get_keyboardlayoutid/)() const | 활성 입력 로케일 식별자를 가져옵니다. |
| virtual int [get_LCID](./get_lcid/)() const | 문화 식별자를 가져옵니다. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | 문화 이름을 가져옵니다. |
| virtual [String](../../system/string/) [get_NativeName](./get_nativename/)() const | 문화의 고유 이름을 가져옵니다. |
| virtual [NumberFormatInfoPtr](../numberformatinfoptr/) [get_NumberFormat](./get_numberformat/)() const | 숫자 형식 정보를 가져옵니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[CalendarPtr](../calendarptr/)\> [get_OptionalCalendars](./get_optionalcalendars/)() const | 문화와 함께 사용할 수 있는 달력 목록을 반환합니다. |
| virtual [CultureInfoPtr](../cultureinfoptr/) [get_Parent](./get_parent/)() const | 부모 문화를 가져옵니다. |
| virtual [TextInfoPtr](../textinfoptr/) [get_TextInfo](./get_textinfo/)() const | 문화에서 사용하는 텍스트 매개변수를 가져옵니다. |
| virtual [String](../../system/string/) [get_ThreeLetterISOLanguageName](./get_threeletterisolanguagename/)() const | ISO 639-2 3자리 언어 코드를 가져옵니다. |
| virtual [String](../../system/string/) [get_ThreeLetterWindowsLanguageName](./get_threeletterwindowslanguagename/)() const | [Windows](../../system.windows/) API에 정의된 언어의 3자리 코드를 가져옵니다. |
| virtual [String](../../system/string/) [get_TwoLetterISOLanguageName](./get_twoletterisolanguagename/)() const | 문화와 관련된 ISO 2자리 언어 이름을 가져옵니다. |
| **bool** [get_UseUserOverride](./get_useuseroverride/)() const | [CultureInfo](./)가 사용자 선택 문화 설정을 사용하는지 여부를 나타내는 플래그를 가져옵니다. |
| [CultureInfoPtr](../cultureinfoptr/) [GetConsoleFallbackUICulture](./getconsolefallbackuiculture/)() const | 콘솔 애플리케이션에 적합한 대체 문화를 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&) | 이름으로 문화를 가져옵니다. CreateSpecificCulture와 동일합니다. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 이름으로 문화를 가져옵니다. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(**int32_t**) | ID로 문화를 가져옵니다. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfoByIetfLanguageTag](./getcultureinfobyietflanguagetag/)(const [String](../../system/string/)\&) | 사용 중단됨. 지정된 RFC 4646 언어 태그로 읽기 전용 [CultureInfo](./) 객체를 가져옵니다. |
| static [ArrayPtr](../../system/arrayptr/)\<[CultureInfoPtr](../cultureinfoptr/)\> [GetCultures](./getcultures/)([CultureTypes](../culturetypes/)) | 지정된 유형에 해당하는 문화를 가져옵니다. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | 특정 유형에 대한 포맷 객체를 가져옵니다. |
| int [GetHashCode](./gethashcode/)() const override | 객체 해시 코드를 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| **bool** [IsInherited](./isinherited/)() const | 상속 여부 플래그를 가져옵니다. 내부 전용. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스의 복사 생성을 가능하게 합니다. |
| [CultureInfo](./)\& [operator=](./operator_equal/)(const [CultureInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스의 복사 생성을 가능하게 합니다. |
| **bool** [operator==](./operator_equal_equal/)(const [CultureInfo](./)\&) const | 문화 매개변수를 비교합니다. |
| static [CultureInfoPtr](../cultureinfoptr/) [ReadOnly](./readonly/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | 읽기 전용 문화 버전을 가져옵니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| static void [set_CurrentCulture](./set_currentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | 현재 스레드의 문화를 설정합니다. |
| static void [set_CurrentUICulture](./set_currentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | 현재 스레드의 UI 문화를 설정합니다. |
| virtual void [set_DateTimeFormat](./set_datetimeformat/)([DateTimeFormatInfoPtr](../datetimeformatinfoptr/)) | 날짜 형식 정보를 설정합니다. |
| static void [set_DefaultThreadCurrentCulture](./set_defaultthreadcurrentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | 현재 애플리케이션 도메인에서 기본 문화를 설정합니다. |
| static void [set_DefaultThreadCurrentUICulture](./set_defaultthreadcurrentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | 현재 애플리케이션 도메인에서 기본 UI 문화를 설정합니다. |
| virtual void [set_NumberFormat](./set_numberformat/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | 숫자 형식 정보를 가져옵니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유 포인터가 아니라)로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하면 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| [String](../../system/string/) [ToString](./tostring/)() const override | 문화를 문자열로 변환합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문장의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하면 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [Object](../../system/object/)
* 클래스 [IFormatProvider](../../system/iformatprovider/)
* 클래스 [ICloneable](../../system/icloneable/)
* 네임스페이스 [System::Globalization](../)
* 라이브러리 [Aspose.Slides](../../)