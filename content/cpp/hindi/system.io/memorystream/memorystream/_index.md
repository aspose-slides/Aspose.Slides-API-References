---
title: MemoryStream()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नई MemoryStream क्लास की इंस्टेंस बनाता है जिसकी प्रारंभिक क्षमता 0 के बराबर है।
type: docs
weight: 1
url: /hi/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() निर्माता

एक नई [MemoryStream](../) क्लास की इंस्टेंस बनाता है जिसकी प्रारंभिक क्षमता 0 के बराबर है।

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) निर्माता

एक नई [MemoryStream](../) क्लास की इंस्टेंस बनाता है जो निर्दिष्ट आकार के मेमोरी बफ़र पर आधारित स्ट्रीम को दर्शाती है।

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| capacity_ | int | ऑब्जेक्ट द्वारा निर्मित स्ट्रीम से जुड़े मेमोरी बफ़र का बाइट्स में आकार। |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) निर्माता

एक नई [MemoryStream](../) क्लास की इंस्टेंस बनाता है जो निर्दिष्ट मेमोरी बफ़र से जुड़ी मेमोरी स्ट्रीम को दर्शाती है। एक पैरामीटर निर्धारित करता है कि क्या स्ट्रीम लिखने योग्य है।

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | एक बाइट एरे जिसे मेमोरी बफ़र के रूप में उपयोग किया जाएगा, जिस पर ऑब्जेक्ट द्वारा निर्मित स्ट्रीम आधारित होगी। |
| writable | **bool** | निर्धारित करता है कि क्या स्ट्रीम लिखने योग्य होनी चाहिए। |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) निर्माता

एक नई [MemoryStream](../) क्लास की इंस्टेंस बनाता है जो निर्दिष्ट मेमोरी बफ़र के एक खंड से जुड़ी मेमोरी स्ट्रीम को दर्शाती है, जो निर्दिष्ट इंडेक्स से शुरू होती है और निर्दिष्ट तत्वों की संख्या को शामिल करती है। पैरामीटर निर्धारित करता है कि क्या स्ट्रीम लिखने योग्य है और क्या GetBytes() मेथड को कॉल किया जा सकता है।

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | एक बाइट एरे जिसका एक खंड मेमोरी बफ़र के रूप में उपयोग किया जाएगा, जिस पर ऑब्जेक्ट द्वारा निर्मित स्ट्रीम आधारित होगी। |
| index | int | **content** में तत्व का 0-आधारित इंडेक्स जहाँ से खंड शुरू होता है। |
| count | int | सेगमेंट में शामिल **content** के तत्वों की संख्या। |
| writable | **bool** | निर्धारित करता है कि क्या स्ट्रीम लिखने योग्य होना चाहिए। |
| publiclyVisible | **bool** | निर्धारित करता है कि क्या अंतर्गत मेमोरी बफ़र को GetByte() मेथड के कॉलर को उपलब्ध कराना चाहिए। |

## देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [MemoryStream](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)