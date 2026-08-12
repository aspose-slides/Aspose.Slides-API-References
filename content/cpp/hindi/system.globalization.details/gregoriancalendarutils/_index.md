---
title: GregorianCalendarUtils
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: ग्रेगोरियन कैलेंडर उपयोगिता फ़ंक्शन।
type: docs
weight: 1
url: /hi/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils वर्ग

ग्रेगोरियन कैलेंडर उपयोगिता फ़ंक्शन।

```cpp
class GregorianCalendarUtils
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) को ICU UDate. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate को [DateTime](../../system/datetime/). |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | ग्रेगोरियन ICU कैलेंडर बनाएं। |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | थ्रेड-स्थानीय ग्रेगोरियन ICU कैलेंडर प्राप्त करता है। |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | विशिष्ट माह में दिनों की संख्या प्राप्त करता है। |
| static int [GetDaysInYear](./getdaysinyear/)(int) | विशिष्ट वर्ष में दिनों की संख्या प्राप्त करता है। |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | जांचता है कि दिन लीप है या नहीं। |
| static **bool** [IsLeapYear](./isleapyear/)(int) | जांचता है कि वर्ष लीप है या नहीं। |

## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | अधिकतम समर्थित ग्रेगोरियन वर्ष। |
| static constexpr [MinYear](./minyear/) | न्यूनतम समर्थित ग्रेगोरियन वर्ष। |

## देखें

* नामस्थान [System::Globalization::Details](../)
* पुस्तकालय [Aspose.Slides](../../)