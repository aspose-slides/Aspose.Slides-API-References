---
title: JapaneseCalendar
second_title: Aspose.Slides for C++ API 레퍼런스
description: "일본 달력. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용해 이 타입의 인스턴스를 생성하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하십시오."
type: docs
weight: 183
url: /ko/system.globalization/japanesecalendar/
---
## JapaneseCalendar 클래스

Japanese calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class JapaneseCalendar : public System::Globalization::Calendar
```

## 메서드

| Method | Description |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | 시간 점에 일수를 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | 시간 점에 시간을 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | 시간 점에 밀리초를 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | 시간 점에 분을 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | 시간 점에 월을 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | 시간 점에 초를 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | 시간 점에 주를 추가합니다. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | 시간 점에 연도를 추가합니다. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI 정보. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | 현재 객체의 복사본을 만들고 shared pointer를 반환합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미론을 사용해 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따라 NaN은 어떤 값과도 같지 않지만, C# 스타일로 두 NaN을 동일하게 취급합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따라 NaN은 어떤 값과도 같지 않지만, C# 스타일로 두 NaN을 동일하게 취급합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 전용. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | 알고리즘 유형을 가져옵니다. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | 현재 연호의 인덱스를 가져옵니다. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | 현재 연호의 값을 가져옵니다. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | 달력에 존재하는 연호 목록을 가져옵니다. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | 달력이 읽기 전용인지 확인합니다. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | 달력이 지원하는 최대 시간점. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | 달리가 지원하는 최소 시간점. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | 2자리 연도로 표현 가능한 마지막 연도를 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | 지정된 시간점에 대한 월의 일을 가져옵니다. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | 지정된 시간점에 대한 요일을 가져옵니다. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | 지정된 시간점에 대한 연도의 일을 가져옵니다. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | 특정 월의 일 수를 가져옵니다. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | 특정 월의 일 수를 가져옵니다. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | 특정 월의 일 수를 가져옵니다. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | 특정 연도의 일 수를 가져옵니다. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | 특정 연도의 일 수를 가져옵니다. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | 특정 연도의 일 수를 가져옵니다. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | 지정된 시간점에 대한 연호를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사체. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | 지정된 시간점에 대한 시간을 가져옵니다. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | 지정된 연도의 윤달을 가져옵니다. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | 지정된 연도의 윤달을 가져옵니다. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | 지정된 연도의 윤달을 가져옵니다. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | 지정된 시간점에 대한 밀리초를 가져옵니다. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | 지정된 시간점에 대한 분을 가져옵니다. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | 지정된 시간점에 대한 월을 가져옵니다. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | 지정된 연도의 월 수를 가져옵니다. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI 정보. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | RTTI 정보. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | 지정된 시간점에 대한 초를 가져옵니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사체. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | 지정된 시간점에 대한 연도의 주를 가져옵니다. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | 지정된 시간점에 대한 연도를 가져옵니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자의 유사체. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | 해당 일이 윤년인지 확인합니다. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | 해당 일이 윤년인지 확인합니다. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | 해당 일이 윤년인지 확인합니다. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | 해당 월이 윤월인지 확인합니다. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | 해당 월이 윤월인지 확인합니다. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | 해당 월이 윤월인지 확인합니다. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | 해당 연도가 윤년인지 확인합니다. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | 해당 연도가 윤년인지 확인합니다. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | 해당 연도가 윤년인지 확인합니다. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | 연도, 월, 일 및 연호 값을 확인합니다. |
|  [JapaneseCalendar](./japanesecalendar/)() | 생성자. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사체. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않고, 새 객체를 초기화하고 서브클래스의 복사 구성을 가능하게 합니다. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무 것도 복사하지 않고, 새 객체를 초기화하고 서브클래스의 복사 구성을 가능하게 합니다. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | 읽기 전용 버전의 달력을 가져옵니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | 2자리 연도로 표현 가능한 마지막 연도를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유 대신)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | [DateTime](../../system/datetime/) 객체를 구성 요소에서 생성합니다. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) 객체를 구성 요소에서 생성합니다. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) 객체를 구성 요소에서 생성합니다. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | TwoDigitYearMax 속성을 사용하여 연도를 4자리 연도로 변환합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사체. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참고

* 클래스 [Calendar](../calendar/)
* 네임스페이스 [System::Globalization](../)
* 라이브러리 [Aspose.Slides](../../)