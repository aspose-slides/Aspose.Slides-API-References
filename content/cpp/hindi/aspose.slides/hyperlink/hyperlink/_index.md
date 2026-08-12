---
title: Hyperlink()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: हाइपरलिंक का एक उदाहरण बनाता है।
type: docs
weight: 339
url: /hi/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) कंस्ट्रक्टर

हाइपरलिंक का एक इनस्टेंस बनाता है।

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL। |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) कंस्ट्रक्टर

एक हाइपरलिंक का इनस्टेंस बनाता है जो विशिष्ट स्लाइड की ओर इशारा करता है। नोट: निर्मित हाइपरलिंक को वही प्रेजेंटेशन के किसी ऑब्जेक्ट को असाइन किया जाना चाहिए, अन्यथा लिंक NoAction के रूप में सहेजा जाएगा।

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | लक्ष्य स्लाइड। |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) कंस्ट्रक्टर

एक हाइपरलिंक का इनस्टेंस बनाता है जिसमें स्रोत के रूप में अन्य हाइपरलिंक उपयोग किया जाता है, द्वितीयक गुणों को ओवरराइड करते हुए।

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | स्रोत हाइपरलिंक |
| targetFrame | [System::String](../../../system/string/) | लक्ष्य फ्रेम |
| tooltip | [System::String](../../../system/string/) | टूलटिप टेक्स्ट |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [Hyperlink](../)
* क्लास [ISlide](../../islide/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)