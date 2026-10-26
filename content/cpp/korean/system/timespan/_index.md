---
title: TimeSpan
second_title: Aspose.Slides for C++ API 레퍼런스
description: "시간 간격을 나타냅니다. 이 타입은 스택에 할당하고 값 또는 참조로 함수에 전달해야 합니다. 이 타입의 객체를 관리하기 위해 System::SmartPtr 클래스를 사용하지 마십시오."
type: docs
weight: 1314
url: /ko/system/timespan/
---
## TimeSpan 클래스

시간 간격을 나타냅니다. 이 타입은 스택에 할당하고 값 또는 참조로 함수에 전달해야 합니다. [System::SmartPtr](../smartptr/) 클래스를 사용해 이 타입의 객체를 관리하지 마십시오.

```cpp
class TimeSpan
```

## 메서드

| Method | Description |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | 현재와 지정된 객체가 나타내는 시간 간격의 합을 나타내는 [TimeSpan](./) 클래스의 새 인스턴스를 반환합니다. |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | 두 [TimeSpan](./) 객체를 비교합니다. |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | 현재 객체와 지정된 객체를 비교합니다. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 현재 객체와 지정된 객체를 비교합니다. |
| [TimeSpan](./) [Duration](./duration/)() const | [TimeSpan](./) 객체의 새 인스턴스를 반환하며, 그 값은 현재 객체의 절대값입니다. |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | 현재 객체가 나타내는 시간 간격이 지정된 객체가 나타내는 시간 간격과 같은지 판단합니다. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 현재 객체가 나타내는 시간 간격이 지정된 객체가 나타내는 시간 간격과 같은지 판단합니다. |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | 지정된 객체들이 같은 시간 간격을 나타내면 true, 그렇지 않으면 false를 반환합니다. |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | 지정된 간격을 나타내는 새로운 [TimeSpan](./) 객체를 반환합니다. |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | 지정된 간격을 나타내는 새로운 [TimeSpan](./) 객체를 반환합니다. |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | 지정된 간격을 나타내는 새로운 [TimeSpan](./) 객체를 반환합니다. |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | 지정된 간격을 나타내는 새로운 [TimeSpan](./) 객체를 반환합니다. |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | 지정된 간격을 나타내는 새로운 [TimeSpan](./) 객체를 반환합니다. |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | 지정된 간격을 나타내는 새로운 [TimeSpan](./) 객체를 반환합니다. |
| constexpr int [get_Days](./get_days/)() const | 현재 [TimeSpan](./) 객체가 나타내는 시간 간격의 일(day) 구성 요소를 반환합니다. |
| constexpr int [get_Hours](./get_hours/)() const | 현재 [TimeSpan](./) 객체가 나타내는 시간 간격의 시간(hour) 구성 요소를 반환합니다. |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | 현재 [TimeSpan](./) 객체가 나타내는 시간 간격의 밀리초 구성 요소를 반환합니다. |
| constexpr int [get_Minutes](./get_minutes/)() const | 현재 [TimeSpan](./) 객체가 나타내는 시간 간격의 분(minute) 구성 요소를 반환합니다. |
| constexpr int [get_Seconds](./get_seconds/)() const | 현재 [TimeSpan](./) 객체가 나타내는 시간 간격의 초(second) 구성 요소를 반환합니다. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | 현재 [TimeSpan](./) 객체가 나타내는 시간 간격을 구성하는 100나노초 단위의 개수를 반환합니다. |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | 현재 [TimeSpan](./) 객체를 전체 및 소수 일 단위로 표현한 값을 반환합니다. |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | 현재 [TimeSpan](./) 객체를 전체 및 소수 시간 단위로 표현한 값을 반환합니다. |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | 현재 [TimeSpan](./) 객체를 전체 및 소수 밀리초 단위로 표현한 값을 반환합니다. |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | 현재 [TimeSpan](./) 객체를 전체 및 소수 분 단위로 표현한 값을 반환합니다. |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | 현재 [TimeSpan](./) 객체를 전체 및 소수 초 단위로 표현한 값을 반환합니다. |
| int [GetHashCode](./gethashcode/)() const | 현재 객체의 해시 코드를 반환합니다. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | 현재 [TimeSpan](./) 객체가 나타내는 부정값을 나타내는 새로운 [TimeSpan](./) 객체를 반환합니다. |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | 현재 객체가 나타내는 시간 간격이 지정된 객체가 나타내는 시간 간격과 같지 않은지 판단합니다. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | 현재와 지정된 객체가 나타내는 시간 간격의 합을 나타내는 [TimeSpan](./) 클래스의 새 인스턴스를 반환합니다. |
| [TimeSpan](./) [operator+](./operator_plus/)() const | 자신을 반환합니다. |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | 현재 객체에 현재와 지정된 객체가 나타내는 시간 간격의 합을 할당합니다. |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | 지정된 객체가 나타내는 시간 간격을 현재 객체가 나타내는 시간 간격에서 뺀 결과를 나타내는 새로운 [TimeSpan](./) 클래스의 인스턴스를 반환합니다. |
| [TimeSpan](./) [operator-](./operator_minus/)() const | 현재 [TimeSpan](./) 객체가 나타내는 부정값을 나타내는 새로운 [TimeSpan](./) 객체를 반환합니다. |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | 현재 객체에 지정된 객체가 나타내는 시간 간격을 현재 객체가 나타내는 시간 간격에서 뺀 결과를 할당합니다. |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | 현재 객체가 나타내는 시간 간격이 지정된 객체가 나타내는 시간 간격보다 짧은지 판단합니다. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | 현재 객체가 나타내는 시간 간격이 지정된 객체가 나타내는 시간 간격보다 짧거나 같은지 판단합니다. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | 지정된 [TimeSpan](./) 객체의 시간 간격을 현재 [TimeSpan](./) 객체에 설정합니다. |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | 현재 객체가 나타내는 시간 간격이 지정된 객체가 나타내는 시간 간격과 같은지 판단합니다. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | 현재 객체가 나타내는 시간 간격이 지정된 객체가 나타내는 시간 간격보다 긴지 판단합니다. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | 현재 객체가 나타내는 시간 간격이 지정된 객체가 나타내는 시간 간격보다 길거나 같은지 판단합니다. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | 문자열을 동등한 [TimeSpan](./) 객체로 변환합니다. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 형식 제공자를 사용하여 문자열을 동등한 [TimeSpan](./) 객체로 변환합니다. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | 지정된 형식, 형식 제공자 및 스타일을 사용하여 문자열을 동등한 [TimeSpan](./) 객체로 변환합니다. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | 지정된 형식, 형식 제공자 및 스타일을 사용하여 문자열을 동등한 [TimeSpan](./) 객체로 변환합니다. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | 지정된 객체가 나타내는 시간 간격을 현재 객체가 나타내는 시간 간격에서 뺀 결과를 나타내는 새로운 [TimeSpan](./) 클래스의 인스턴스를 반환합니다. |
| constexpr [TimeSpan](./timespan/)() | 0 시간 간격을 나타내는 [TimeSpan](./) 객체를 구성합니다. |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | 지정된 시간 간격을 나타내는 [TimeSpan](./) 클래스의 인스턴스를 구성합니다. |
|  [TimeSpan](./timespan/)(int, int, int) | 지정된 시간(시), 분, 초의 합과 같은 시간 간격을 나타내는 [TimeSpan](./) 클래스의 인스턴스를 구성합니다. |
|  [TimeSpan](./timespan/)(int, int, int, int, int) | 지정된 시간(시), 분, 초, 밀리초의 합과 같은 시간 간격을 나타내는 [TimeSpan](./) 클래스의 인스턴스를 구성합니다. |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | 지정된 [TimeSpan](./) 객체가 나타내는 시간 간격과 같은 시간 간격을 나타내는 [TimeSpan](./) 객체를 구성합니다. |
| [String](../string/) [ToString](./tostring/)() const | 현재 객체가 나타내는 시간 간격의 문자열 표현을 반환합니다. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | 지정된 형식을 사용하여 현재 객체의 값을 동등한 문자열 표현으로 변환합니다. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 지정된 형식 및 형식 제공자를 사용하여 현재 객체의 값을 동등한 문자열 표현으로 변환합니다. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | 문자열을 동등한 [TimeSpan](./) 객체로 변환하고 변환 결과를 반환합니다. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | 지정된 형식 제공자를 사용하여 문자열을 동등한 [TimeSpan](./) 객체로 변환하고 변환 결과를 반환합니다. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | 지정된 형식 및 형식 제공자를 사용하여 문자열을 동등한 [TimeSpan](./) 객체로 변환하고 변환 결과를 반환합니다. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | 지정된 형식, 형식 제공자 및 스타일을 사용하여 문자열을 동등한 [TimeSpan](./) 객체로 변환하고 변환 결과를 반환합니다. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | 지정된 형식, 형식 제공자 및 스타일을 사용하여 문자열을 동등한 [TimeSpan](./) 객체로 변환하고 변환 결과를 반환합니다. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | 지정된 형식 및 형식 제공자를 사용하여 문자열을 동등한 [TimeSpan](./) 객체로 변환하고 변환 결과를 반환합니다. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | [TypeInfo](../typeinfo/) 객체를 반환하며, 이는 [TimeSpan](./) 구조를 나타냅니다. |
## 필드

| Field | Description |
| --- | --- |
| static [MaxValue](./maxvalue/) | 가능한 가장 긴 간격을 나타내는 [TimeSpan](./) 객체입니다. |
| static [MinValue](./minvalue/) | /// 가능한 가장 짧은 간격을 나타내는 [TimeSpan](./) 객체입니다. |
| static constexpr [TicksPerDay](./ticksperday/) | 하루(24시간) 안에 포함된 100나노초 단위의 개수입니다. |
| static constexpr [TicksPerHour](./ticksperhour/) | 한 시간 안에 포함된 100나노초 단위의 개수입니다. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | 1밀리초 안에 포함된 100나노초 단위의 개수입니다. |
| static constexpr [TicksPerMinute](./ticksperminute/) | 1분 안에 포함된 100나노초 단위의 개수입니다. |
| static constexpr [TicksPerSecond](./tickspersecond/) | 1초 안에 포함된 100나노초 단위의 개수입니다. |
| static [Zero](./zero/) | 영(0) 간격을 나타내는 [TimeSpan](./) 객체입니다. |
## 비고



```cpp
#include "system/datetime.h"
#include "system/timespan.h"
#include <iostream>

int main()
{
  const auto date1 = System::DateTime(2021, 01, 01);
  const auto date2 = System::DateTime(2021, 10, 30);

  const auto interval = date2 - date1;

  std::cout << "Number of ticks: " << interval.get_Ticks() << std::endl;
  std::cout << "Number of milliseconds: " << interval.get_Milliseconds() << std::endl;
  std::cout << "Total number of milliseconds: " << interval.get_TotalMilliseconds() << std::endl;
  std::cout << "Number of minutes: " << interval.get_Minutes() << std::endl;
  std::cout << "Total number of minutes: " << interval.get_TotalMinutes() << std::endl;
  std::cout << "Number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Total number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Number of days: " << interval.get_Days() << std::endl;
  std::cout << "Total number of days: " << interval.get_TotalDays() << std::endl;

  return 0;
}
/*
This code example produces the following output:
틱 수: 260928000000000
밀리초 수: 0
밀리초 총합: 2.60928e+10
분 수: 0
분 총합: 434880
시간 수: 0
시간 총합: 0
일 수: 302
일 총합: 302
*/
```

## 참조

* Namespace [System](../)
* Library [Aspose.Slides](../../)