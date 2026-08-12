---
title: StringFormat()
second_title: Aspose.Slides for C++ API संदर्भ
description: StringFormat क्लास का नया उदाहरण बनाता है।
type: docs
weight: 1
url: /hi/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() कंस्ट्रक्टर

एक नया उदाहरण बनाता है [StringFormat](../) क्लास का।

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) कंस्ट्रक्टर

निर्दिष्ट फ़ॉर्मेट फ़्लैग्स और भाषा के साथ [StringFormat](../) क्लास का एक नया उदाहरण बनाता है।

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | एक बिटवाइज़ संयोजन जो StringFormatFlags enum मान को निर्दिष्ट करता है जिसे बनाए जा रहे ऑब्जेक्ट द्वारा प्रतिनिधित्व किया जाएगा |
| language | **int32_t** | पाठ की भाषा |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) कंस्ट्रक्टर

कॉपी कंस्ट्रक्टर।

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | [StringFormat](../) ऑब्जेक्ट जिससे कॉपी किया जाना है |

## See Also

* Enum [StringFormatFlags](../../stringformatflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringFormat](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)