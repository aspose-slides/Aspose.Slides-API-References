---
title: CreateXmlDeclaration()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट मानों के साथ एक XmlDeclaration नोड बनाता है।
type: docs
weight: 378
url: /hi/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String&, const String&, const String&) मेथड


निर्दिष्ट मानों के साथ एक [XmlDeclaration](../../xmldeclaration/) नोड बनाता है।

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```


### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| version | const [String](../../../system/string/)& | संस्करण \"1.0\" होना चाहिए। |
| encoding | const [String](../../../system/string/)& | एन्कोडिंग एट्रिब्यूट का मान। यह वह एन्कोडिंग है जो आपके द्वारा [XmlDocument](../) को फ़ाइल या स्ट्रीम में सहेजते समय उपयोग की जाती है; इसलिए, इसे [Text::Encoding](../../../system.text/encoding/) क्लास द्वारा समर्थित स्ट्रिंग पर सेट किया जाना चाहिए, अन्यथा \"XmlDocument::Save(String)\" विफल होता है। यदि यह **nullptr** या [String::Empty](../../../system/string/empty/) है, तो [XmlDocument::Save](../save/) मेथड XML घोषणा पर एन्कोडिंग एट्रिब्यूट नहीं लिखता और इसलिए डिफ़ॉल्ट एन्कोडिंग, UTF-8, उपयोग की जाती है। |
| standalone | const [String](../../../system/string/)& | मान \"yes\" या \"no\" में से कोई एक होना चाहिए। यदि यह **nullptr** या [String::Empty](../../../system/string/empty/) है, तो [XmlDocument::Save](../save/) मेथड XML घोषणा पर स्टैंडअलोन एट्रिब्यूट नहीं लिखता। |

### Return Value

नया [XmlDeclaration](../../xmldeclaration/) नोड।

## Remarks



ध्यान दें: यदि [XmlDocument](../) को TextWriter या [XmlTextWriter](../../xmltextwriter/) में सहेजा जाता है, तो यह एन्कोडिंग मान हटाया जाता है। इसके बजाय, TextWriter या [XmlTextWriter](../../xmltextwriter/) की एन्कोडिंग उपयोग की जाती है। यह सुनिश्चित करता है कि आउटपुट XML को सही एन्कोडिंग का उपयोग करके फिर पढ़ा जा सके। 

## See Also

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlDeclaration](../../xmldeclaration/)
* क्लास [String](../../../system/string/)
* क्लास [XmlDocument](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)