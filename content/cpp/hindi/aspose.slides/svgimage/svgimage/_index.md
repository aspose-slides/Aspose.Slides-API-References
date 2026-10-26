---
title: SvgImage()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: नया SvgImage ऑब्जेक्ट बनाता है।
type: docs
weight: 53
url: /hi/aspose.slides/svgimage/svgimage/
---
## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>) कंस्ट्रक्टर

नया [SvgImage](../) ऑब्जेक्ट बनाता है।

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg डेटा। |

## SvgImage::SvgImage(System::String) कंस्ट्रक्टर

नया [SvgImage](../) ऑब्जेक्ट बनाता है।

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg कंटेंट। |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>) कंस्ट्रक्टर

नया [SvgImage](../) ऑब्जेक्ट बनाता है।

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg स्ट्रीम। |

## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) कंस्ट्रक्टर

नया [SvgImage](../) ऑब्जेक्ट बनाता है।

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg डेटा। |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | बाहरी वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुओं को अनदेखा किया जाएगा। |
| baseUri | [System::String](../../../system/string/) | निर्दिष्ट Svg का बेस URI। सापेक्ष लिंक को हल करने के लिए उपयोग होता है। |

## SvgImage::SvgImage(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) कंस्ट्रक्टर

नया [SvgImage](../) ऑब्जेक्ट बनाता है।

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg कंटेंट। |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | बाहरी वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुओं को अनदेखा किया जाएगा। |
| baseUri | [System::String](../../../system/string/) | निर्दिष्ट Svg का बेस URI। सापेक्ष लिंक को हल करने के लिए उपयोग होता है। |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) कंस्ट्रक्टर

नया [SvgImage](../) ऑब्जेक्ट बनाता है।

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg स्ट्रीम। |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | बाहरी वस्तुओं को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर null है तो सभी बाहरी वस्तुओं को अनदेखा किया जाएगा। |
| baseUri | [System::String](../../../system/string/) | निर्दिष्ट Svg का बेस URI। सापेक्ष लिंक को हल करने के लिए उपयोग होता है। |

## अन्य देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [SvgImage](../)
* क्लास [String](../../../system/string/)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)