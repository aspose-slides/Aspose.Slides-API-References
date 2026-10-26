---
title: AreFPNaN()
second_title: Aspose.Slides for C++ API संदर्भ
description: नामस्थान विवरण
type: docs
weight: 1
url: /hi/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) फ़ंक्शन


नामस्थान [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | पहला फ़्लोटिंग पॉइंट प्रकार। |
| T2 | दूसरा फ़्लोटिंग पॉइंट प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs | T1 | पहला फ़्लोटिंग पॉइंट मान। |
| rhs | T2 | दूसरा फ़्लोटिंग पॉइंट मान। |

### वापसी मान

यदि दोनों **lhs** और **rhs** फ़्लोटिंग पॉइंट मान हैं तो सत्य, अन्यथा असत्य।

## टिप्पणी

जाँचता है कि दो फ़्लोटिंग पॉइंट मान दोनों NaN हैं। जब नॉन-सिग्नलिंग NaN समर्थित हो तो स्थिति को संभालता है। 
## System::TestPredicates::AreFPNaN(T1, T2) फ़ंक्शन

जाँचता है कि दो फ़्लोटिंग पॉइंट मान दोनों NaN हैं। जब नॉन-सिग्नलिंग NaN समर्थित नहीं हो तो स्थिति को संभालता है।

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | पहला फ़्लोटिंग पॉइंट प्रकार। |
| T2 | दूसरा फ़्लोटिंग पॉइंट प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs | T1 | पहला फ़्लोटिंग पॉइंट मान। |
| rhs | T2 | दूसरा फ़्लोटिंग पॉइंट मान। |

### वापसी मान

जब NaN मान समर्थित नहीं हो तो हमेशा असत्य लौटाता है।

## देखें

* नामस्थान [System::TestPredicates](../)
* लाइब्रेरी [Aspose.Slides](../../)