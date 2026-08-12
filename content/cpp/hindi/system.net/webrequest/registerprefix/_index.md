---
title: RegisterPrefix()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट URI के लिए WebRequest उत्तराधिकारी को पंजीकृत करता है।
type: docs
weight: 92
url: /hi/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) विधि

निर्दिष्ट URI के लिए [WebRequest](../) उत्तराधिकारी को पंजीकृत करता है।

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | URI या URI उपसर्ग। |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | [WebRequest](../) वर्ग की नई इंस्टेंस बनाता है। |

### रिटर्न मान

जब [WebRequest](../) उत्तराधिकारी को निर्दिष्ट URI के लिए सफलतापूर्वक पंजीकृत किया जाता है तो true, अन्यथा false।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [IWebRequestCreate](../../iwebrequestcreate/)
* क्लास [WebRequest](../)
* नामस्थान [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)