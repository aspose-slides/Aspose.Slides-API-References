---
title: Calendar
second_title: Aspose.Slides for C++ API 레퍼런스
description: "날짜가 처리되고, 계산되고, 포맷되는 방식을 정의하는 Calendar. Setter 작업은 읽기 전용이 아닌 객체에서만 사용할 수 있습니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용해 이 유형의 인스턴스를 생성하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 이 포인터를 함수 인자로 전달하십시오."
type: docs
weight: 1
url: /ko/system.globalization/calendar/
---
## Calendar 클래스

[Calendar](./)은(는) 날짜가 처리되고, 계산되고, 포맷되는 방식을 정의합니다. Setter 작업은 읽기 전용이 아닌 객체에서만 허용됩니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용해 이 타입의 인스턴스를 생성하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 이 포인터를 함수 인자로 전달하십시오.

```cpp
class Calendar : public System::ICloneable
```

## 메서드

| Method | Description |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](./adddays/)([DateTime](../../system/datetime/), int) const | 시간 포인트에 일수를 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddHours](./addhours/)([DateTime](../../system/datetime/), int) const | 시간 포인트에 시간을 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](./addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | 시간 포인트에 밀리초를 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](./addminutes/)([DateTime](../../system/datetime/), int) const | 시간 포인트에 분을 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddMonths](./addmonths/)([DateTime](../../system/datetime/), int) const | 시간 포인트에 월을 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](./addseconds/)([DateTime](../../system/datetime/), int) const | 시간 포인트에 초를 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](./addweeks/)([DateTime](../../system/datetime/), int) const | 시간 포인트에 주를 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddYears](./addyears/)([DateTime](../../system/datetime/), int) const | 시간 포인트에 연도를 추가합니다. |
|  [Calendar](./calendar/)(const [Calendar](./)\&) | RTTI 정보. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | 현재 객체의 복사본을 생성하고 공유 포인터를 반환합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# 스타일의 부동 소수점 비교를 흉내 내어, IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# 스타일의 부동 소수점 비교를 흉내 내어, IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용. |
| virtual [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const | 알고리즘 유형을 가져옵니다. |
| int [get_CurrentEra](./get_currentera/)() const | 현재 시대의 인덱스를 가져옵니다. |
| int [get_CurrentEraValue](./get_currenteravalue/)() const | 현재 시대의 값을 가져옵니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const | 캘린더에 존재하는 시대 목록을 가져옵니다. |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](./get_id/)() const | 캘린더 식별자를 가져옵니다. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | 캘린더가 읽기 전용인지 확인합니다. |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const | 캘린더가 지원하는 최대 시간 지점. |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const | 캘린더가 지원하는 최소 시간 지점. |
| virtual int [get_TwoDigitYearMax](./get_twodigityearmax/)() const | 2자리 연도로 표현할 수 있는 마지막 연도를 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const | 지정된 시간 포인트에 대한 월의 일을 가져옵니다. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const | 지정된 시간 포인트에 대한 요일을 가져옵니다. |
| virtual int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const | 지정된 시간 포인트에 대한 연중 일을 가져옵니다. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | 특정 월의 일 수를 가져옵니다. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | 특정 월의 일 수를 가져옵니다. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | 특정 연도의 일 수를 가져옵니다. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | 특정 연도의 일 수를 가져옵니다. |
| virtual int [GetEra](./getera/)([DateTime](../../system/datetime/)) const | 지정된 시간 포인트에 대한 시대를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 커스텀 객체의 해싱을 가능하게 합니다. |
| virtual int [GetHour](./gethour/)([DateTime](../../system/datetime/)) const | 지정된 시간 포인트에 대한 시간을 가져옵니다. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | 지정된 연도에 대한 윤달을 가져옵니다. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | 지정된 연도에 대한 윤달을 가져옵니다. |
| virtual **double** [GetMilliseconds](./getmilliseconds/)([DateTime](../../system/datetime/)) const | 지정된 시간 포인트에 대한 밀리초를 가져옵니다. |
| virtual int [GetMinute](./getminute/)([DateTime](../../system/datetime/)) const | 지정된 시간 포인트에 대한 분을 가져옵니다. |
| virtual int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const | 지정된 시간 포인트에 대한 월을 가져옵니다. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | 지정된 연도에 대한 월 수를 가져옵니다. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | 지정된 연도에 대한 월 수를 가져옵니다. |
| virtual int [GetSecond](./getsecond/)([DateTime](../../system/datetime/)) const | 지정된 시간 포인트에 대한 초를 가져옵니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual int [GetWeekOfYear](./getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | 지정된 시간 포인트에 대한 연중 주를 가져옵니다. |
| virtual int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const | 지정된 시간 포인트에 대한 연도를 가져옵니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | 날이 윤일인지 확인합니다. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | 날이 윤일인지 확인합니다. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | 월이 윤달인지 확인합니다. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | 월이 윤달인지 확인합니다. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | 년이 윤년인지 확인합니다. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | 년이 윤년인지 확인합니다. |
| **bool** [IsValidDay](./isvalidday/)(int, int, int, int) const | 연도, 월, 일 및 시대 값을 확인합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 커스텀 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Calendar](./)\& [operator=](./operator_equal/)(const [Calendar](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](./readonly/)(const [CalendarPtr](../calendarptr/)\&) | 캘린더의 읽기 전용 버전을 가져옵니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [set_TwoDigitYearMax](./set_twodigityearmax/)(int) | 2자리 연도로 표현할 수 있는 마지막 연도를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유 포인터가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) 객체를 구성 요소로부터 생성합니다. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) 객체를 구성 요소로부터 생성합니다. |
| virtual int [ToFourDigitYear](./tofourdigityear/)(int) const | TwoDigitYearMax 속성을 사용하여 연도를 4자리 연도로 변환합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 커스텀 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 관련 항목

* 클래스 [ICloneable](../../system/icloneable/)
* 네임스페이스 [System::Globalization](../)
* 라이브러리 [Aspose.Slides](../../)