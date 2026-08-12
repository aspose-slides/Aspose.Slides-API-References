---
title: XmlPreloadedResolver()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: XmlPreloadedResolver क्लास का नया उदाहरण इनिशियलाइज़ करता है।
type: docs
weight: 27
url: /hi/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() constructor

एक नया उदाहरण बनाता है [XmlPreloadedResolver](../) क्लास का।

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) constructor

एक नया उदाहरण बनाता है [XmlPreloadedResolver](../) क्लास का, निर्दिष्ट पूर्व-लोड किए गए ज्ञात DTDs के साथ।

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | वह ज्ञात DTDs जिन्हें कैश में पूर्व-लोड किया जाना चाहिए। |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) constructor

एक नया उदाहरण बनाता है [XmlPreloadedResolver](../) क्लास का, निर्दिष्ट फ़ॉलबैक रिज़ॉल्वर के साथ।

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | वह [XmlResolver](../../../system.xml/xmlresolver/) या आपका स्वयं का रिज़ॉल्वर। |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) constructor

एक नया उदाहरण बनाता है [XmlPreloadedResolver](../) क्लास का, निर्दिष्ट फ़ॉलबैक रिज़ॉल्वर और पूर्व-लोड किए गए ज्ञात DTDs के साथ।

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | वह [XmlResolver](../../../system.xml/xmlresolver/) या आपका स्वयं का रिज़ॉल्वर। |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | वह ज्ञात DTDs जिन्हें कैश में पूर्व-लोड किया जाना चाहिए। |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) constructor

एक नया उदाहरण बनाता है [XmlPreloadedResolver](../) क्लास का, निर्दिष्ट फ़ॉलबैक रिज़ॉल्वर, पूर्व-लोड किए गए ज्ञात DTDs और URI समानता तुलनाकर्ता के साथ।

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | वह [XmlResolver](../../../system.xml/xmlresolver/) या आपका स्वयं का रिज़ॉल्वर। |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | वह ज्ञात DTDs जिन्हें कैश में पूर्व-लोड किया जाना चाहिए। |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | URI की तुलना करने के लिए उपयोग किया जाने वाला IEqualityComparer इंटरफ़ेस का कार्यान्वयन। |

## See Also

* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlPreloadedResolver](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Class [Uri](../../../system/uri/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)