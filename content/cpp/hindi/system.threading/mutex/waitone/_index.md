---
title: WaitOne()
second_title: Aspose.Slides for C++ API संदर्भ
description: Mutex को लॉक करता है। यदि आवश्यक हो तो अनिश्चितकाल तक प्रतीक्षा करता है।
type: docs
weight: 53
url: /hi/system.threading/mutex/waitone/
---
## Mutex::WaitOne() मेथड

Locks mutex. Performs unlimited waiting if neccessary.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```

### रिटर्न वैल्यू

Always returns true as it does not return until mutex is locked.

## Mutex::WaitOne(int) मेथड

Locks mutex. Performs waiting if neccessary.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| millisecondsTimeout | int | Waiting timeout in milliseconds. |

### रिटर्न वैल्यू

Returns true if mutex was locked or false if timeout exceeded.

## Mutex::WaitOne(TimeSpan) मेथड

Locks mutex. Performs waiting if neccessary.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | A [System::TimeSpan](../../../system/timespan/) that represents the number of milliseconds to wait, or a [System::TimeSpan](../../../system/timespan/) that represents -1 milliseconds to wait indefinitely. |

### रिटर्न वैल्यू

Returns true if mutex was locked or false if timeout exceeded.

## संबंधित देखें

* क्लास [Mutex](../)
* क्लास [TimeSpan](../../../system/timespan/)
* नामस्थान [System::Threading](../../)
* लाइब्रेरी [Aspose.Slides](../../../)