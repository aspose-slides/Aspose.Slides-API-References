---
title: InsertClone()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक निर्दिष्ट मास्टर स्लाइड की प्रति संग्रह में निर्दिष्ट स्थान पर जोड़ता है। जुड़े हुए लेआउट स्लाइड भी कॉपी हो जाएंगे।
type: docs
weight: 66
url: /hi/aspose.slides/imasterslidecollection/insertclone/
---
## IMasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) विधि

एक निर्दिष्ट मास्टर स्लाइड की प्रति निर्दिष्ट स्थिति पर संग्रह में जोड़ता है। जुड़े हुए लेआउट स्लाइड भी कॉपी हो जाएंगे।

```cpp
virtual System::SharedPtr<IMasterSlide> Aspose::Slides::IMasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster)=0
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | नए स्लाइड का सूचकांक। |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) को क्लोन करने के लिए। |

### रिटर्न मान

डाली गई मास्टर स्लाइड।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMasterSlide](../../imasterslide/)
* क्लास [IMasterSlideCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)