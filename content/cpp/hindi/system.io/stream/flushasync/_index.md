---
title: FlushAsync()
second_title: Aspose.Slides for C++ API संदर्भ
description: असिंक्रोनस रूप से इस स्ट्रीम के सभी बफ़र्स को साफ़ करता है, किसी भी बफ़र किए गए डेटा को अंतर्निहित डिवाइस पर लिखवाता है, और रद्द करने के अनुरोधों की निगरानी करता है।
type: docs
weight: 118
url: /hi/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) मेथड

असिंक्रोनस रूप से इस स्ट्रीम के सभी बफ़र्स को साफ़ करता है, किसी भी बफ़र किए गए डेटा को अंतर्निहित डिवाइस पर लिखवाता है, और रद्द करने के अनुरोधों की निगरानी करता है।

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | रद्द करने के अनुरोधों की निगरानी के लिए टोकन। |

### वापसी मान

एक टास्क जो असिंक्रोनस फ़्लश ऑपरेशन का प्रतिनिधित्व करता है।

## Stream::FlushAsync() मेथड

असिंक्रोनस रूप से इस स्ट्रीम के सभी बफ़र्स को साफ़ करता है, किसी भी बफ़र किए गए डेटा को अंतर्निहित डिवाइस पर लिखवाता है, और रद्द करने के अनुरोधों की निगरानी करता है।

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```

### वापसी मान

एक टास्क जो असिंक्रोनस फ़्लश ऑपरेशन का प्रतिनिधित्व करता है।

## देखें

* Typedef [TaskPtr](../../../system/taskptr/)
* क्लास [CancellationToken](../../../system.threading/cancellationtoken/)
* क्लास [Stream](../)
* नामस्थान [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)