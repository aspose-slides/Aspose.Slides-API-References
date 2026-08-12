---
title: FlushAsync()
second_title: Aspose.Slides C++ API संदर्भ
description: असिंक्रोनस रूप से इस स्ट्रीम के सभी बफ़र को साफ़ करता है, किसी भी बफ़र किए गए डेटा को अंतर्निहित डिवाइस पर लिखवाता है, और रद्दीकरण अनुरोधों की निगरानी करता है।
type: docs
weight: 157
url: /hi/system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) मेथड


Asynchronously clears all buffers for this stream, causes any buffered data to be written to the underlying device, and monitors cancellation requests.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | रद्दीकरण अनुरोधों की निगरानी के लिए टोकन। |

### रिटर्न मान

एक टास्क जो असिंक्रोनस फ्लश ऑपरेशन को दर्शाता है।

## देखें

* टाइपडिफ [TaskPtr](../../../system/taskptr/)
* क्लास [CancellationToken](../../../system.threading/cancellationtoken/)
* क्लास [FileStream](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)