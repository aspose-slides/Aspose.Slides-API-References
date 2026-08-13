---
title: TimeZoneInfo
second_title: Aspose.Slides for C++ API 참조
description: "특정 시간대를 설명하는 정보를 나타냅니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 직접 인스턴스를 생성하거나 operator new를 사용하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 인수로 함수에 전달하십시오."
type: docs
weight: 1340
url: /ko/system/timezoneinfo/
---
## TimeZoneInfo 클래스

특정 시간대를 설명하는 정보를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하여 인스턴스를 만들면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../smartptr/) 포인터로 감싸고, 해당 포인터를 인수로 함수에 전달하십시오.

```cpp
class TimeZoneInfo : public System::IEquatable<TimeZoneInfoPtr>
```

## 메서드

| Method | Description |
| --- | --- |
| static void [ClearCachedData](./clearcacheddata/)() | 캐시된 시간대 데이터를 지웁니다. |
| static [DateTime](../datetime/) [ConvertTime](./converttime/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&, const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) 시간대를 한 시간대에서 다른 시간대로 변환합니다. |
| static [DateTimeOffset](../datetimeoffset/) [ConvertTime](./converttime/)(const [DateTimeOffset](../datetimeoffset/)\&, const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) 지정된 시간대의 시간으로 변환합니다. |
| static [DateTime](../datetime/) [ConvertTime](./converttime/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) 지정된 시간대의 시간으로 변환합니다. |
| static [DateTime](../datetime/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)([DateTime](../datetime/), const [String](../string/)\&) | [Convert](../convert/) 지정된 시간대의 시간으로 변환합니다. |
| static [DateTimeOffset](../datetimeoffset/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)(const [DateTimeOffset](../datetimeoffset/)\&, const [String](../string/)\&) | [Convert](../convert/) 지정된 시간대의 시간으로 변환합니다. |
| static [DateTime](../datetime/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)([DateTime](../datetime/), const [String](../string/)\&, const [String](../string/)\&) | [Convert](../convert/) 지정된 시간대의 시간으로 변환합니다. |
| static [DateTime](../datetime/) [ConvertTimeFromUtc](./converttimefromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | UTC 시간을 지정된 시간대의 시간으로 변환합니다. |
| static [DateTime](../datetime/) [ConvertTimeToUtc](./converttimetoutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | 시간을 UTC 시간으로 변환합니다. |
| static [DateTime](../datetime/) [ConvertTimeToUtc](./converttimetoutc/)([DateTime](../datetime/)) | 시간을 UTC 시간으로 변환합니다. |
| static [DateTime](../datetime/) [ConvertTimeToUtcNoThrow](./converttimetoutcnothrow/)([DateTime](../datetime/)) | 시간을 UTC 시간으로 변환합니다. 내부 사용 전용. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&, const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\>\&, **bool**) | 사용자 정의 시간대를 생성합니다. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&, const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\>\&) | 사용자 정의 시간대를 생성합니다. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&) | 사용자 정의 시간대를 생성합니다. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override |  |
| **bool** [Equals](./equals/)([TimeZoneInfoPtr](../timezoneinfoptr/)) override | 현재 객체와 지정된 객체가 같은지 판단합니다. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) 의미를 사용해 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 IEC 60559:1989에 따라 어떤 값과도 같지 않음에도 불구하고 C# 스타일 부동소수점 비교를 에뮬레이트하여 NaN을 서로 같다고 간주합니다. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 IEC 60559:1989에 따라 어떤 값과도 같지 않음에도 불구하고 C# 스타일 부동소수점 비교를 에뮬레이트하여 NaN을 서로 같다고 간주합니다. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [FindSystemTimeZoneById](./findsystemtimezonebyid/)(const [String](../string/)\&) | 지정된 식별자를 가진 시간대를 가져옵니다. |
| [TimeSpan](../timespan/) [get_BaseUtcOffset](./get_baseutcoffset/)() const | 현재 시간대의 표준 시간과 UTC 시간 사이의 시간 간격을 나타내는 [TimeSpan](../timespan/) 인스턴스를 반환합니다. |
| [String](../string/) [get_DaylightName](./get_daylightname/)() const | 현재 시간대의 일광 절약 시간 이름을 가져옵니다. |
| [String](../string/) [get_DisplayName](./get_displayname/)() const | 현재 시간대의 이름을 가져옵니다. |
| [String](../string/) [get_Id](./get_id/)() const | 현재 객체가 나타내는 시간대의 식별자를 반환합니다. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [get_Local](./get_local/)() | 로컬 시간대를 나타내는 [TimeZoneInfo](./) 인스턴스를 반환합니다. |
| [String](../string/) [get_StandardName](./get_standardname/)() const | 현재 시간대의 표준 시간 이름을 가져옵니다. |
| **bool** [get_SupportsDaylightSavingTime](./get_supportsdaylightsavingtime/)() const | 시간대에 일광 절약 시간 규칙이 있는지 나타내는 플래그를 가져옵니다. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [get_Utc](./get_utc/)() | UTC 시간대를 나타내는 [TimeZoneInfo](./) 인스턴스를 반환합니다. |
| [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\> [GetAdjustmentRules](./getadjustmentrules/)() const | 현재 [TimeZoneInfo](./) 객체에 적용되는 조정 규칙을 나타내는 **AdjustmentRule** 객체 배열을 반환합니다. |
| [ArrayPtr](../arrayptr/)\<[TimeSpan](../timespan/)\> [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)([DateTime](../datetime/)) const | 지정된 날짜와 시간이 매핑될 수 있는 UTC 날짜와 시간을 가져옵니다. |
| [ArrayPtr](../arrayptr/)\<[TimeSpan](../timespan/)\> [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)(const [DateTimeOffset](../datetimeoffset/)\&) const | 지정된 날짜와 시간이 매핑될 수 있는 UTC 날짜와 시간을 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| int [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해시를 가능하게 합니다. |
| static [SharedPtr](../sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[TimeZoneInfoPtr](../timezoneinfoptr/)\>\> [GetSystemTimeZones](./getsystemtimezones/)() | 로컬 시스템에서 사용할 수 있는 모든 시간대의 정렬된 컬렉션을 가져옵니다. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../object/gettype/) 호출과 유사합니다. |
| [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)([DateTime](../datetime/)) const | 지정된 날짜와 시간에 대해 이 시간대와 UTC 시간대 사이의 차이를 계산합니다. |
| [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)(const [DateTimeOffset](../datetimeoffset/)\&) const | 지정된 날짜와 시간에 대해 이 시간대와 UTC 시간대 사이의 차이를 계산합니다. |
| static [TimeSpan](../timespan/) [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | 지정된 시간대의 UTC 날짜시간에 대한 UTC 오프셋을 반환하는 내부 헬퍼 함수입니다. 내부 사용 전용. |
| static [TimeSpan](../timespan/) [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&, **bool**\&, **bool**\&) | 지정된 시간대의 UTC 날짜시간에 대한 UTC 오프셋을 반환하는 내부 헬퍼 함수입니다. 내부 사용 전용. |
| [TimeSpan](../timespan/) [GetUtcOffsetNoThrow](./getutcoffsetnothrow/)([DateTime](../datetime/)) const | 지정된 날짜와 시간에 대해 이 시간대와 UTC 시간대 사이의 차이를 계산합니다. 내부 사용 전용. |
| **bool** [HasSameRules](./hassamerules/)(const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) const | 현재와 다른 시간대가 동일한 조정 규칙을 가지고 있는지 확인합니다. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| **bool** [IsAmbiguousTime](./isambiguoustime/)([DateTime](../datetime/)) const | 지정된 날짜와 시간이 모호하여 여러 UTC 시간에 매핑될 수 있는지 확인합니다. |
| **bool** [IsAmbiguousTime](./isambiguoustime/)(const [DateTimeOffset](../datetimeoffset/)\&) const | 지정된 날짜와 시간이 모호하여 여러 UTC 시간에 매핑될 수 있는지 확인합니다. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)([DateTime](../datetime/)) const | 지정된 날짜와 시간이 일광 절약 시간 범위에 속하는지 확인합니다. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)(const [DateTimeOffset](../datetimeoffset/)\&) const | 지정된 날짜와 시간이 일광 절약 시간 범위에 속하는지 확인합니다. |
| **bool** [IsDaylightSavingTimeNoThrow](./isdaylightsavingtimenothrow/)([DateTime](../datetime/)) const | 지정된 날짜와 시간이 일광 절약 시간 범위에 속하는지 확인합니다. |
| **bool** [IsInvalidTime](./isinvalidtime/)([DateTime](../datetime/)) const | 지정된 날짜와 시간이 올바르지 않은지 확인합니다. |
| void [Lock](../object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용합니다. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../object/object/)([Object](../object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 할당 연산자. 실제로 아무것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있게 합니다. |
| int [SharedCount](../object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| [String](../string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static [DateTime](../datetime/) [TransitionTimeToDateTime](./transitiontimetodatetime/)(**int32_t**, const **TransitionTime**\&) | 연도와 **TransitionTime**을 [DateTime](../datetime/) 로 변환하는 도우미 함수입니다. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) 구문을 구현합니다. |
| void [Unlock](../object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 타입정의

| Typedef | Description |
| --- | --- |
| [AdjustmentRulePtr](./adjustmentruleptr/) | **AdjustmentRule** 클래스 인스턴스에 대한 공유 포인터 별칭입니다. |

## 보기

* 클래스 [IEquatable](../iequatable/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)