---
title: Cast()
second_title: Aspose.Slides for C++ API संदर्भ
description: स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। उपयोग तब किया जाता है जब स्रोत और परिणाम प्रकार समान होते हैं।
type: docs
weight: 14
url: /hi/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) फ़ंक्शन

स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। उपयोग तब किया जाता है जब स्रोत और परिणाम प्रकार समान होते हैं।

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### रिटर्न मान

कास्ट परिणाम।

## System::Collections::Generic::Details::CastRules::Cast(Source) फ़ंक्शन

स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। उपयोग तब किया जाता है जब स्रोत प्रकार को स्थैतिक रूप से परिणाम प्रकार में परिवर्तित किया जा सकता है।

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### रिटर्न मान

कास्ट परिणाम।

## System::Collections::Generic::Details::CastRules::Cast(Source) फ़ंक्शन

स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। उपयोग तब किया जाता है जब प्रकार समान नहीं होते और स्रोत प्रकार को स्थैतिक रूप से परिणाम प्रकार में परिवर्तित नहीं किया जा सकता।

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### रिटर्न मान

कास्ट परिणाम।

## System::Collections::Generic::Details::CastRules::Cast(Source) फ़ंक्शन

स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। उपयोग तब किया जाता है जब स्रोत प्रकार को [Nullable](../../system/nullable/) क्लास उदाहरण में बॉक्स किया जा रहा है।

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### रिटर्न मान

कास्ट परिणाम।

## System::Collections::Generic::Details::CastRules::Cast(Source) फ़ंक्शन

स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। उपयोग तब किया जाता है जब स्रोत प्रकार को [Nullable](../../system/nullable/) क्लास उदाहरण से अनबॉक्स किया जा रहा है।

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### रिटर्न मान

कास्ट परिणाम।

## System::Collections::Generic::Details::CastRules::Cast(Source) फ़ंक्शन

स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। उपयोग तब किया जाता है जब स्रोत प्रकार को [Object](../../system/object/) क्लास उदाहरण में बॉक्स किया जा रहा है।

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### रिटर्न मान

कास्ट परिणाम।

## System::Collections::Generic::Details::CastRules::Cast(Source) फ़ंक्शन

स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। उपयोग तब किया जाता है जब स्रोत प्रकार को [Object](../../system/object/) क्लास उदाहरण से अनबॉक्स किया जा रहा है।

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### रिटर्न मान

कास्ट परिणाम।

## System::Collections::Generic::Details::CastRules::Cast(Source) फ़ंक्शन

स्रोत प्रकार को परिणाम प्रकार में परिवर्तित करता है। उपयोग तब किया जाता है जब कास्टिंग अमान्य हो या रूपांतरण स्पष्ट हो।

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Source | स्रोत प्रकार। |
| Result | परिणाम प्रकार। |

### रिटर्न मान

कास्ट परिणाम।

## देखें

* संरचना [CastType](../casttype/)
* नामस्थान [System::Collections::Generic::Details::CastRules](../)
* लाइब्रेरी [Aspose.Slides](../../)