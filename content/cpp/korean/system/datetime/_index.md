---
title: DateTime
second_title: Aspose.Slides for C++ API 레퍼런스
description: "시간 연속선에서 특정 날짜와 시간 값을 나타냅니다. 이 타입은 스택에 할당하고 값이나 참조로 함수에 전달해야 합니다. 이 타입의 객체를 관리하기 위해 System::SmartPtr 클래스를 사용하지 마세요."
type: docs
weight: 222
url: /ko/system/datetime/
---
## DateTime 클래스

Represents a specific date and time value on the time continuum. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class DateTime
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | 지정된 시간 간격을 현재 객체가 나타내는 날짜 및 시간 값에 추가한 결과인 날짜 및 시간 값을 나타내는 [DateTime](./) 클래스의 새 인스턴스를 반환합니다. |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | 현재 객체가 나타내는 값과 지정된 일 수를 합한 날짜 및 시간 값을 나타내는 [DateTime](./) 클래스의 새 인스턴스를 반환합니다. |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | 현재 객체가 나타내는 값과 지정된 시간 수를 합한 날짜 및 시간 값을 나타내는 [DateTime](./) 클래스의 새 인스턴스를 반환합니다. |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | 현재 객체가 나타내는 값과 지정된 밀리초 수를 합한 날짜 및 시간 값을 나타내는 [DateTime](./) 클래스의 새 인스턴스를 반환합니다. |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | 현재 객체가 나타내는 값과 지정된 분 수를 합한 날짜 및 시간 값을 나타내는 [DateTime](./) 클래스의 새 인스턴스를 반환합니다. |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | 현재 객체가 나타내는 값과 지정된 개월 수를 합한 날짜 및 시간 값을 나타내는 [DateTime](./) 클래스의 새 인스턴스를 반환합니다. |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | 현재 객체가 나타내는 값과 지정된 초 수를 합한 날짜 및 시간 값을 나타내는 [DateTime](./) 클래스의 새 인스턴스를 반환합니다. |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | 현재 객체가 나타내는 값과 지정된 100나노초 간격 수를 합한 날짜 및 시간 값을 나타내는 [DateTime](./) 클래스의 새 인스턴스를 반환합니다. |
| [DateTime](./) [AddYears](./addyears/)(int) const | 현재 객체가 나타내는 날짜 및 시간 값에 연도 구성 요소를 지정된 수만큼 증가시킨 값과 동일한 날짜 및 시간 값을 나타내는 [DateTime](./) 클래스의 새 인스턴스를 반환합니다. |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | [DateTime](./) 클래스의 지정된 인스턴스가 나타내는 두 값을 비교하고 시간선에서 값들의 상대 위치를 나타내는 값을 반환합니다. |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | 현재 객체와 [DateTime](./) 클래스의 지정된 인스턴스가 나타내는 두 날짜 및 시간 값을 비교하고 시간선에서 값들의 상대 위치를 나타내는 값을 반환합니다. |
| constexpr [DateTime](./datetime/)() | MinValue와 동일한 가장 작은 가능한 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다. |
|  [DateTime](./datetime/)(int, int, int) | 특정 연도, 월, 일로 지정된 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다. |
|  [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | 지정된 달력에서 특정 연도, 월, 일로 지정된 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다. |
|  [DateTime](./datetime/)(int, int, int, int, int, int) | 특정 연도, 월, 일, 시, 분, 초로 지정된 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | 특정 연도, 월, 일, 시, 분, 초로 지정된 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | 지정된 달력에서 특정 연도, 월, 일, 시, 분, 초로 지정된 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | 특정 연도, 월, 일, 시, 분, 초 및 밀리초로 지정된 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | 지정된 달력에서 특정 연도, 월, 일, 시, 분, 초 및 밀리초로 지정된 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | 틱 수로 지정된 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | 틱 수로 지정된 날짜 및 시간 값을 나타내는 인스턴스를 생성합니다. 내부 사용 전용. |
|  [DateTime](./datetime/)(const [DateTime](./)\&) | 인스턴스를 복사 생성합니다. |
| static int [DaysInMonth](./daysinmonth/)(int, int) | 지정된 연도의 지정된 월에 포함된 일 수를 반환합니다. |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | [DateTime](./) 클래스의 지정된 인스턴스가 동일한 날짜 및 시간 값을 나타내는지 확인합니다. |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | [DateTime](./) 클래스의 지정된 인스턴스가 현재 객체와 동일한 날짜 및 시간 값을 나타내는지 확인합니다. |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | 지정된 부호 없는 64비트 정수에서 날짜 시간 값을 역직렬화하고 [DateTime](./) 클래스의 새 인스턴스를 해당 값으로 설정합니다. |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | 지정된 파일 시간을 로컬 시간과 동일한 날짜 및 시간 값을 나타내는 [DateTime](./) 클래스의 인스턴스로 변환합니다. |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | 지정된 파일 시간을 UTC 시간과 동일한 날짜 및 시간 값을 나타내는 [DateTime](./) 클래스의 인스턴스로 변환합니다. |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | 지정된 OLE Automation 날짜와 동등한 날짜 및 시간 값을 나타내는 [DateTime](./) 클래스의 인스턴스를 반환합니다. |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | 지정된 유닉스 시간 값을 [DateTime](./) 클래스의 인스턴스로 변환합니다. 내부 사용 전용. |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | 현재 객체가 나타내는 날짜 및 시간 중 날짜 부분만을 나타내고 시간 부분의 각 구성 요소를 0으로 설정한 [DateTime](./) 클래스의 새 인스턴스를 반환합니다. |
| int [get_Day](./get_day/)() const | 현재 객체가 나타내는 월에서 일의 순서를 반환합니다. |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | 현재 객체가 나타내는 요일을 나타내는 값을 반환합니다. |
| int [get_DayOfYear](./get_dayofyear/)() const | 현재 객체가 나타내는 연도에서 일의 순서를 반환합니다. |
| constexpr int [get_Hour](./get_hour/)() const | 현재 객체가 나타내는 날짜 및 시간 값의 시 구성 요소를 반환합니다. |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | 현재 객체가 나타내는 날짜 및 시간이 로컬인지 UTC인지, 혹은 둘 다 아닌지를 나타내는 값을 반환합니다. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | 현재 객체가 나타내는 날짜 및 시간 값의 밀리초 구성 요소를 반환합니다. |
| constexpr int [get_Minute](./get_minute/)() const | 현재 객체가 나타내는 날짜 및 시간 값의 분 구성 요소를 반환합니다. |
| int [get_Month](./get_month/)() const | 현재 객체가 나타내는 연도에서 월의 순서를 반환합니다. |
| static [DateTime](./) [get_Now](./get_now/)() | 현재 시간을 로컬 시간으로 나타내는 [DateTime](./) 클래스의 인스턴스를 반환합니다. |
| constexpr int [get_Second](./get_second/)() const | 현재 객체가 나타내는 날짜 및 시간 값의 초 구성 요소를 반환합니다. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | 그레고리력에서 0001년 1월 1일 0시 0분 0초 UTC부터 현재 객체가 나타내는 날짜 및 시간까지 경과한 100나노초 간격 수를 반환합니다. |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | 현재 객체가 나타내는 하루의 시작부터 현재 객체가 나타내는 날짜 및 시간 값까지의 시간 간격을 나타내는 값을 반환합니다. |
| static [DateTime](./) [get_Today](./get_today/)() | 객체가 나타내는 값의 시간 부분 각 구성 요소를 0으로 설정한 현재 날짜를 나타내는 [DateTime](./) 클래스의 인스턴스를 반환합니다. |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | 현재 시간을 UTC로 나타내는 [DateTime](./) 클래스의 인스턴스를 반환합니다. |
| int [get_Year](./get_year/)() const | 현재 객체가 나타내는 연도를 반환합니다. |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | 날짜 구성 요소를 가져옵니다. 내부 사용 전용. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | 각 요소가 표준 날짜 및 시간 형식 지정자 중 하나로 포맷된 현재 객체의 문자열 표현인 문자열 배열을 반환합니다. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | 각 요소가 지정된 표준 날짜 및 시간 형식 지정자로 포맷된 현재 객체의 문자열 표현인 문자열 배열을 반환합니다. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 각 요소가 표준 날짜 및 시간 형식 지정자 중 하나와 지정된 포맷 제공자를 사용해 포맷된 현재 객체의 문자열 표현인 문자열 배열을 반환합니다. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 각 요소가 지정된 표준 날짜 및 시간 형식 지정자와 포맷 제공자를 사용해 포맷된 현재 객체의 문자열 표현인 문자열 배열을 반환합니다. |
| int [GetHashCode](./gethashcode/)() const | 현재 객체에 대한 해시 코드를 반환합니다. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | 현재 객체가 나타내는 날짜 및 시간 값이 현재 시간대의 일광 절약 시간 범위에 속하는지 여부를 결정합니다. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | 지정된 연도가 윤년인지 여부를 결정합니다. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | 현재 객체와 지정된 [DateTime](./) 객체가 서로 다른 날짜 및 시간 값을 나타내는지 여부를 결정합니다. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | 현재 객체가 나타내는 값과 지정된 시간 간격을 합한 날짜 및 시간 값을 나타내는 [DateTime](./) 클래스의 새 인스턴스를 반환합니다. |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | 현재 객체를 현재 객체가 나타내는 값과 지정된 시간 간격을 합한 날짜 및 시간 값으로 설정합니다. |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | 현재 객체가 나타내는 값에서 지정된 시간 간격을 빼서 얻은 날짜 및 시간 값을 나타내는 [DateTime](./) 클래스의 새 인스턴스를 반환합니다. |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | 현재 객체와 지정된 객체가 나타내는 날짜 및 시간 값 사이의 시간 간격을 나타내는 [TimeSpan](../timespan/) 클래스의 인스턴스를 반환합니다. |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | 현재 객체가 나타내는 날짜 및 시간 값에서 지정된 시간 간격을 빼서 얻은 날짜 및 시간 값으로 현재 객체를 설정합니다. |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | 현재 객체가 나타내는 날짜 및 시간 값이 지정된 [DateTime](./) 객체가 나타내는 값보다 이전인지 여부를 결정합니다. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | 현재 객체가 나타내는 날짜 및 시간 값이 지정된 [DateTime](./) 객체가 나타내는 값보다 이전이거나 같은지 여부를 결정합니다. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | 지정된 [DateTime](./) 인스턴스가 나타내는 값을 현재 객체에 할당합니다. |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | 현재 객체와 지정된 [DateTime](./) 객체가 동일한 날짜 및 시간 값을 나타내는지 여부를 결정합니다. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | 현재 객체가 지정된 [DateTime](./) 객체가 나타내는 값보다 이후의 날짜와 시간 값을 나타내는지 확인합니다. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | 현재 객체가 지정된 [DateTime](./) 객체가 나타내는 값보다 이후이거나 동일한 날짜와 시간 값을 나타내는지 확인합니다. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | 지정된 문자열 형태의 날짜와 시간 값을 [DateTime](./) 객체와 동등한 형태로 변환합니다. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 문화별 형식 정보를 사용하여 지정된 문자열 형태의 날짜와 시간 값을 [DateTime](./) 객체와 동등한 형태로 변환합니다. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 지정된 형식과 문화별 형식 정보를 사용하여 지정된 문자열 형태의 날짜와 시간 값을 [DateTime](./) 객체와 동등한 형태로 변환합니다. 문자열 형태는 지정된 형식과 정확히 일치해야 합니다. 변환에 실패하면 예외가 발생합니다. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 지정된 형식, 문화별 형식 정보 및 스타일을 사용하여 지정된 문자열 형태의 날짜와 시간 값을 [DateTime](./) 객체와 동등한 형태로 변환합니다. 문자열 형태는 지정된 형식 중 하나 이상과 정확히 일치해야 합니다. 변환에 실패하면 예외가 발생합니다. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | 지정된 [DateTime](./) 객체와 동일한 틱 수를 나타내며, 인수 **kind**에 따라 로컬 시간, UTC 시간 또는 둘 다 아닌 시간을 나타내는 새로운 [DateTime](./) 객체를 생성합니다. |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | 현재 객체가 나타내는 값에서 지정된 시간 간격을 빼서 얻은 날짜와 시간 값을 나타내는 [DateTime](./) 클래스의 새 인스턴스를 반환합니다. |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | 현재 객체와 지정된 객체가 나타내는 날짜와 시간 값 사이의 시간 간격을 나타내는 [TimeSpan](../timespan/) 클래스의 인스턴스를 반환합니다. |
| **int64_t** [ToBinary](./tobinary/)() const | 현재 객체를 직렬화합니다. |
| **int64_t** [ToFileTime](./tofiletime/)() const | 현재 객체가 나타내는 날짜와 시간 값을 파일 시간 형태로 나타내는 값을 반환합니다. |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | 현재 객체가 나타내는 날짜와 시간 값을 파일 시간 UTC로 변환합니다. |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | 현재 객체가 나타내는 날짜와 시간 값을 로컬 시간으로 나타내는 [DateTime](./) 클래스의 새 인스턴스를 반환합니다. |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | 현재 객체의 긴 날짜 문자열 표현을 포함하는 문자열을 반환합니다. |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | 현재 객체의 긴 시간 문자열 표현을 포함하는 문자열을 반환합니다. |
| **double** [ToOADate](./tooadate/)() const | 현재 객체가 나타내는 날짜와 시간 값을 OLE Automation Date 형식으로 반환합니다. |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | 현재 객체의 짧은 날짜 문자열 표현을 포함하는 문자열을 반환합니다. |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | 현재 객체의 짧은 시간 문자열 표현을 포함하는 문자열을 반환합니다. |
| [String](../string/) [ToString](./tostring/)() const | 현재 문화에서 정의된 서식 규칙을 사용하여 현재 객체가 나타내는 날짜와 시간 값의 문자열 표현을 반환합니다. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | 지정된 형식과 현재 문화에 정의된 서식 규칙을 사용하여 현재 객체가 나타내는 날짜와 시간 값의 문자열 표현을 반환합니다. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 지정된 형식 정보를 사용하여 현재 객체가 나타내는 날짜와 시간 값의 문자열 표현을 반환합니다. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 지정된 형식 정보를 사용하여 현재 객체가 나타내는 날짜와 시간 값의 문자열 표현을 반환합니다. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | 현재 객체가 나타내는 날짜와 시간 값을 UTC로 나타내는 [DateTime](./) 클래스의 새 인스턴스를 반환합니다. |
| time_t [ToUnixTime](./tounixtime/)() const | 현재 객체가 나타내는 날짜와 시간 값을 Unix 시간으로 나타내는 값을 반환합니다. 내부 사용용. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | 지정된 문자열 형태의 날짜와 시간 값을 [DateTime](./) 객체와 동등한 형태로 변환합니다. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | 지정된 문화별 형식 정보와 스타일을 사용하여 지정된 문자열 형태의 날짜와 시간 값을 [DateTime](./) 객체와 동등한 형태로 변환합니다. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | 지정된 형식, 문화별 형식 정보 및 스타일을 사용하여 지정된 문자열 형태의 날짜와 시간 값을 [DateTime](./) 객체와 동등한 형태로 변환합니다. 문자열 형태는 지정된 형식과 정확히 일치해야 합니다. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | 지정된 형식들, 문화별 형식 정보 및 스타일을 사용하여 지정된 문자열 형태의 날짜와 시간 값을 [DateTime](./) 객체와 동등한 형태로 변환합니다. 문자열 형태는 지정된 형식 중 하나 이상과 정확히 일치해야 합니다. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | [TypeInfo](../typeinfo/) 객체를 반환하며, 이 클래스에 대한 정보를 포함합니다. |

## Fields

| Field | Description |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | 최소 가능한 값과 최대 가능한 [DateTime](./) 값 사이의 시간 간격을 100 나노초 단위로 나타낸 수. |
| static [MaxValue](./maxvalue/) | 최대 가능한 날짜와 시간 값을 나타내는 [DateTime](./) 클래스의 인스턴스. |
| static constexpr [MinTicks](./minticks/) | [DateTime](./) 클래스의 인스턴스가 나타낼 수 있는 최소 틱 수. |
| static [MinValue](./minvalue/) | 최소 가능한 날짜와 시간 값을 나타내는 [DateTime](./) 클래스의 인스턴스. |
| static constexpr [TicksPerDay](./ticksperday/) | 하루에 해당하는 틱 수. |
| static constexpr [TicksPerHour](./ticksperhour/) | 한 시간에 해당하는 틱 수. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | 마이크로초당 틱 수. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | 밀리초당 틱 수. |
| static constexpr [TicksPerMinute](./ticksperminute/) | 분당 틱 수. |
| static constexpr [TicksPerSecond](./tickspersecond/) | 초당 틱 수. |
| static [UnixEpoch](./unixepoch/) | Unix epoch 시작(1970-01-01 00:00:00)을 나타내는 [DateTime](./) 클래스의 인스턴스. |

## Remarks

```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // 'DateTime' 클래스 인스턴스를 생성합니다.
  DateTime dateTime{1990, 10, 30};

  // 인스턴스를 여러 형식으로 출력합니다.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
이 코드 예제는 다음과 같은 출력을 생성합니다:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)