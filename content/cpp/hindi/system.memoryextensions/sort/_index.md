---
title: Sort()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक कस्टम कॉम्पेयरर का उपयोग करके Span को सॉर्ट करता है।
type: docs
weight: 339
url: /hi/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) function


एक [Span](../../system/span/) को एक कस्टम कॉम्पेयरर का उपयोग करके सॉर्ट करता है।

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |
| TComparer | कॉम्पेयरर ऑब्जेक्ट का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | सॉर्ट करने के लिए स्पैन |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | कुंजी तुलना के लिए कॉम्पेयरर ऑब्जेक्ट का स्मार्ट पॉइंटर |

## System::MemoryExtensions::Sort(Span\<T\>\&) function


डिफ़ॉल्ट तुलना का उपयोग करके एक [Span](../../system/span/) को सॉर्ट करता है।

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | सॉर्ट करने के लिए स्पैन |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) function


कस्टम कॉम्पेयरर का उपयोग करके कुंजी-मूल्य जोड़ों को सॉर्ट करता है (कुंजियाँ और मान एक साथ सॉर्ट होते हैं)

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TKey | कुंजियों का प्रकार |
| TValue | मानों का प्रकार |
| TComparer | कॉम्पेयरर ऑब्जेक्ट का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | सॉर्ट करने के लिए कुंजियों का स्पैन |
| values | [Span](../../system/span/)\<TValue\>\& | सॉर्ट करने के लिए मानों का स्पैन (कुंजियों के साथ संबंध बनाए रखते हुए) |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | कुंजी तुलना के लिए कॉम्पेयरर ऑब्जेक्ट का स्मार्ट पॉइंटर |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) function


तुलना डेलीगेट का उपयोग करके कुंजी-मूल्य जोड़ों को सॉर्ट करता है।

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TKey | कुंजियों का प्रकार |
| TValue | मानों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | सॉर्ट करने के लिए कुंजियों का स्पैन |
| values | [Span](../../system/span/)\<TValue\>\& | सॉर्ट करने के लिए मानों का स्पैन |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) डेलीगेट कुंजी तुलना के लिए |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) function


डिफ़ॉल्ट तुलना का उपयोग करके कुंजी-मूल्य जोड़ों को सॉर्ट करता है।

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TKey | कुंजियों का प्रकार |
| TValue | मानों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | सॉर्ट करने के लिए कुंजियों का स्पैन |
| values | [Span](../../system/span/)\<TValue\>\& | सॉर्ट करने के लिए मानों का स्पैन |

## संदर्भ देखें

* Typedef [SharedPtr](../../system/sharedptr/)
* क्लास [Span](../../system/span/)
* क्लास [Comparison](../../system/comparison/)
* नेमस्पेस [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)