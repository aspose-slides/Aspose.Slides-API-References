---
title: FieldAttributes
second_title: Aspose.Slides for C++ API संदर्भ
description: परावर्तित फ़ील्ड विशेषताएँ।
type: docs
weight: 170
url: /hi/system.reflection/fieldattributes/
---
## FieldAttributes enum


परावर्तित फ़ील्ड विशेषताएँ।

```cpp
enum class FieldAttributes
```

### Values

| नाम | मान | विवरण |
| --- | --- | --- |
| FieldAccessMask | 7 | सदस्य पहुंच मास्क। इस मास्क का उपयोग पहुंच जानकारी प्राप्त करने के लिए किया जाता है। |
| PrivateScope | 0 | गैर-संदर्भ योग्य सदस्य। |
| Private | 1 | निजी सदस्य। |
| FamANDAssem | 2 | निजी और असेंबली-स्कोप वाले सदस्य। |
| Assembly | 3 | असेंबली-स्कोप वाले सदस्य। |
| Family | 4 | सदस्य जो प्रकार और उपप्रकारों द्वारा सुलभ हैं। |
| FamORAssem | 5 | सदस्य जो प्रकार, उप-प्रकार और असेंबली द्वारा सुलभ हैं। |
| Public | 6 | सदस्य जो किसी भी व्यक्ति द्वारा सुलभ हैं। |
| Static | 16 | स्टैटिक सदस्य, जो इंस्टेंस सदस्यों के विपरीत हैं। |
| InitOnly | 32 | स्थिरांक सदस्य जो केवल आरंभ किए जा सकते हैं लेकिन बदले नहीं जा सकते। |
| Literal | 64 | संकलन समय स्थिरांक सदस्य। |
| NotSerialized | 128 | गैर-सीरियलाइज़्ड सदस्य। |
| SpecialName | 512 | नीचे दिए गए नामों में से एक का विशेष फ़ील्ड। |
| PinvokeImpl | 8192 | इंटरऑप फॉरवर्डेड कार्यान्वयन। |
| ReservedMask | 38144 | केवल रनटाइम उपयोग के लिए आरक्षित फ़्लैग। |
| RTSpecialName | 1024 | रनटाइम को नाम एन्कोडिंग जाँचनी चाहिए। |
| HasFieldMarshal | 4096 | मार्शलिंग जानकारी मौजूद है। |
| HasDefault | 32768 | डिफ़ॉल्ट मान मौजूद है। |
| HasFieldRVA | 256 | RVA मौजूद है। |

## See Also

* नेमस्पेस [System::Reflection](../)
* लाइब्रेरी [Aspose.Slides](../../)