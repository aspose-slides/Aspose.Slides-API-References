---
title: DateTimeOffset
second_title: Aspose.Slides for C++ API 레퍼런스
description: "협정 세계시(UTC)를 기준으로 날짜와 시간을 포함합니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여서만 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하여 인스턴스를 만들면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고 해당 포인터를 함수 인자로 전달하십시오."
type: docs
weight: 235
url: /ko/system/datetimeoffset/
---
## DateTimeOffset 클래스

Contains the date and time of day relative to Coordinated Universal Time. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DateTimeOffset
```

## 메서드

| Method | Description |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | 지정된 시간 간격을 [DateTimeOffset](./) 객체에 추가합니다. |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | 지정된 일 수를 [DateTimeOffset](./) 객체에 추가합니다. |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | 지정된 시간 수를 [DateTimeOffset](./) 객체에 추가합니다. |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | 지정된 밀리초 수를 [DateTimeOffset](./) 객체에 추가합니다. |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | 지정된 분 수를 [DateTimeOffset](./) 객체에 추가합니다. |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | 지정된 개월 수를 [DateTimeOffset](./) 객체에 추가합니다. |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | 지정된 초 수를 [DateTimeOffset](./) 객체에 추가합니다. |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | 지정된 틱 수를 [DateTimeOffset](./) 객체에 추가합니다. |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | 지정된 연 수를 [DateTimeOffset](./) 객체에 추가합니다. |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | 두 [DateTimeOffset](./) 객체를 비교합니다. |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | 두 [DateTimeOffset](./) 객체를 비교합니다. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 두 [DateTimeOffset](./) 객체를 비교합니다. |
| constexpr [DateTimeOffset](./datetimeoffset/)() | 기본 생성자입니다. |
|  [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | 생성자입니다. |
|  [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | 생성자입니다. |
|  [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | 생성자입니다. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | 생성자입니다. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | 생성자입니다. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | 생성자입니다. |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | 두 [DateTimeOffset](./) 객체가 같은 시간점을 나타내는지 확인합니다. |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | 두 [DateTimeOffset](./) 객체가 같은 시간점을 나타내는지 확인합니다. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 두 [DateTimeOffset](./) 객체가 같은 시간점을 나타내는지 확인합니다. |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | 두 [DateTimeOffset](./) 객체가 같은 시간점을 나타내며 동일한 오프셋을 가지고 있는지 확인합니다. |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 두 [DateTimeOffset](./) 객체가 같은 시간점을 나타내며 동일한 오프셋을 가지고 있는지 확인합니다. |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) 파일 시간을 로컬 시간 오프셋이 적용된 날짜와 시간으로 변환합니다. |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix 시간을 [DateTimeOffset](./) 객체로 변환합니다. |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix 시간을 [DateTimeOffset](./) 객체로 변환합니다. |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | 현재 객체의 날짜 구성 요소를 가져옵니다. |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | [DateTime](../datetime/) 값을 가져옵니다. |
| int [get_Day](./get_day/)() const | 현재 객체의 월 일(day)을 가져옵니다. |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | 현재 객체의 요일을 가져옵니다. |
| int [get_DayOfYear](./get_dayofyear/)() const | 현재 객체의 연중 일(day)을 가져옵니다. |
| int [get_Hour](./get_hour/)() const | 현재 객체의 시간 구성 요소를 가져옵니다. |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | [DateTime](../datetime/) 값을 가져와 로컬 날짜와 시간을 나타냅니다. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | 현재 객체의 밀리초 구성 요소를 가져옵니다. |
| int [get_Minute](./get_minute/)() const | 현재 객체의 분 구성 요소를 가져옵니다. |
| int [get_Month](./get_month/)() const | 현재 객체의 월 구성 요소를 가져옵니다. |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | [DateTimeOffset](./) 를 가져옵니다(날짜와 시간이 현재 로컬 시간으로 설정되고 오프셋이 로컬 시간 오프셋으로 설정됨). |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | UTC로부터의 오프셋을 가져옵니다. |
| constexpr int [get_Second](./get_second/)() const | 현재 객체의 초 구성 요소를 가져옵니다. |
| **int64_t** [get_Ticks](./get_ticks/)() const | 현재 객체의 틱 수를 가져옵니다. |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | 현재 객체의 시간대를 가져옵니다. |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | [DateTime](../datetime/) 값을 가져와 UTC 날짜와 시간을 나타냅니다. |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | [DateTimeOffset](./) 를 가져옵니다(날짜와 시간이 현재 UTC 시간으로 설정되고 오프셋이 [TimeSpan::Zero](../timespan/zero/)). |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | UTC 시간에서 현재 객체의 틱 수를 가져옵니다. |
| int [get_Year](./get_year/)() const | 현재 객체의 연 구성 요소를 가져옵니다. |
| int [GetHashCode](./gethashcode/)() const | 현재 [DateTimeOffset](./) 객체의 해시 코드를 가져옵니다. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | 현재 객체와 지정된 [DateTimeOffset](./) 객체가 서로 다른 날짜와 시간 값을 나타내는지 판단합니다. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | 현재 객체와 지정된 시간 간격의 합을 나타내는 날짜와 시간 값을 표현하는 새로운 [DateTimeOffset](./) 클래스 인스턴스를 반환합니다. |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | 지정된 시간 간격을 현재 객체의 값에서 빼서 얻은 날짜와 시간 값을 나타내는 새로운 [DateTimeOffset](./) 클래스 인스턴스를 반환합니다. |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | 현재 객체와 지정된 객체가 나타내는 날짜와 시간 값 사이의 시간 간격을 표현하는 [TimeSpan](../timespan/) 클래스 인스턴스를 반환합니다. |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | 현재 객체가 지정된 [DateTimeOffset](./) 객체가 나타내는 값보다 이전 날짜와 시간 값을 나타내는지 판단합니다. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | 현재 객체가 지정된 [DateTimeOffset](./) 객체가 나타내는 값보다 이전이거나 같은 날짜와 시간 값을 나타내는지 판단합니다. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | 현재 객체와 지정된 [DateTimeOffset](./) 객체가 같은 날짜와 시간 값을 나타내는지 판단합니다. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | 현재 객체가 지정된 [DateTimeOffset](./) 객체가 나타내는 값보다 이후 날짜와 시간 값을 나타내는지 판단합니다. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | 현재 객체가 지정된 [DateTimeOffset](./) 객체가 나타내는 값보다 이후이거나 같은 날짜와 시간 값을 나타내는지 판단합니다. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | 지정된 문자열을 [DateTimeOffset](./) 등가물로 변환합니다. |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 지정된 문자열을 지정된 형식 제공자와 형식 스타일을 사용하여 [DateTimeOffset](./) 객체로 변환합니다. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 지정된 문자열을 지정된 형식, 형식 제공자 및 형식 스타일을 사용하여 [DateTimeOffset](./) 객체로 변환합니다. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | 지정된 문자열을 지정된 포맷들, 형식 제공자 및 형식 스타일을 사용하여 [DateTimeOffset](./) 객체로 변환합니다. |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | 지정된 시간 간격을 현재 객체에서 빼줍니다. |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | 지정된 [DateTimeOffset](./) 값을 현재 객체에서 빼줍니다. |
| **int64_t** [ToFileTime](./tofiletime/)() const | 현재 객체를 [Windows](../../system.windows/) 파일 시간으로 변환합니다. |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | 현재 객체를 로컬 시간을 나타내는 객체로 변환합니다. |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | 현재 객체의 오프셋을 지정된 오프셋으로 교체합니다. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 지정된 형식과 형식 제공자를 사용하여 현재 객체를 문자열로 변환합니다. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 지정된 형식 제공자를 사용하여 현재 객체를 문자열로 변환합니다. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | 지정된 형식을 사용하여 현재 객체를 문자열로 변환합니다. |
| [String](../string/) [ToString](./tostring/)() const | 현재 객체를 문자열로 변환합니다. |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | 현재 객체를 UTC 시간을 나타내는 객체로 변환합니다. |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Unix epoch 시작부터 경과한 밀리초를 가져옵니다. |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Unix epoch 시작부터 경과한 초를 가져옵니다. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | 지정된 문자열을 [DateTimeOffset](./) 객체로 변환을 시도합니다. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | 지정된 문자열을 지정된 형식 제공자와 형식 스타일을 사용하여 [DateTimeOffset](./) 객체로 변환을 시도합니다. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | 지정된 문자열을 지정된 포맷들, 형식 제공자 및 형식 스타일을 사용하여 [DateTimeOffset](./) 객체로 변환을 시도합니다. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | 지정된 문자열을 지정된 형식, 형식 제공자 및 형식 스타일을 사용하여 [DateTimeOffset](./) 객체로 변환을 시도합니다. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | [TypeInfo](../typeinfo/) 객체를 반환합니다(이는 [TimeSpan](../timespan/) 구조를 나타냅니다). |

## 필드

| Field | Description |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | 틱 단위 최대 오프셋을 가져옵니다. |
| static [MaxValue](./maxvalue/) | 가장 큰 [DateTimeOffset](./) 값을 가져옵니다. |
| static constexpr [MinOffset](./minoffset/) | 틱 단위 최소 오프셋을 가져옵니다. |
| static [MinValue](./minvalue/) | 가장 이른 [DateTimeOffset](./) 값을 가져옵니다. |
| static [UnixEpoch](./unixepoch/) | Unix epoch 시작 시점을 가져옵니다. |

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)