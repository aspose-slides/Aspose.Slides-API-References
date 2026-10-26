---
title: Compare()
second_title: Aspose.Slides C++ के लिए API रेफ़रेंस
description: दो मानों की तुलना करता है।
type: docs
weight: 2731
url: /hi/system/compare/
---
## System::Compare(const TA\&, const TB\&) फ़ंक्शन

दो मानों की तुलना करता है।

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### टेम्पलेट पैरामीटर

| Parameter | Description |
| --- | --- |
| TA | पहले कॉम्पेरेंड का प्रकार |
| TB | दूसरे कॉम्पेरेंड का प्रकार |

### आर्ग्युमेंट

| Parameter | Type | Description |
| --- | --- | --- |
| a | const TA\& | पहला कॉम्पेरेंड |
| b | const TB\& | दूसरा कॉम्पेरेंड |

### रिटर्न मान

- 1 यदि **a** **b** से कम तुलना करता है; 0 यदि मान समान हैं; 1 यदि **a** **b** से अधिक तुलना करता है

## System::Compare(const TA\&, const TB\&) फ़ंक्शन

दो फ्लोटिंग पॉइंट मानों की तुलना करता है।

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### टेम्पलेट पैरामीटर

| Parameter | Description |
| --- | --- |
| TA | पहले कॉम्पेरेंड का प्रकार |
| TB | दूसरे कॉम्पेरेंड का प्रकार |

### आर्ग्युमेंट

| Parameter | Type | Description |
| --- | --- | --- |
| a | const TA\& | पहला कॉम्पेरेंड |
| b | const TB\& | दूसरा कॉम्पेरेंड |

### रिटर्न मान

- 1 यदि **a** **b** से कम तुलना करता है; 0 यदि मान समान हैं; 1 यदि **a** **b** से अधिक तुलना करता है

## और देखें

* Namespace [System](../)
* Library [Aspose.Slides](../../)