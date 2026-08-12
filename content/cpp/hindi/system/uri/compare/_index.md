---
title: Compare()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट Uri वस्तुओं की तुलना निर्दिष्ट तुलना नियमों का उपयोग करके करता है।
type: docs
weight: 521
url: /hi/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) विधि

निर्दिष्ट [Uri](../) वस्तुओं की तुलना निर्दिष्ट तुलना नियमों का उपयोग करके करता है।

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | पहला तुलना किया गया मान |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | दूसरा तुलना किया गया मान |
| partsToCompare | [UriComponents](../../uricomponents/) | **uri1** और **uri2** के उन भागों को निर्दिष्ट करता है जिन्हें तुलना की जानी है |
| compareFormat | [UriFormat](../../uriformat/) | URIs के घटकों की तुलना करते समय उपयोग किए जाने वाले कैरेक्टर एस्केपिंग को निर्दिष्ट करता है |
| comparisonType | [StringComparison](../../stringcomparison/) | StringComparison मानों में से एक |

### रिटर्न वैल्यू

**uri1** यदि **uri2** से छोटा हो तो नकारात्मक मान; यदि uri1 और uri2 बराबर हों तो 0; यदि **uri1** **uri2** से बड़ा हो तो सकारात्मक मान

## देखें

* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)