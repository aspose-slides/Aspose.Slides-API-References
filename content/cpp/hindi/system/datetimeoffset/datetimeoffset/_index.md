---
title: DateTimeOffset()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: डिफ़ॉल्ट कंस्ट्रक्टर।
type: docs
weight: 1
url: /hi/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() कंस्ट्रक्टर

डिफ़ॉल्ट कंस्ट्रक्टर।

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | तिथि और समय। |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| ticks | **int64_t** | टिक्स की संख्या। |
| offset | [TimeSpan](../../timespan/) | UTC से समय ऑफ़सेट। |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | तिथि और समय। |
| offset | [TimeSpan](../../timespan/) | UTC से समय ऑफ़सेट। |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| year | int | वर्ष (1 से 9999)। |
| month | int | माह (1 से 12)। |
| day | int | दिन (1 से महीने में दिनों की संख्या)। |
| hour | int | घंटा (0 से 23)। |
| minute | int | मिनट (0 से 59)। |
| second | int | सेकंड (0 से 59)। |
| offset | [TimeSpan](../../timespan/) | UTC से समय ऑफ़सेट। |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| year | int | वर्ष (1 से 9999)। |
| month | int | माह (1 से 12)। |
| day | int | दिन (1 से महीने में दिनों की संख्या)। |
| hour | int | घंटा (0 से 23)। |
| minute | int | मिनट (0 से 59)। |
| second | int | सेकंड (0 से 59)। |
| millisecond | int | मिलीसेकंड (0 से 999)। |
| offset | [TimeSpan](../../timespan/) | UTC से समय ऑफ़सेट। |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| year | int | वर्ष। |
| month | int | माह (1 से 12)। |
| day | int | दिन (1 से महीने में दिनों की संख्या)। |
| hour | int | घंटा (0 से 23)। |
| minute | int | मिनट (0 से 59)। |
| second | int | सेकंड (0 से 59)। |
| millisecond | int | मिलीसेकंड (0 से 999)। |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | वर्ष, माह और दिन की व्याख्या के लिए उपयोग किया गया कैलेंडर। |
| offset | [TimeSpan](../../timespan/) | UTC से समय ऑफ़सेट। |

## संबंधित देखें

* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeOffset](../)
* Class [DateTime](../../datetime/)
* Class [TimeSpan](../../timespan/)
* Class [Calendar](../../../system.globalization/calendar/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)