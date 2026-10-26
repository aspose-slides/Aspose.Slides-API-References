---
title: Join()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रबंधित थ्रेड को जोड़ता है। यदि आवश्यक हो तो असीमित प्रतीक्षा करता है।
type: docs
weight: 196
url: /hi/system.threading/thread/join/
---
## Thread::Join() मेथड


प्रबंधित थ्रेड को जोड़ता है। यदि आवश्यक हो तो अनन्त प्रतीक्षा करता है।

```cpp
void System::Threading::Thread::Join()
```

## Thread::Join(int) मेथड


प्रबंधित थ्रेड को जोड़ता है। सीमित प्रतीक्षा करता है।

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| millisecondsTimeout | int | मिलिसेकंड में प्रतीक्षा टाइमआउट। |

### वापसी मान

यदि थ्रेड सफलतापूर्वक जुड़ा हो तो true, यदि टाइमआउट पार हो गया हो तो false।

## Thread::Join(TimeSpan) मेथड


प्रबंधित थ्रेड को जोड़ता है। सीमित प्रतीक्षा करता है।

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | एक [TimeSpan](../../../system/timespan/) जो थ्रेड के समाप्त होने की प्रतीक्षा के समय की राशि को निर्धारित करता है। |

### वापसी मान

यदि थ्रेड सफलतापूर्वक जुड़ा हो तो true, यदि टाइमआउट पार हो गया हो तो false।

## संबंधित देखें

* क्लास [Thread](../)
* क्लास [TimeSpan](../../../system/timespan/)
* नामस्थान [System::Threading](../../)
* लाइब्रेरी [Aspose.Slides](../../../)