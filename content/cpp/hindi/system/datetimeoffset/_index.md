---
title: DateTimeOffset
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "समन्वित विश्व समय (Coordinated Universal Time) के सापेक्ष दिन और समय को समाहित करता है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार के इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियां और/या सत्यापन दोष उत्पन्न हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन को आर्ग्यूमेंट के रूप में पास करने के लिए करें।"
type: docs
weight: 235
url: /hi/system/datetimeoffset/
---
## DateTimeOffset क्लास

Contains the date and time of day relative to Coordinated Universal Time. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DateTimeOffset
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | निर्दिष्ट टाइम अंतराल को [DateTimeOffset](./) ऑब्जेक्ट में जोड़ता है। |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | निर्दिष्ट संख्या में दिनों को [DateTimeOffset](./) ऑब्जेक्ट में जोड़ता है। |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | निर्दिष्ट संख्या में घंटों को [DateTimeOffset](./) ऑब्जेक्ट में जोड़ता है। |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | निर्दिष्ट संख्या में मिलीसेकंड को [DateTimeOffset](./) ऑब्जेक्ट में जोड़ता है। |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | निर्दिष्ट संख्या में मिनटों को [DateTimeOffset](./) ऑब्जेक्ट में जोड़ता है। |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | निर्दिष्ट संख्या में महीनों को [DateTimeOffset](./) ऑब्जेक्ट में जोड़ता है। |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | निर्दिष्ट संख्या में सेकण्ड को [DateTimeOffset](./) ऑब्जेक्ट में जोड़ता है। |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | निर्दिष्ट संख्या में टिक को [DateTimeOffset](./) ऑब्जेक्ट में जोड़ता है। |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | निर्दिष्ट संख्या में वर्षों को [DateTimeOffset](./) ऑब्जेक्ट में जोड़ता है। |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | दो [DateTimeOffset](./) ऑब्जेक्ट की तुलना करता है। |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | दो [DateTimeOffset](./) ऑब्जेक्ट की तुलना करता है। |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | दो [DateTimeOffset](./) ऑब्जेक्ट की तुलना करता है। |
| constexpr [DateTimeOffset](./datetimeoffset/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | कन्स्ट्रक्टर। |
| [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | कन्स्ट्रक्टर। |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | कन्स्ट्रक्टर। |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | कन्स्ट्रक्टर। |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | कन्स्ट्रक्टर। |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | कन्स्ट्रक्टर। |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | जाँचता है कि दो [DateTimeOffset](./) ऑब्जेक्ट समान समय बिंदु दर्शाते हैं या नहीं। |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | जाँचता है कि दो [DateTimeOffset](./) ऑब्जेक्ट समान समय बिंदु दर्शाते हैं या नहीं। |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | जाँचता है कि दो [DateTimeOffset](./) ऑब्जेक्ट समान समय बिंदु दर्शाते हैं या नहीं। |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | जाँचता है कि दो [DateTimeOffset](./) ऑब्जेक्ट समान समय बिंदु और समान ऑफ़सेट दर्शाते हैं या नहीं। |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | जाँचता है कि दो [DateTimeOffset](./) ऑब्जेक्ट समान समय बिंदु और समान ऑफ़सेट दर्शाते हैं या नहीं। |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) फ़ाइल समय को स्थानीय समय ऑफ़सेट के साथ तिथि और समय में बदलता है। |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix समय को [DateTimeOffset](./) ऑब्जेक्ट में बदलता है। |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix समय को [DateTimeOffset](./) ऑब्जेक्ट में बदलता है। |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | वर्तमान ऑब्जेक्ट का तिथि घटक प्राप्त करता है। |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | [DateTime](../datetime/) मान प्राप्त करता है। |
| int [get_Day](./get_day/)() const | वर्तमान ऑब्जेक्ट का महीने का दिन प्राप्त करता है। |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | वर्तमान ऑब्जेक्ट का सप्ताह का दिन प्राप्त करता है। |
| int [get_DayOfYear](./get_dayofyear/)() const | वर्तमान ऑब्जेक्ट का वर्ष का दिन प्राप्त करता है। |
| int [get_Hour](./get_hour/)() const | वर्तमान ऑब्जेक्ट का घंटे का घटक प्राप्त करता है। |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | [DateTime](../datetime/) मान प्राप्त करता है जो स्थानीय तिथि और समय को दर्शाता है। |
| constexpr int [get_Millisecond](./get_millisecond/)() const | वर्तमान ऑब्जेक्ट का मिलीसेकंड घटक प्राप्त करता है। |
| int [get_Minute](./get_minute/)() const | वर्तमान ऑब्जेक्ट का मिनट घटक प्राप्त करता है। |
| int [get_Month](./get_month/)() const | वर्तमान ऑब्जेक्ट का महीने का घटक प्राप्त करता है। |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | [DateTimeOffset](./) प्राप्त करता है जिसकी तिथि और समय वर्तमान स्थानीय समय पर सेट होते हैं और जिसका ऑफ़सेट स्थानीय समय के ऑफ़सेट पर सेट होता है। |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | UTC से ऑफ़सेट प्राप्त करता है। |
| constexpr int [get_Second](./get_second/)() const | वर्तमान ऑब्जेक्ट का सेकण्ड घटक प्राप्त करता है। |
| **int64_t** [get_Ticks](./get_ticks/)() const | वर्तमान ऑब्जेक्ट के टिक की संख्या प्राप्त करता है। |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | वर्तमान ऑब्जेक्ट का दैनिक समय प्राप्त करता है। |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | [DateTime](../datetime/) मान प्राप्त करता है जो UTC तिथि और समय को दर्शाता है। |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | [DateTimeOffset](./) प्राप्त करता है जिसकी तिथि और समय वर्तमान UTC-समय पर सेट होते हैं और जिसका ऑफ़सेट [TimeSpan::Zero](../timespan/zero/) है। |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | UTC समय में वर्तमान ऑब्जेक्ट के टिक की संख्या प्राप्त करता है। |
| int [get_Year](./get_year/)() const | वर्तमान ऑब्जेक्ट का वर्ष घटक प्राप्त करता है। |
| int [GetHashCode](./gethashcode/)() const | वर्तमान [DateTimeOffset](./) ऑब्जेक्ट का हैश कोड प्राप्त करता है। |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट और निर्दिष्ट [DateTimeOffset](./) ऑब्जेक्ट अलग तिथि और समय मान दर्शाते हैं या नहीं। |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | एक नया [DateTimeOffset](./) क्लास इंस्टेंस लौटाता है जो वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान और निर्दिष्ट टाइम स्पैन के योग को दर्शाता है। |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | एक नया [DateTimeOffset](./) क्लास इंस्टेंस लौटाता है जो वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान से निर्दिष्ट टाइम स्पैन को घटाने का परिणाम दर्शाता है। |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | [TimeSpan](../timespan/) क्लास का एक इंस्टेंस लौटाता है जो वर्तमान और निर्दिष्ट ऑब्जेक्ट द्वारा दर्शाए गए तिथि और समय मानों के बीच समय अंतराल दर्शाता है। |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा दर्शाया गया तिथि और समय मान निर्दिष्ट [DateTimeOffset](./) ऑब्जेक्ट द्वारा दर्शाए गए मान से पहले है या नहीं। |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा दर्शाया गया तिथि और समय मान निर्दिष्ट [DateTimeOffset](./) ऑब्जेक्ट द्वारा दर्शाए गए मान से पहले या समान है या नहीं। |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट और निर्दिष्ट [DateTimeOffset](./) ऑब्जेक्ट समान तिथि और समय मान दर्शाते हैं या नहीं। |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा दर्शाया गया तिथि और समय मान निर्दिष्ट [DateTimeOffset](./) ऑब्जेक्ट द्वारा दर्शाए गए मान से बाद में है या नहीं। |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा दर्शाया गया तिथि और समय मान निर्दिष्ट [DateTimeOffset](./) ऑब्जेक्ट द्वारा दर्शाए गए मान से बाद में या समान है या नहीं। |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | निर्दिष्ट स्ट्रिंग को [DateTimeOffset](./) समतुल्य में बदलता है। |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | निर्दिष्ट फॉर्मेट प्रोवाइडर और फॉर्मेटिंग शैली का उपयोग करके निर्दिष्ट स्ट्रिंग को [DateTimeOffset](./) ऑब्जेक्ट में बदलता है। |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | निर्दिष्ट फॉर्मेट, फॉर्मेट प्रोवाइडर और फॉर्मेटिंग शैली का उपयोग करके निर्दिष्ट स्ट्रिंग को [DateTimeOffset](./) ऑब्जेक्ट में बदलता है। |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | निर्दिष्ट फॉर्मेट्स, फॉर्मेट प्रोवाइडर और फॉर्मेटिंग शैली का उपयोग करके निर्दिष्ट स्ट्रिंग को [DateTimeOffset](./) ऑब्जेक्ट में बदलता है। |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | वर्तमान ऑब्जेक्ट से निर्दिष्ट टाइम अंतराल घटाता है। |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | वर्तमान ऑब्जेक्ट से निर्दिष्ट [DateTimeOffset](./) मान घटाता है। |
| **int64_t** [ToFileTime](./tofiletime/)() const | वर्तमान ऑब्जेक्ट को [Windows](../../system.windows/) फ़ाइल समय में बदलता है। |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | वर्तमान ऑब्जेक्ट को स्थानीय समय दर्शाने वाला ऑब्जेक्ट में बदलता है। |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | वर्तमान ऑब्जेक्ट का ऑफ़सेट निर्दिष्ट ऑफ़सेट से बदलता है। |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | निर्दिष्ट फॉर्मेट और फॉर्मेट प्रोवाइडर का उपयोग करके वर्तमान ऑब्जेक्ट को स्ट्रिंग में बदलता है। |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | निर्दिष्ट फॉर्मेट प्रोवाइडर का उपयोग करके वर्तमान ऑब्जेक्ट को स्ट्रिंग में बदलता है। |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | निर्दिष्ट फॉर्मेट का उपयोग करके वर्तमान ऑब्जेक्ट को स्ट्रिंग में बदलता है। |
| [String](../string/) [ToString](./tostring/)() const | वर्तमान ऑब्जेक्ट को स्ट्रिंग में बदलता है। |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | वर्तमान ऑब्जेक्ट को UTC समय दर्शाने वाला ऑब्जेक्ट में बदलता है। |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Unix इपोक शुरू होने से बीते मिलीसेकंड प्राप्त करता है। |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Unix इपोक शुरू होने से बीते सेकंड प्राप्त करता है। |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | निर्दिष्ट स्ट्रिंग को [DateTimeOffset](./) ऑब्जेक्ट में बदलने का प्रयास करता है। |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | निर्दिष्ट फॉर्मेट प्रोवाइडर और फॉर्मेटिंग शैली का उपयोग करके निर्दिष्ट स्ट्रिंग को [DateTimeOffset](./) ऑब्जेक्ट में बदलने का प्रयास करता है। |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | निर्दिष्ट फॉर्मेट्स, फॉर्मेट प्रोवाइडर और फॉर्मेटिंग शैली का उपयोग करके निर्दिष्ट स्ट्रिंग को [DateTimeOffset](./) ऑब्जेक्ट में बदलने का प्रयास करता है। |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | निर्दिष्ट फॉर्मेट, फॉर्मेट प्रोवाइडर और फॉर्मेटिंग शैली का उपयोग करके निर्दिष्ट स्ट्रिंग को [DateTimeOffset](./) ऑब्जेक्ट में बदलने का प्रयास करता है। |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | एक [TypeInfo](../typeinfo/) ऑब्जेक्ट लौटाता है जो [TimeSpan](../timespan/) संरचना को दर्शाता है। |

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | अधिकतम ऑफ़सेट टिक्स में प्राप्त करता है। |
| static [MaxValue](./maxvalue/) | सबसे बड़ा [DateTimeOffset](./) मान प्राप्त करता है। |
| static constexpr [MinOffset](./minoffset/) | न्यूनतम ऑफ़सेट टिक्स में प्राप्त करता है। |
| static [MinValue](./minvalue/) | सबसे प्रारंभिक [DateTimeOffset](./) मान प्राप्त करता है। |
| static [UnixEpoch](./unixepoch/) | Unix इपोक शुरू होना प्राप्त करता है। |

## संबंधित देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)