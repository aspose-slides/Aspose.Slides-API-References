---
title: WaitOne()
second_title: Aspose.Slides for C++ API संदर्भ
description: सेमाफोर को लॉक करता है। यदि आवश्यक हो तो अनिश्चित काल तक प्रतीक्षा करता है।
type: docs
weight: 40
url: /hi/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() मेथड

सेमाफोर को लॉक करता है। यदि आवश्यक हो तो अनिश्चित काल तक प्रतीक्षा करता है।

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```

### रिटर्न वैल्यू

सेमाफोर लॉक होने तक यह वापस नहीं आता, इसलिए हमेशा true लौटाता है।

## Semaphore::WaitOne(int) मेथड

सेमाफोर को लॉक करता है। यदि आवश्यक हो तो प्रतीक्षा करता है।

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| millisecondsTimeout | int | मिलिसेकंड में प्रतीक्षा टाइमआउट। |

### रिटर्न वैल्यू

यदि सेमाफोर लॉक किया गया हो तो true लौटाता है, अन्यथा timeout अधिक हो जाने पर false लौटाता है।

## देखें

* क्लास [Semaphore](../)
* नामस्थान [System::Threading](../../)
* लाइब्रेरी [Aspose.Slides](../../../)