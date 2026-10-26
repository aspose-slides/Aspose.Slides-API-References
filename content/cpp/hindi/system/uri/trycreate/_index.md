---
title: TryCreate()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट URI का प्रतिनिधित्व करने वाला Uri ऑब्जेक्ट बनाता है; एक तर्क URI प्रकार को निर्दिष्ट करता है।
type: docs
weight: 508
url: /hi/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) विधि

निर्दिष्ट URI का प्रतिनिधित्व करने वाला [Uri](../) ऑब्जेक्ट बनाता है; एक तर्क URI प्रकार को निर्दिष्ट करता है।

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | वह स्ट्रिंग URI जो निर्मित किए जा रहे ऑब्जेक्ट द्वारा दर्शाया जाएगा |
| uriKind | [UriKind](../../urikind/) | URI प्रकार को निर्दिष्ट करता है |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | आउटपुट तर्क जो, यदि निर्माण सफल हो, विधि के रिटर्न पर नव निर्मित [Uri](../) ऑब्जेक्ट की ओर संकेत करता है |

### रिटर्न मान

यदि निर्माण सफल हो तो true, अन्यथा false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) विधि

निर्दिष्ट [Uri](../) ऑब्जेक्ट (जो बेस URI का प्रतिनिधित्व करता है) और रिलेटिव URI की स्ट्रिंग प्रतिनिधित्व से [Uri](../) ऑब्जेक्ट बनाता है।

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | बेस URI |
| relativeUri | const [String](../../string/)\& | रिलेटिव URI जिसे बेस URI में जोड़ा जाता है |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | आउटपुट तर्क जो, यदि निर्माण सफल हो, विधि के रिटर्न पर नव निर्मित [Uri](../) ऑब्जेक्ट की ओर संकेत करता है |

### रिटर्न मान

यदि निर्माण सफल हो तो true, अन्यथा false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) विधि

निर्दिष्ट बेस और रिलेटिव URIs से [Uri](../) ऑब्जेक्ट बनाता है।

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | बेस URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | रिलेटिव URI जिसे बेस URI में जोड़ा जाता है |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | आउटपुट तर्क जो, यदि निर्माण सफल हो, विधि के रिटर्न पर नव निर्मित [Uri](../) ऑब्जेक्ट की ओर संकेत करता है |

### रिटर्न मान

यदि निर्माण सफल हो तो true, अन्यथा false

## संबंधित देखें

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)