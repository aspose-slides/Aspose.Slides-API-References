---
title: DateTime()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक ऐसा उदाहरण बनाता है जो न्यूनतम संभव तिथि और समय मान को दर्शाता है, जो MinValue के बराबर होता है।
type: docs
weight: 1
url: /hi/system/datetime/datetime/
---
## DateTime::DateTime() कंस्ट्रक्टर

एक उदाहरण बनाता है जो न्यूनतम संभव तिथि और समय मान को दर्शाता है, जो MinValue के बराबर है।

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) कंस्ट्रक्टर

एक उदाहरण बनाता है जो विशेष वर्ष, माह और दिन के रूप में निर्दिष्ट तिथि और समय मान को दर्शाता है।

```cpp
System::DateTime::DateTime(int year, int month, int day)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| year | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले वर्ष। |
| month | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **year** का माह। |
| day | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **month** का दिन। |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) कंस्ट्रक्टर

एक उदाहरण बनाता है जो निर्दिष्ट कैलेंडर में विशेष वर्ष, माह और दिन के रूप में निर्दिष्ट तिथि और समय मान को दर्शाता है।

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| year | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले वर्ष। |
| month | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **year** का माह। |
| day | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **month** का दिन। |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | निर्दिष्ट **year**, **month** और **day** को समझने के लिए उपयोग किया जाने वाला कैलेंडर। |

## DateTime::DateTime(int, int, int, int, int, int) कंस्ट्रक्टर

एक उदाहरण बनाता है जो विशेष वर्ष, माह, दिन, घंटा, मिनट और सेकंड के रूप में निर्दिष्ट तिथि और समय मान को दर्शाता है।

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| year | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले वर्ष। |
| month | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **year** का माह। |
| day | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **month** का दिन। |
| hour | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **day** का घंटा। |
| minute | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **hour** का मिनट। |
| second | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **minute** का सेकंड। |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) कंस्ट्रक्टर

एक उदाहरण बनाता है जो विशेष वर्ष, माह, दिन, घंटा, मिनट और सेकंड के रूप में निर्दिष्ट तिथि और समय मान को दर्शाता है।

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| year | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले वर्ष। |
| month | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **year** का माह। |
| day | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **month** का दिन। |
| hour | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **day** का घंटा। |
| minute | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **hour** का मिनट। |
| second | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **minute** का सेकंड। |
| kind | [DateTimeKind](../../datetimekind/) | वह मान जो दर्शाता है कि प्रदान किए गए तिथि और समय पैरामीटर स्थानीय समय, UTC समय या कोई नहीं दर्शाते हैं। |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) कंस्ट्रक्टर

एक उदाहरण बनाता है जो निर्दिष्ट कैलेंडर में विशेष वर्ष, माह, दिन, घंटा, मिनट और सेकंड के रूप में निर्दिष्ट तिथि और समय मान को दर्शाता है।

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| year | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले वर्ष। |
| month | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **year** का माह। |
| day | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **month** का दिन। |
| hour | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **day** का घंटा। |
| minute | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **hour** का मिनट। |
| second | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **minute** का सेकंड। |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | निर्दिष्ट **year**, **month** और **day** को समझने के लिए उपयोग किया जाने वाला कैलेंडर। |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) कंस्ट्रक्टर

एक उदाहरण बनाता है जो विशेष वर्ष, माह, दिन, घंटा, मिनट, सेकंड और मिलिसेकंड के रूप में निर्दिष्ट तिथि और समय मान को दर्शाता है।

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| year | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले वर्ष। |
| month | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **year** का माह। |
| day | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **month** का दिन। |
| hour | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **day** का घंटा। |
| minute | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **hour** का मिनट। |
| second | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **minute** का सेकंड। |
| millisecond | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **second** का मिलिसेकंड। |
| kind | [DateTimeKind](../../datetimekind/) | वह मान जो दर्शाता है कि प्रदान किए गए तिथि और समय पैरामीटर स्थानीय समय, UTC समय या कोई नहीं दर्शाते हैं। |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) कंस्ट्रक्टर

एक उदाहरण बनाता है जो निर्दिष्ट कैलेंडर में विशेष वर्ष, माह, दिन, घंटा, मिनट, सेकंड और मिलिसेकंड के रूप में निर्दिष्ट तिथि और समय मान को दर्शाता है।

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| year | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले वर्ष। |
| month | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **year** का माह। |
| day | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **month** का दिन। |
| hour | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **day** का घंटा। |
| minute | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **hour** का मिनट। |
| second | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **minute** का सेकंड। |
| millisecond | int | उन उदाहरण द्वारा प्रतिनिधित्व किए जाने वाले **second** का मिलिसेकंड। |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | वह मान जो दर्शाता है कि प्रदान किए गए तिथि और समय पैरामीटर स्थानीय समय, UTC समय या कोई नहीं दर्शाते हैं। |
| calendar | [DateTimeKind](../../datetimekind/) | निर्दिष्ट **year**, **month** और **day** को समझने के लिए उपयोग किया जाने वाला कैलेंडर। |

## DateTime::DateTime(int64_t, DateTimeKind) कंस्ट्रक्टर

एक उदाहरण बनाता है जो टिक की संख्या के रूप में निर्दिष्ट तिथि और समय मान को दर्शाता है।

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ticks | **int64_t** | जॉर्जियन कैलेंडर में 1 जनवरी 0001 00:00:00.000 से बीते 100-ns अंतरालों की संख्या। |
| kind | [DateTimeKind](../../datetimekind/) | वह मान जो दर्शाता है कि **ticks** पैरामीटर स्थानीय समय, UTC समय या कोई नहीं दर्शाता है। |

## DateTime::DateTime(int64_t, DateTimeKind, bool) कंस्ट्रक्टर

एक उदाहरण बनाता है जो टिक की संख्या के रूप में निर्दिष्ट तिथि और समय मान को दर्शाता है। आंतरिक उपयोग के लिए।

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ticks | **int64_t** | जॉर्जियन कैलेंडर में 1 जनवरी 0001 00:00:00.000 से बीते 100-ns अंतरालों की संख्या। |
| kind | [DateTimeKind](../../datetimekind/) | वह मान जो दर्शाता है कि **ticks** पैरामीटर स्थानीय समय, UTC समय या कोई नहीं दर्शाता है। |
| is_ambiguous_local_dst | **bool** | सत्य यदि निर्दिष्ट तिथि और समय अस्पष्ट है और कई UTC समयों से मैप किया जा सकता है। |

## DateTime::DateTime(const DateTime\&) कंस्ट्रक्टर

एक उदाहरण को कॉपी-कंस्ट्रक्ट करता है।

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dt | const [DateTime](../)\& | [DateTime](../) क्लास का एक उदाहरण जिससे प्रतिनिधित्व किए गए तिथि और समय मान को कॉपी किया जाता है। |

## संबंधित देखें

* Enum [DateTimeKind](../../datetimekind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [Calendar](../../../system.globalization/calendar/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)