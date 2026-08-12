---
title: operator==()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ResultValueTask के लिए समानता ऑपरेटर।
type: docs
weight: 131
url: /hi/system.threading.tasks/resultvaluetask/operator_equal_equal/
---
## ResultValueTask::operator==(const ResultValueTask\&) const विधि

समानता ऑपरेटर के लिए [ResultValueTask](../).

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | const [ResultValueTask](../)\& | इस उदाहरण के साथ तुलना करने के लिए अन्य [ResultValueTask](../)। |

### रिटर्न मान

bool True यदि दोनों कार्यों का परिणाम मान समान हो या समान अंतर्निहित कार्य को संदर्भित करते हों; अन्यथा, false।

## टिप्पणी

यदि कोई भी उदाहरण प्रत्यक्ष परिणाम मान रखता है, तो परिणामों की सीधे तुलना की जाती है। अन्यथा, अंतर्निहित कार्य पॉइंटर्स की तुलना की जाती है।

## देखें

* क्लास [ResultValueTask](../)
* नामस्थान [System::Threading::Tasks](../../)
* लाइब्रेरी [Aspose.Slides](../../../)