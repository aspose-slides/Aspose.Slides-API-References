---
title: EastAsianLunisolarCalendar
second_title: Aspose.Slides for C++ API 레퍼런스
description: "동아시아 음양력 달력. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 이 타입의 인스턴스를 생성하거나 operator new를 사용하지 마십시오. 이렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고 이 포인터를 인수로 함수에 전달하십시오."
type: docs
weight: 105
url: /ko/system.globalization/eastasianlunisolarcalendar/
---
## EastAsianLunisolarCalendar 클래스

동아시아 음양력 달력. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 이 타입의 인스턴스를 생성하거나 operator new를 사용하여 생성하지 마십시오. 이렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고 이 포인터를 인수로 함수에 전달하십시오.

```cpp
class EastAsianLunisolarCalendar : public System::Globalization::Calendar
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | 시간 지점에 일을 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | 시간 지점에 시간을 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | 시간 지점에 밀리초를 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | 시간 지점에 분을 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | 시간 지점에 달을 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | 시간 지점에 초를 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | 시간 지점에 주를 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | 시간 지점에 연도를 추가합니다. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI 정보. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | 현재 객체의 복사본을 만들고 shared 포인터를 반환합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 IEC 60559:1989에 따라 어떤 값과도 같지 않음에도 C# 스타일 부동소수점 비교를 에뮬레이션하여 두 NaN이 동일하다고 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 IEC 60559:1989에 따라 어떤 값과도 같지 않음에도 C# 스타일 부동소수점 비교를 에뮬레이션하여 두 NaN이 동일하다고 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | RTTI 정보. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | 현재 시대의 인덱스를 가져옵니다. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | 현재 시대의 값을 가져옵니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](../calendar/get_eras/)() const | 달력에 존재하는 시대 목록을 가져옵니다. |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](../calendar/get_id/)() const | 달력 식별자를 가져옵니다. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | 달력이 읽기 전용인지 확인합니다. |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](../calendar/get_maxsupporteddatetime/)() const | 달리가 지원하는 최대 시간 지점입니다. |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](../calendar/get_minsupporteddatetime/)() const | 달리가 지원하는 최소 시간 지점입니다. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | 2자리로 표현할 수 있는 마지막 연도를 가져옵니다. |
| int [GetCelestialStem](./getcelestialstem/)(int) const | 천간을 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | 지정된 시간 지점의 월 일을 가져옵니다. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | 지정된 시간 지점의 요일을 가져옵니다. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | 지정된 시간 지점의 연일을 가져옵니다. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | 특정 월의 일 수를 가져옵니다. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | 특정 월의 일 수를 가져옵니다. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | 특정 년도의 일 수를 가져옵니다. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | 특정 년도의 일 수를 가져옵니다. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | 지정된 시간 지점의 시대를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | 지정된 시간 지점의 시간을 가져옵니다. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int) const | 지정된 연도의 윤달을 가져옵니다. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int, int) const | 지정된 연도의 윤달을 가져옵니다. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | 지정된 시간 지점의 밀리초를 가져옵니다. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | 지정된 시간 지점의 분을 가져옵니다. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | 지정된 시간 지점의 월을 가져옵니다. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | 지정된 연도의 월 수를 가져옵니다. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | 지정된 연도의 월 수를 가져옵니다. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | 지정된 시간 지점의 초를 가져옵니다. |
| virtual int [GetSexagenaryYear](./getsexagenaryyear/)([DateTime](../../system/datetime/)) const | 육십갑자 주기의 연도를 가져옵니다. |
| int [GetTerrestrialBranch](./getterrestrialbranch/)(int) const | 지지(지구지)를 가져옵니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | 지정된 시간 지점의 연주(주)를 가져옵니다. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | 지정된 시간 지점의 연도를 가져옵니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int) const | 해당 일이 윤일인지 확인합니다. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int, int) const | 해당 일이 윤일인지 확인합니다. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | 해당 월이 윤달인지 확인합니다. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | 해당 월이 윤달인지 확인합니다. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int) const | 해당 연도가 윤년인지 확인합니다. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int, int) const | 해당 연도가 윤년인지 확인합니다. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | 연도, 월, 일 및 시대 값을 확인합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않으며 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | 읽기 전용 버전의 달력을 가져옵니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr와 레퍼런스 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | 2자리로 표현할 수 있는 마지막 연도를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 weak 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 weak 모드로 전환할 수 있게 합니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) 객체를 구성 요소로부터 생성합니다. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) 객체를 구성 요소로부터 생성합니다. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | TwoDigitYearMax 속성을 사용해 연도를 4자리 연도로 변환합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Weak 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Weak 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [Calendar](../calendar/)
* 네임스페이스 [System::Globalization](../)
* 라이브러리 [Aspose.Slides](../../)