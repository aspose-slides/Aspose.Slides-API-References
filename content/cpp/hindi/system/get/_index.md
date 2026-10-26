---
title: Get()
second_title: Aspose.Slides for C++ API संदर्भ
description: दिए गए ट्यूपल का N-वाँ तत्व प्राप्त करने का फ़ंक्शन। बेस ऑब्जेक्ट के लिए ओवरलोड।
type: docs
weight: 2406
url: /hi/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) फ़ंक्शन

दिए गए ट्यूपल का N-वाँ तत्व प्राप्त करने के लिए फ़ंक्शन। बेस ऑब्जेक्ट के लिए ओवरलोड।

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| N | तत्व का सूचकांक। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | निरीक्षण के लिए ऑब्जेक्ट। |

### वापसी मान

ऑब्जेक्ट में कास्ट किया गया N-वाँ ट्यूपल तत्व का मान।

## System::Get(const T\&) फ़ंक्शन

दिए गए ट्यूपल का N-वाँ तत्व प्राप्त करने के लिए फ़ंक्शन। Deconstruct मेथड वाले ऑब्जेक्ट्स के लिए ओवरलोड।

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| N | तत्व का सूचकांक। |
| T | निरीक्षण किए गए ऑब्जेक्ट का प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| object | const T\& | निरीक्षण के लिए ऑब्जेक्ट। |

### वापसी मान

N-वाँ ट्यूपल तत्व का मान।

## System::Get(const SharedPtr\<T\>\&) फ़ंक्शन

दिए गए ट्यूपल का N-वाँ तत्व प्राप्त करने के लिए फ़ंक्शन। साझा पॉइंटर्स के लिए ओवरलोड।

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| N | तत्व का सूचकांक। |
| T | निरीक्षण किए गए ऑब्जेक्ट का प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | निरीक्षण के लिए ऑब्जेक्ट। |

### वापसी मान

N-वाँ ट्यूपल तत्व का मान।

## System::Get(T\&, const Index\&) फ़ंक्शन

collection[index] अभिव्यक्तियों के लिए कार्यान्वयन।

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | कलेक्शन प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| collection | T\& | कलेक्शन ऑब्जेक्ट। |
| index | const [Index](../index/)\& | प्रकार [System.Index](../index/) का तत्व सूचकांक। |

### वापसी मान

गणना किए गए ऑफ़सेट पर कलेक्शन तत्व।

## System::Get(T\&, const Range\&) फ़ंक्शन

प्रदान किए गए रेंज द्वारा परिभाषित निर्दिष्ट कलेक्शन का स्लाइस लौटाता है।

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| collection | T\& | स्लाइस करने के लिए कलेक्शन। |
| range | const [Range](../range/)\& | स्लाइस की सीमाएँ निर्दिष्ट करने वाला रेंज। |

### वापसी मान

गणना किए गए प्रारंभिक ऑफ़सेट और लंबाई से कलेक्शन का एक दृश्य या स्लाइस।

## System::Get(const ValueTuple\<Args...\>\&) फ़ंक्शन

value ट्यूपल का N-वाँ तत्व प्राप्त करता है।

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| N | तत्व का सूचकांक। |
| Args | ट्यूपल तत्व। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tuple | const [ValueTuple](../valuetuple/)\<Args...\>\& | जिस ट्यूपल से तत्व प्राप्त करना है। |

### वापसी मान

N-वाँ ट्यूपल तत्व का मान।

## संबंधित देखें

* Typedef [SharedPtr](../sharedptr/)
* क्लास [Object](../object/)
* क्लास [Index](../index/)
* क्लास [Range](../range/)
* क्लास [ValueTuple](../valuetuple/)
* नेमस्पेस [System](../)
* Library [Aspose.Slides](../../)