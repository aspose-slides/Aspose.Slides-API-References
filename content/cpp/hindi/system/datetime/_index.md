---
title: DateTime
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "समय निरन्तरता पर एक विशिष्ट तिथि और समय मान का प्रतिनिधित्व करता है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए तथा फ़ंक्शनों को मान या संदर्भ द्वारा पास किया जाना चाहिए। इस प्रकार की वस्तुओं को प्रबंधित करने के लिए कभी भी System::SmartPtr क्लास का उपयोग न करें।"
type: docs
weight: 222
url: /hi/system/datetime/
---
## DateTime क्लास


समय निरन्तरता पर एक विशिष्ट तिथि और समय मान का प्रतिनिधित्व करता है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शन को मूल्य या संदर्भ द्वारा पास किया जाना चाहिए। इस प्रकार की वस्तुओं को प्रबंधित करने के लिए कभी भी [System::SmartPtr](../smartptr/) क्लास का उपयोग न करें।

```cpp
class DateTime
```

## विधियां

| विधि | विवरण |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | एक नया [DateTime](./) क्लास का उदाहरण लौटाता है जो एक तिथि और समय मान का प्रतिनिधित्व करता है जो निर्दिष्ट समय अंतराल को वर्तमान वस्तु द्वारा प्रदर्शित तिथि और समय मान में जोड़ने से प्राप्त होता है। |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | एक नया [DateTime](./) क्लास का उदाहरण लौटाता है जो तिथि और समय मान का प्रतिनिधित्व करता है जो वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए मान और निर्दिष्ट दिनों की संख्या का योग है। |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | एक नया [DateTime](./) क्लास का उदाहरण लौटाता है जो तिथि और समय मान का प्रतिनिधित्व करता है जो वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए मान और निर्दिष्ट घंटों की संख्या का योग है। |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | एक नया [DateTime](./) क्लास का उदाहरण लौटाता है जो तिथि और समय मान का प्रतिनिधित्व करता है जो वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए मान और निर्दिष्ट मिलीसेकंड की संख्या का योग है। |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | एक नया [DateTime](./) क्लास का उदाहरण लौटाता है जो तिथि और समय मान का प्रतिनिधित्व करता है जो वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए मान और निर्दिष्ट मिनटों की संख्या का योग है। |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | एक नया [DateTime](./) क्लास का उदाहरण लौटाता है जो तिथि और समय मान का प्रतिनिधित्व करता है जो वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए मान और निर्दिष्ट महीनों की संख्या का योग है। |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | एक नया [DateTime](./) क्लास का उदाहरण लौटाता है जो तिथि और समय मान का प्रतिनिधित्व करता है जो वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए मान और निर्दिष्ट सेकंड की संख्या का योग है। |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | एक नया [DateTime](./) क्लास का उदाहरण लौटाता है जो तिथि और समय मान का प्रतिनिधित्व करता है जो वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए मान और निर्दिष्ट 100-नैनोसेकंड अंतराल की संख्या का योग है। |
| [DateTime](./) [AddYears](./addyears/)(int) const | एक नया [DateTime](./) क्लास का उदाहरण लौटाता है जो वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए मान के समान है, लेकिन वर्ष घटक को निर्दिष्ट संख्या से बढ़ाया जाता है। |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | निर्दिष्ट [DateTime](./) क्लास की दो उदाहरणों द्वारा प्रतिनिधित्व किए गए मानों की तुलना करता है और एक मान लौटाता है जो समयरेखा पर मानों की सापेक्ष स्थितियों को दर्शाता है। |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | वर्तमान वस्तु और निर्दिष्ट [DateTime](./) क्लास के उदाहरण द्वारा प्रतिनिधित्व किए गए दो तिथि और समय मानों की तुलना करता है और एक मान लौटाता है जो समयरेखा पर मानों की सापेक्ष स्थितियों को दर्शाता है। |
| constexpr [DateTime](./datetime/)() | एक उदाहरण बनाता है जो न्यूनतम संभव तिथि और समय मान का प्रतिनिधित्व करता है जो MinValue के बराबर है। |
|  [DateTime](./datetime/)(int, int, int) | एक उदाहरण बनाता है जो एक तिथि और समय मान का प्रतिनिधित्व करता है जिसे विशेष वर्ष, महीना और दिन के रूप में निर्दिष्ट किया गया है। |
|  [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | एक उदाहरण बनाता है जो एक तिथि और समय मान का प्रतिनिधित्व करता है जिसे निर्दिष्ट कैलेंडर में विशेष वर्ष, महीना और दिन के रूप में निर्दिष्ट किया गया है। |
|  [DateTime](./datetime/)(int, int, int, int, int, int) | एक उदाहरण बनाता है जो एक तिथि और समय मान का प्रतिनिधित्व करता है जिसे विशेष वर्ष, महीना, दिन, घंटे, मिनट और सेकंड के रूप में निर्दिष्ट किया गया है। |
|  [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | एक उदाहरण बनाता है जो एक तिथि और समय मान का प्रतिनिधित्व करता है जिसे विशेष वर्ष, महीना, दिन, घंटे, मिनट और सेकंड के रूप में निर्दिष्ट किया गया है। |
|  [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | एक उदाहरण बनाता है जो एक तिथि और समय मान का प्रतिनिधित्व करता है जिसे निर्दिष्ट कैलेंडर में विशेष वर्ष, महीना, दिन, घंटा, मिनट और सेकंड के रूप में निर्दिष्ट किया गया है। |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | एक उदाहरण बनाता है जो एक तिथि और समय मान का प्रतिनिधित्व करता है जिसे विशेष वर्ष, महीना, दिन, घंटा, मिनट, सेकंड और मिलीसेकंड के रूप में निर्दिष्ट किया गया है। |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | एक उदाहरण बनाता है जो एक तिथि और समय मान का प्रतिनिधित्व करता है जिसे निर्दिष्ट कैलेंडर में विशेष वर्ष, महीना, दिन, घंटा, मिनट, सेकंड और मिलीसेकंड के रूप में निर्दिष्ट किया गया है। |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | एक उदाहरण बनाता है जो टिक की संख्या के रूप में निर्दिष्ट तिथि और समय मान का प्रतिनिधित्व करता है। |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | एक उदाहरण बनाता है जो टिक की संख्या के रूप में निर्दिष्ट तिथि और समय मान का प्रतिनिधित्व करता है। आंतरिक उपयोग के लिए। |
|  [DateTime](./datetime/)(const [DateTime](./)\&) | एक उदाहरण की कॉपी-निर्माण करता है। |
| static int [DaysInMonth](./daysinmonth/)(int, int) | निर्दिष्ट वर्ष के निर्दिष्ट महीने में दिनों की संख्या लौटाता है। |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | निर्धारित करता है कि निर्दिष्ट [DateTime](./) क्लास की उदाहरण एक ही तिथि और समय मान का प्रतिनिधित्व करती हैं या नहीं। |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | निर्धारित करता है कि निर्दिष्ट [DateTime](./) क्लास का उदाहरण वर्तमान वस्तु के समान तिथि और समय मान का प्रतिनिधित्व करता है या नहीं। |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | निर्दिष्ट अनसाइंड 64-बिट पूर्णांक से दिनांक-समय मान को डीसीरियलाइज़ करता है और नई [DateTime](./) क्लास के उदाहरण को उस मान पर सेट करता है। |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | निर्दिष्ट फ़ाइल समय को [DateTime](./) क्लास के एक उदाहरण में परिवर्तित करता है जो स्थानीय समय के समान तिथि और समय मान का प्रतिनिधित्व करता है। |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | निर्दिष्ट फ़ाइल समय को [DateTime](./) क्लास के एक उदाहरण में परिवर्तित करता है जो UTC समय के समान तिथि और समय मान का प्रतिनिधित्व करता है। |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | निर्दिष्ट OLE ऑटोमेशन डेट के बराबर तिथि और समय मान का प्रतिनिधित्व करने वाला [DateTime](./) क्लास का एक उदाहरण लौटाता है। |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | निर्दिष्ट Unix समय मान को [DateTime](./) क्लास के एक उदाहरण में परिवर्तित करता है। आंतरिक उपयोग के लिए। |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | एक नया [DateTime](./) क्लास का उदाहरण लौटाता है जो वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए तिथि और समय का केवल तिथि भाग दर्शाता है, जहाँ समय भाग के सभी घटकों को 0 पर सेट किया जाता है। |
| int [get_Day](./get_day/)() const | वर्तमान वस्तु द्वारा दर्शाए गए महीने में दिन की क्रमिक संख्या लौटाता है। |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | वर्तमान वस्तु द्वारा दर्शाए गए सप्ताह के दिन को दर्शाने वाला मान लौटाता है। |
| int [get_DayOfYear](./get_dayofyear/)() const | वर्तमान वस्तु द्वारा दर्शाए गए वर्ष में दिन की क्रमिक संख्या लौटाता है। |
| constexpr int [get_Hour](./get_hour/)() const | वर्तमान वस्तु द्वारा दर्शाए गए तिथि और समय मान के घंटे घटक को लौटाता है। |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | वर्तमान वस्तु द्वारा दर्शाए गए तिथि और समय के स्थानीय या UTC होने या न होने को दर्शाने वाला मान लौटाता है। |
| constexpr int [get_Millisecond](./get_millisecond/)() const | वर्तमान वस्तु द्वारा दर्शाए गए तिथि और समय मान के मिलीसेकंड घटक को लौटाता है। |
| constexpr int [get_Minute](./get_minute/)() const | वर्तमान वस्तु द्वारा दर्शाए गए तिथि और समय मान के मिनट घटक को लौटाता है। |
| int [get_Month](./get_month/)() const | वर्तमान वस्तु द्वारा दर्शाए गए वर्ष में महीने की क्रमिक संख्या लौटाता है। |
| static [DateTime](./) [get_Now](./get_now/)() | एक [DateTime](./) क्लास का उदाहरण लौटाता है जो वर्तमान समय को स्थानीय समय के रूप में दर्शाता है। |
| constexpr int [get_Second](./get_second/)() const | वर्तमान वस्तु द्वारा दर्शाए गए तिथि और समय मान के सेकंड घटक को लौटाता है। |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | वर्तमान वस्तु द्वारा दर्शाए गए तिथि और समय तक ग्रीगोरियन कैलेंडर में 1 जनवरी 0001, 0:00:00 UTC से बीते 100-नैनोसेकंड अंतराल की संख्या लौटाता है। |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | वर्तमान वस्तु द्वारा दर्शाए गए दिन की शुरुआत से लेकर वर्तमान वस्तु द्वारा दर्शाए गए तिथि और समय मान तक के समय अंतराल को दर्शाने वाला मान लौटाता है। |
| static [DateTime](./) [get_Today](./get_today/)() | एक [DateTime](./) क्लास का उदाहरण लौटाता है जो वर्तमान तिथि को दर्शाता है, जिसमें वस्तु द्वारा प्रदर्शित मान के समय भाग के सभी घटकों को 0 पर सेट किया गया है। |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | एक [DateTime](./) क्लास का उदाहरण लौटाता है जो वर्तमान समय को UTC के रूप में दर्शाता है। |
| int [get_Year](./get_year/)() const | वर्तमान वस्तु द्वारा दर्शाए गए वर्ष को लौटाता है। |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | तिथि के भाग प्राप्त करता है। आंतरिक उपयोग के लिए। |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | स्ट्रिंग्स का एक एरे लौटाता है जहाँ प्रत्येक तत्व वर्तमान वस्तु का स्ट्रिंग प्रतिनिधित्व होता है, जो मानक तिथि और समय स्वरूप संकेतकों में से एक के साथ स्वरूपित है। |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | स्ट्रिंग्स का एक एरे लौटाता है जहाँ प्रत्येक तत्व वर्तमान वस्तु का स्ट्रिंग प्रतिनिधित्व होता है, जो निर्दिष्ट मानक तिथि और समय स्वरूप संकेतक के साथ स्वरूपित है। |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | स्ट्रिंग्स का एक एरे लौटाता है जहाँ प्रत्येक तत्व वर्तमान वस्तु का स्ट्रिंग प्रतिनिधित्व होता है, जो मानक तिथि और समय स्वरूप संकेतकों में से एक और निर्दिष्ट फॉर्मेट प्रोवाइडर के साथ स्वरूपित है। |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | स्ट्रिंग्स का एक एरे लौटाता है जहाँ प्रत्येक तत्व वर्तमान वस्तु का स्ट्रिंग प्रतिनिधित्व होता है, जो निर्दिष्ट मानक तिथि और समय स्वरूप संकेतक और फॉर्मेट प्रोवाइडर के साथ स्वरूपित है। |
| int [GetHashCode](./gethashcode/)() const | वर्तमान वस्तु के लिए एक हैश कोड लौटाता है। |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | निर्धारित करता है कि क्या वर्तमान वस्तु द्वारा दर्शाए गए तिथि और समय मान वर्तमान समयक्षेत्र के डेलाइट सेविंग टाइम रेंज में आता है। |
| static **bool** [IsLeapYear](./isleapyear/)(int) | निर्धारित करता है कि निर्दिष्ट वर्ष लीप वर्ष है या नहीं। |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | निर्धारित करता है कि वर्तमान वस्तु और निर्दिष्ट [DateTime](./) वस्तु अलग-अलग तिथि और समय मान का प्रतिनिधित्व करती हैं या नहीं। |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | एक नया [DateTime](./) क्लास का उदाहरण लौटाता है जो तिथि और समय मान का प्रतिनिधित्व करता है जो वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए मान और निर्दिष्ट समय अंतराल के योग के बराबर है। |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | वर्तमान वस्तु को उस तिथि और समय मान पर सेट करता है जो वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए मान और निर्दिष्ट समय अंतराल के योग के बराबर है। |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | एक नया [DateTime](./) क्लास का उदाहरण लौटाता है जो तिथि और समय मान का प्रतिनिधित्व करता है जो वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए मान से निर्दिष्ट समय अंतराल घटाने के परिणामस्वरूप प्राप्त होता है। |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | एक [TimeSpan](../timespan/) क्लास का उदाहरण लौटाता है जो वर्तमान और निर्दिष्ट वस्तुओं द्वारा प्रतिनिधित्व किए गए तिथि और समय मानों के बीच समय अंतराल का प्रतिनिधित्व करता है। |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | वर्तमान वस्तु को उस तिथि और समय मान पर सेट करता है जो वर्तमान वस्तु द्वारा दर्शाए गए तिथि और समय मान से निर्दिष्ट समय अंतराल घटाने के परिणामस्वरूप प्राप्त होता है। |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | निर्धारित करता है कि क्या वर्तमान वस्तु द्वारा दर्शाए गए तिथि और समय मान, निर्दिष्ट [DateTime](./) वस्तु द्वारा प्रतिनिधित्व किए गए मान से पहले है। |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | निर्धारित करता है कि क्या वर्तमान वस्तु द्वारा दर्शाए गए तिथि और समय मान, निर्दिष्ट [DateTime](./) वस्तु द्वारा प्रतिनिधित्व किए गए मान से पहले या समान है। |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | निर्दिष्ट [DateTime](./) उदाहरण द्वारा प्रतिनिधित्व किए गए मान को वर्तमान वस्तु को सौंपता है। |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | निर्धारित करता है कि क्या वर्तमान वस्तु और निर्दिष्ट [DateTime](./) वस्तु एक ही तिथि और समय मान का प्रतिनिधित्व करती हैं। |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | निर्धारित करता है कि वर्तमान वस्तु वह तिथि-समय मान दर्शाती है जो निर्दिष्ट [DateTime](./) वस्तु द्वारा दर्शाए गए मान से बाद में है। |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | निर्धारित करता है कि वर्तमान वस्तु वह तिथि-समय मान दर्शाती है जो निर्दिष्ट [DateTime](./) वस्तु द्वारा दर्शाए गए मान से बाद में या समान है। |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | निर्दिष्ट तिथि-समय मान की स्ट्रिंग अभिव्यक्ति को समान [DateTime](./) वस्तु में परिवर्तित करता है। |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग कर निर्दिष्ट तिथि-समय मान की स्ट्रिंग अभिव्यक्ति को समान [DateTime](./) वस्तु में परिवर्तित करता है। |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | निर्दिष्ट फ़ॉर्मेट और संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी का उपयोग कर निर्दिष्ट तिथि-समय मान की स्ट्रिंग अभिव्यक्ति को समान [DateTime](./) वस्तु में परिवर्तित करता है। स्ट्रिंग अभिव्यक्ति का फ़ॉर्मेट बिल्कुल निर्दिष्ट फ़ॉर्मेट से मेल खाना चाहिए। यदि परिवर्तन विफल होता है तो यह अपवाद फेंकता है। |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | निर्दिष्ट फ़ॉर्मेट्स, संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी और शैली का उपयोग कर निर्दिष्ट तिथि-समय मान की स्ट्रिंग अभिव्यक्ति को समान [DateTime](./) वस्तु में परिवर्तित करता है। स्ट्रिंग अभिव्यक्ति का फ़ॉर्मेट निर्दिष्ट फ़ॉर्मेट्स में से एक या अधिक के साथ बिल्कुल मेल खाना चाहिए। यदि परिवर्तन विफल होता है तो यह अपवाद फेंकता है। |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | निर्दिष्ट [DateTime](./) वस्तु के समान टिक संख्या दर्शाने वाला एक नया [DateTime](./) वस्तु बनाता है और **kind** तर्क द्वारा निर्दिष्ट अनुसार स्थानीय समय, UTC समय या कोई नहीं दर्शाता है। |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | वर्तमान वस्तु द्वारा दर्शाए गए मान से निर्दिष्ट समय अंतराल को घटाने के परिणामस्वरूप तिथि-समय मान को दर्शाने वाला [DateTime](./) वर्ग का नया उदाहरण लौटाता है। |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | वर्तमान और निर्दिष्ट वस्तुओं द्वारा दर्शाए गए तिथि-समय मानों के बीच के समय अंतराल को दर्शाने वाला [TimeSpan](../timespan/) वर्ग का एक उदाहरण लौटाता है। |
| **int64_t** [ToBinary](./tobinary/)() const | वर्तमान वस्तु को क्रमबद्ध (सीरियलाइज़) करता है। |
| **int64_t** [ToFileTime](./tofiletime/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए तिथि-समय मान को फ़ाइल समय के रूप में दर्शाने वाला मान लौटाता है। |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए तिथि-समय मान को फ़ाइल समय UTC में परिवर्तित करता है। |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | वर्तमान वस्तु द्वारा दर्शाए गए तिथि-समय मान को स्थानीय समय के रूप में दर्शाने वाला [DateTime](./) वर्ग का नया उदाहरण लौटाता है। |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | वर्तमान वस्तु की लंबी तिथि स्ट्रिंग अभिव्यक्ति युक्त स्ट्रिंग लौटाता है। |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | वर्तमान वस्तु की लंबी समय स्ट्रिंग अभिव्यक्ति युक्त स्ट्रिंग लौटाता है। |
| **double** [ToOADate](./tooadate/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए तिथि-समय मान को OLE ऑटोमेशन तिथि के रूप में लौटाता है। |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | वर्तमान वस्तु की संक्षिप्त तिथि स्ट्रिंग अभिव्यक्ति युक्त स्ट्रिंग लौटाता है। |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | वर्तमान वस्तु की संक्षिप्त समय स्ट्रिंग अभिव्यक्ति युक्त स्ट्रिंग लौटाता है। |
| [String](../string/) [ToString](./tostring/)() const | वर्तमान संस्कृति द्वारा निर्धारित स्वरूपण मानकों का उपयोग कर वर्तमान वस्तु द्वारा दर्शाए गए तिथि-समय मान की स्ट्रिंग अभिव्यक्ति लौटाता है। |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | निर्दिष्ट फ़ॉर्मेट और वर्तमान संस्कृति द्वारा निर्धारित स्वरूपण मानकों का उपयोग कर वर्तमान वस्तु द्वारा दर्शाए गए तिथि-समय मान की स्ट्रिंग अभिव्यक्ति लौटाता है। |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | निर्दिष्ट फ़ॉर्मेट जानकारी का उपयोग कर वर्तमान वस्तु द्वारा दर्शाए गए तिथि-समय मान की स्ट्रिंग अभिव्यक्ति लौटाता है। |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | निर्दिष्ट फ़ॉर्मेट जानकारी का उपयोग कर वर्तमान वस्तु द्वारा दर्शाए गए तिथि-समय मान की स्ट्रिंग अभिव्यर्ति लौटाता है। |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | वर्तमान वस्तु द्वारा दर्शाए गए तिथि-समय मान को UTC के रूप में दर्शाने वाला [DateTime](./) वर्ग का नया उदाहरण लौटाता है। |
| time_t [ToUnixTime](./tounixtime/)() const | वर्तमान वस्तु द्वारा दर्शाए गए तिथि-समय मान को यूनिक्स समय के रूप में दर्शाने वाला मान लौटाता है। FOR INTERNAL USE. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | निर्दिष्ट तिथि-समय मान की स्ट्रिंग अभिव्यत्ति को समान [DateTime](./) वस्तु में परिवर्तित करता है। |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | निर्दिष्ट संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी और शैली का उपयोग कर निर्दिष्ट तिथि-समय मान की स्ट्रिंग अभिव्यत्ति को समान [DateTime](./) वस्तु में परिवर्तित करता है। |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | निर्दिष्ट फ़ॉर्मेट, संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी और शैली का उपयोग कर निर्दिष्ट तिथि-समय मान की स्ट्रिंग अभिव्यत्ति को समान [DateTime](./) वस्तु में परिवर्तित करता है। स्ट्रिंग अभिव्यत्ति का फ़ॉर्मेट बिल्कुल निर्दिष्ट फ़ॉर्मेट से मेल खाना चाहिए। |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | निर्दिष्ट फ़ॉर्मेट्स, संस्कृति-विशिष्ट फ़ॉर्मेट जानकारी और शैली का उपयोग कर निर्दिष्ट तिथि-समय मान की स्ट्रिंग अभिव्यत्ति को समान [DateTime](./) वस्तु में परिवर्तित करता है। स्ट्रिंग अभिव्यत्ति का फ़ॉर्मेट निर्दिष्ट फ़ॉर्मेट्स में से एक या अधिक के साथ बिल्कुल मेल खाना चाहिए। |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | इस वर्ग के बारे में जानकारी युक्त एक [TypeInfo](../typeinfo/) वस्तु लौटाता है। |

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | न्यूनतम संभव और अधिकतम संभव [DateTime](./) मान के बीच समय अंतराल में 100-नैनोसेकंड की संख्या। |
| static [MaxValue](./maxvalue/) | अधिकतम संभव तिथि-समय मान को दर्शाने वाला [DateTime](./) वर्ग का एक उदाहरण। |
| static constexpr [MinTicks](./minticks/) | [DateTime](./) वर्ग की एक उदाहरण द्वारा प्रतिनिधित्व किए जा सकने वाले न्यूनतम टिक संख्या। |
| static [MinValue](./minvalue/) | न्यूनतम संभव तिथि-समय मान को दर्शाने वाला [DateTime](./) वर्ग का एक उदाहरण। |
| static constexpr [TicksPerDay](./ticksperday/) | एक दिन में टिक संख्या। |
| static constexpr [TicksPerHour](./ticksperhour/) | एक घंटे में टिक संख्या। |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | एक माइक्रोसेकंड में टिक संख्या। |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | एक मिलीसेकंड में टिक संख्या। |
| static constexpr [TicksPerMinute](./ticksperminute/) | एक मिनट में टिक संख्या। |
| static constexpr [TicksPerSecond](./tickspersecond/) | एक सेकंड में टिक संख्या। |
| static [UnixEpoch](./unixepoch/) | Unix एपोच की शुरुआत (1970.01.01 00:00:00) को दर्शाने वाला [DateTime](./) वर्ग का एक उदाहरण। |

## टिप्पणी

```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // 'DateTime' क्लास का इंस्टेंस बनाएं।
  DateTime dateTime{1990, 10, 30};

  // इंस्टेंस को कई फॉर्मेट्स में प्रिंट करें।
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## देखिए

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)