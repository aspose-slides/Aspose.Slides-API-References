---
title: CompareDocument()
second_title: Aspose.Slides for C++ API संदर्भ
description: जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो दो दस्तावेज़ों के बेस यूनिफ़ॉर्म रिसोर्स आइडेंटिफ़ायर (URIs) की तुलना करता है, यह इस आधार पर कि दस्तावेज़ XSLT प्रोसेसर द्वारा किस क्रम में लोड किए गए थे (अर्थात, XslTransform क्लास)।
type: docs
weight: 53
url: /hi/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) मेथड

जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो दो दस्तावेज़ों के बेस यूनिफ़ॉर्म रिसोर्स आइडेंटिफ़ायर (URIs) की तुलना करता है, यह इस आधार पर कि दस्तावेज़ XSLT प्रोसेसर द्वारा किस क्रम में लोड किए गए थे (अर्थात, [XslTransform](../../xsltransform/) क्लास)।

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | तुलना करने के लिए पहले दस्तावेज़ का बेस URI। |
| nextbaseUri | [String](../../../system/string/) | तुलना करने के लिए दूसरे दस्तावेज़ का बेस URI। |

### रिटर्न मान

एक पूर्णांक मान जो दो बेस URIs के सापेक्ष क्रम का वर्णन करता है: -1 यदि **baseUri** **nextbaseUri** से पहले आता है; 0 यदि दोनों बेस URIs समान हैं; और 1 यदि **baseUri** **nextbaseUri** के बाद आता है।

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XsltContext](../)
* नेमस्पेस [System::Xml::Xsl](../../)
* लाइब्रेरी [Aspose.Slides](../../../)