---
title: GetAmbiguousTimeOffsets()
second_title: Aspose.Slides for C++ API संदर्भ
description: किसी निर्दिष्ट तिथि और समय को जिस UTC तिथि और समय में मैप किया जा सकता है, उसे प्राप्त करता है।
type: docs
weight: 261
url: /hi/system/timezoneinfo/getambiguoustimeoffsets/
---
## TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime) const विधि

कोई निर्दिष्ट तिथि और समय जिसे मैप किया जा सकता है, उसके लिये UTC तिथियों और समयों को प्राप्त करता है।

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime date_time) const
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | तिथि और समय। |

### वापसी मान

[Array](../../array/) UTC तिथियों और समयों का।

## TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset\&) const विधि

कोई निर्दिष्ट तिथि और समय जिसे मैप किया जा सकता है, उसके लिये UTC तिथियों और समयों को प्राप्त करता है।

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset &date_time_offset) const
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | तिथि और समय। |

### वापसी मान

[Array](../../array/) UTC तिथियों और समयों का।

## देखें

* टाइपडिफ [ArrayPtr](../../arrayptr/)
* क्लास [TimeSpan](../../timespan/)
* क्लास [DateTime](../../datetime/)
* क्लास [TimeZoneInfo](../)
* क्लास [DateTimeOffset](../../datetimeoffset/)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)