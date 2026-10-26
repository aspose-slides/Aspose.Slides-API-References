---
title: IsBypassed()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक मान लौटाता है जो दर्शाता है कि निर्दिष्ट होस्ट के लिए प्रॉक्सी का उपयोग नहीं किया जाना चाहिए।
type: docs
weight: 40
url: /hi/system.net/iwebproxy/isbypassed/
---
## IWebProxy::IsBypassed(System::SharedPtr\<Uri\>) मेथड

प्रॉक्सी को निर्दिष्ट होस्ट के लिए उपयोग नहीं किया जाना चाहिए, यह दर्शाने वाला मान लौटाता है।

```cpp
virtual bool System::Net::IWebProxy::IsBypassed(System::SharedPtr<Uri> host)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| host | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | जांच हेतु होस्ट URI। |

### वापसी मान

जब प्रॉक्सी सर्वर का उपयोग नहीं किया जाना चाहिए तो true, अन्यथा false।

## संबंधित

* Typedef [SharedPtr](../../../system/sharedptr/)
* वर्ग [Uri](../../../system/uri/)
* वर्ग [IWebProxy](../)
* नामस्थान [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)