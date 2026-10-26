---
title: Semaphore()
second_title: Aspose.Slides for C++ API संदर्भ
description: बिना नाम का सेमाफोर बनाता है।
type: docs
weight: 1
url: /hi/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) कंस्ट्रक्टर


बिना नाम का सेमाफोर बनाता है।

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| initialCount | int | सक्रिय प्रविष्टियों की प्रारंभिक गिनती। |
| maximumCount | int | अधिकतम अनुमत प्रविष्टियों की गिनती। |

## Semaphore::Semaphore(int, int, const String\&) कंस्ट्रक्टर


नामित सेमाफोर बनाता है।

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| initialCount | int | सक्रिय प्रविष्टियों की प्रारंभिक गिनती। |
| maximumCount | int | अधिकतम अनुमत प्रविष्टियों की गिनती। |
| name | const [String](../../../system/string/)\& | [Semaphore](../) नाम। |

## Semaphore::Semaphore(int, int, const String\&, bool\&) कंस्ट्रक्टर


नामित सेमाफोर बनाता है।

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| initialCount | int | सक्रिय प्रविष्टियों की प्रारंभिक गिनती। |
| maximumCount | int | अधिकतम अनुमत प्रविष्टियों की गिनती। |
| name | const [String](../../../system/string/)\& | [Semaphore](../) नाम। |
| createdNew | **bool**\& | वेरिएबल का संदर्भ जिसमें true सेट किया जाता है यदि सेमाफोर बनाया गया हो और false यदि समान नाम वाला मौजूदा सेमाफोर पुन: उपयोग किया गया हो। |

## संबंधित देखें

* क्लास [Semaphore](../)
* क्लास [String](../../../system/string/)
* नामस्थान [System::Threading](../../)
* लाइब्रेरी [Aspose.Slides](../../../)