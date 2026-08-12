---
title: ThreadPoolImpl
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: थ्रेड पूल का आंतरिक डेटा। यह एक सिंग्लटन प्रकार है जिसका मेमोरी प्रबंधन एक्सेस फ़ंक्शन(s) द्वारा किया जाता है। आपको इसे सीधे बनाना कभी नहीं चाहिए।
type: docs
weight: 235
url: /hi/system.threading/threadpoolimpl/
---
## ThreadPoolImpl क्लास

[Thread](../thread/) पूल आंतरिक डेटा। यह एक सिंग्लटन प्रकार है जिसका मेमोरी प्रबंधन एक्सेस फ़ंक्शन(s) द्वारा किया जाता है। आपको इसे सीधे बनाने के लिए कभी नहीं बनाना चाहिए।

```cpp
class ThreadPoolImpl
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | उपलब्ध थ्रेड्स की संख्या प्राप्त करता है। |
| static **bool**\& [GetInitialized](./getinitialized/)() | आरम्भिक स्थिति सिंग्लटन प्राप्त करता है। |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | समकालिक थ्रेड्स की अधिकतम संख्या प्राप्त करता है। |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | पूल द्वारा निर्मित थ्रेड्स की न्यूनतम संख्या प्राप्त करता है। |
| void [JoinAll](./joinall/)() | सभी स्वत्व वाले थ्रेड्स को जॉइन करता है। अनिश्चितकाल प्रतीक्षा करता है। |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | कार्य आइटम को कतार में जोड़ता है। |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | पूल द्वारा स्वत्व वाले थ्रेड्स की संख्या सेट करता है। |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | पूल द्वारा स्वत्व वाले थ्रेड्स की न्यूनतम संख्या सेट करता है। |
|  [ThreadPoolImpl](./threadpoolimpl/)() | निर्माता। |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | ध्वंसक। यदि थ्रेड्स अभी तक समाप्त नहीं हुए हों तो सभी थ्रेड्स को जॉइन करता है। |

## देखें भी

* नेमस्पेस [System::Threading](../)
* लाइब्रेरी [Aspose.Slides](../../)