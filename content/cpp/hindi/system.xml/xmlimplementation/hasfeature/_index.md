---
title: HasFeature()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: जांच करता है कि दस्तावेज़ ऑब्जेक्ट मॉडल (DOM) कार्यान्वयन एक विशिष्ट सुविधा को लागू करता है या नहीं।
type: docs
weight: 14
url: /hi/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String\&, const String\&) मेथड

यदि दस्तावेज़ [Object](../../../system/object/) मॉडल (DOM) कार्यान्वयन एक विशिष्ट सुविधा को लागू करता है तो परीक्षण करता है।

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)\& | परीक्षण हेतु सुविधा का पैकेज नाम। यह नाम केस-सेंसिटिव नहीं है। |
| strVersion | const [String](../../../system/string/)\& | परीक्षण हेतु पैकेज नाम का संस्करण संख्या। यदि संस्करण निर्दिष्ट नहीं किया गया है (**nullptr**), तो सुविधा के किसी भी संस्करण का समर्थन करने पर मेथड **true** लौटाता है। |

### रिटर्न वैल्यू

**true** यदि निर्दिष्ट संस्करण में सुविधा लागू है; अन्यथा **false**।

## टिप्पणियाँ

निम्न तालिका उन संयोजनों को दिखाती है जो **HasFeature** को **true** लौटाने का कारण बनते हैं।

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlImplementation](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)