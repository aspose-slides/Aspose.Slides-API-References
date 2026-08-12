---
title: XmlParserContext()
second_title: Aspose.Slides for C++ API संदर्भ
description: "निर्दिष्ट XmlNameTable, XmlNamespaceManager, xml:lang, और xml:space मानों के साथ XmlParserContext क्लास का नया उदाहरण प्रारम्भ करता है।"
type: docs
weight: 261
url: /hi/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) constructor

[XmlParserContext](../) क्लास का नया उदाहरण निर्दिष्ट [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, और **xml:space** मानों के साथ प्रारम्भ करता है।

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | स्ट्रिंग्स को एटॉमिक करने के लिए उपयोग किया जाने वाला [XmlNameTable](../../xmlnametable/)। यदि यह **nullptr** है, तो **nsMgr** बनाने के लिए उपयोग की गई नाम तालिका उपयोग की जाएगी। एटॉमिक स्ट्रिंग्स के बारे में अधिक जानकारी के लिए, देखें [XmlNameTable](../../xmlnametable/)। |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | नामस्थान जानकारी खोजने के लिए उपयोग किया गया [XmlNamespaceManager](../../xmlnamespacemanager/), या **nullptr**। |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** दायरा। |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | एक XmlSpace मान जो **xml:space** दायरा दर्शाता है। |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor

[XmlParserContext](../) क्लास का नया उदाहरण निर्दिष्ट [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space**, और एन्कोडिंग के साथ प्रारम्भ करता है।

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | स्ट्रिंग्स को एटॉमिक करने के लिए उपयोग किया जाने वाला [XmlNameTable](../../xmlnametable/)। यदि यह **nullptr** है, तो **nsMgr** बनाने के लिए उपयोग की गई नाम तालिका उपयोग की जाएगी। एटॉमिक स्ट्रिंग्स के बारे में अधिक जानकारी के लिए, देखें [XmlNameTable](../../xmlnametable/)। |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | नामस्थान जानकारी खोजने के लिए उपयोग किया गया [XmlNamespaceManager](../../xmlnamespacemanager/), या **nullptr**। |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** दायरा। |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | एक XmlSpace मान जो **xml:space** दायरा दर्शाता है। |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | एन्कोडिंग सेटिंग को दर्शाने वाला Encoding वस्तु। |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) constructor

[XmlParserContext](../) क्लास का नया उदाहरण निर्दिष्ट [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), बेस URI, **xml:lang**, **xml:space**, और दस्तावेज़ प्रकार मानों के साथ प्रारम्भ करता है।

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | स्ट्रिंग्स को एटॉमिक करने के लिए उपयोग किया जाने वाला [XmlNameTable](../../xmlnametable/)। यदि यह **nullptr** है, तो **nsMgr** बनाने के लिए उपयोग की गई नाम तालिका उपयोग की जाएगी। एटॉमिक स्ट्रिंग्स के बारे में अधिक जानकारी के लिए, देखें [XmlNameTable](../../xmlnametable/)। |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | नामस्थान जानकारी खोजने के लिए उपयोग किया गया [XmlNamespaceManager](../../xmlnamespacemanager/), या **nullptr**। |
| docTypeName | const [String](../../../system/string/)\& | डॉक्यूमेंट टाइप घोषणा का नाम। |
| pubId | const [String](../../../system/string/)\& | पब्लिक पहचानकर्ता। |
| sysId | const [String](../../../system/string/)\& | सिस्टम पहचानकर्ता। |
| internalSubset | const [String](../../../system/string/)\& | आंतरिक DTD उपसमुच्चय। DTD उपसमुच्चय एंटिटी रिज़ॉल्यूशन के लिए उपयोग किया जाता है, दस्तावेज़ मान्यकरण के लिए नहीं। |
| baseURI | const [String](../../../system/string/)\& | XML फ्रैगमेंट के लिए बेस URI (वह स्थान जहाँ से फ्रैगमेंट लोड किया गया था)। |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** दायरा। |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | एक XmlSpace मान जो **xml:space** दायरा दर्शाता है। |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor

[XmlParserContext](../) क्लास का नया उदाहरण निर्दिष्ट [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), बेस URI, **xml:lang**, **xml:space**, एन्कोडिंग, और दस्तावेज़ प्रकार मानों के साथ प्रारम्भ करता है।

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | स्ट्रिंग्स को एटॉमिक करने के लिए उपयोग किया जाने वाला [XmlNameTable](../../xmlnametable/)। यदि यह **nullptr** है, तो **nsMgr** बनाने के लिए उपयोग की गई नाम तालिका उपयोग की जाएगी। एटॉमिक स्ट्रिंग्स के बारे में अधिक जानकारी के लिए, देखें [XmlNameTable](../../xmlnametable/)। |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | नामस्थान जानकारी खोजने के लिए उपयोग किया गया [XmlNamespaceManager](../../xmlnamespacemanager/), या **nullptr**। |
| docTypeName | const [String](../../../system/string/)\& | डॉक्यूमेंट टाइप घोषणा का नाम। |
| pubId | const [String](../../../system/string/)\& | पब्लिक पहचानकर्ता। |
| sysId | const [String](../../../system/string/)\& | सिस्टम पहचानकर्ता। |
| internalSubset | const [String](../../../system/string/)\& | आंतरिक DTD उपसमुच्चय। DTD एंटिटी रिज़ॉल्यूशन के लिए उपयोग किया जाता है, दस्तावेज़ मान्यकरण के लिए नहीं। |
| baseURI | const [String](../../../system/string/)\& | XML फ्रैगमेंट के लिए बेस URI (वह स्थान जहाँ से फ्रैगमेंट लोड किया गया था)। |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** दायरा। |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | एक XmlSpace मान जो **xml:space** दायरा दर्शाता है। |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | एन्कोडिंग सेटिंग को दर्शाने वाला Encoding वस्तु। |

## संबंधित देखें

* Enum [XmlSpace](../../xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlNameTable](../../xmlnametable/)
* क्लास [XmlNamespaceManager](../../xmlnamespacemanager/)
* क्लास [String](../../../system/string/)
* क्लास [XmlParserContext](../)
* क्लास [Encoding](../../../system.text/encoding/)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)