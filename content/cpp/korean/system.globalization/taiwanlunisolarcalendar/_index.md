---
title: TaiwanLunisolarCalendar
second_title: Aspose.Slides for C++ API 참조
description: "대만 음양력 달력. 구현되지 않았습니다. 이 클래스의 객체는 System::MakeObject() 함수로만 할당해야 합니다. 스택에 이 유형의 인스턴스를 생성하거나 operator new를 사용하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 래핑하고 해당 포인터를 함수 인수로 전달하십시오."
type: docs
weight: 339
url: /ko/system.globalization/taiwanlunisolarcalendar/
---
## TaiwanLunisolarCalendar 클래스

Taiwan lunisolar calendar. Not implemented. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TaiwanLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | 시간 지점에 일수를 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | 시간 지점에 시간을 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | 시간 지점에 밀리초를 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | 시간 지점에 분을 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | 시간 지점에 월을 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | 시간 지점에 초를 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | 시간 지점에 주를 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | 시간 지점에 연도를 추가합니다. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI 정보. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | 현재 객체의 복사본을 만들고 그에 대한 공유 포인터를 반환합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 취급하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 취급하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](../eastasianlunisolarcalendar/get_algorithmtype/)() const override | RTTI 정보. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | 현재 시대의 인덱스를 반환합니다. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | 현재 시대의 값을 반환합니다. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | 달력에 존재하는 시대 목록을 반환합니다. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | 달력이 읽기 전용인지 확인합니다. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | 달리가 지원하는 최대 시간 지점. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | 달기가 지원하는 최소 시간 지점. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | 2자리 연도로 표현할 수 있는 마지막 연도를 반환합니다. |
| int [GetCelestialStem](../eastasianlunisolarcalendar/getcelestialstem/)(int) const | 천간을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 반환합니다. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | 지정된 시간 지점의 월 일자를 반환합니다. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | 지정된 시간 지점의 요일을 반환합니다. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | 지정된 시간 지점의 연 일자를 반환합니다. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | 특정 월의 일 수를 반환합니다. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | 특정 월의 일 수를 반환합니다. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | 특정 월의 일 수를 반환합니다. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | 특정 연도의 일 수를 반환합니다. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | 특정 연도의 일 수를 반환합니다. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | 지정된 시간 지점의 시대를 반환합니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | 지정된 시간 지점의 시간을 반환합니다. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | 지정된 연도의 윤달을 반환합니다. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | 지정된 연도의 윤달을 반환합니다. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | 지정된 연도의 윤달을 반환합니다. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | 지정된 시간 지점의 밀리초를 반환합니다. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | 지정된 시간 지점의 분을 반환합니다. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | 지정된 시간 지점의 월을 반환합니다. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | 지정된 연도의 월 수를 반환합니다. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI 정보. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | RTTI 정보. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | 지정된 시간 지점의 초를 반환합니다. |
| virtual int [GetSexagenaryYear](../eastasianlunisolarcalendar/getsexagenaryyear/)([DateTime](../../system/datetime/)) const | 육십갑자 주기의 연도를 반환합니다. |
| int [GetTerrestrialBranch](../eastasianlunisolarcalendar/getterrestrialbranch/)(int) const | 지지를 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 반환합니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | 지정된 시간 지점의 연 주를 반환합니다. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | 지정된 시간 지점의 연도를 반환합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | 해당일이 윤일인지 확인합니다. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | 해당일이 윤일인지 확인합니다. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | 해당일이 윤일인지 확인합니다. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | 해당월이 윤월인지 확인합니다. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | 해당월이 윤월인지 확인합니다. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | 해당연도가 윤년인지 확인합니다. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | 해당연도가 윤년인지 확인합니다. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | 해당연도가 윤년인지 확인합니다. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | 연도, 월, 일 및 시대 값을 확인합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | 읽기 전용 버전의 달력을 반환합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 따라 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 따라 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | 2자리 연도로 표현할 수 있는 마지막 연도를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있게 합니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운트 값을 반환합니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하세요. |
|  [TaiwanLunisolarCalendar](./taiwanlunisolarcalendar/)() | 생성자. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) 객체를 구성 요소에서 생성합니다. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) 객체를 구성 요소에서 생성합니다. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | TwoDigitYearMax 속성을 사용하여 연도를 4자리 연도로 변환합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참고

* 클래스 [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* 네임스페이스 [System::Globalization](../)
* 라이브러리 [Aspose.Slides](../../)