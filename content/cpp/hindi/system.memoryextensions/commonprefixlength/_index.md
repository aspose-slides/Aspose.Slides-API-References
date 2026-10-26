---
title: CommonPrefixLength()
second_title: Aspose.Slides for C++ API संदर्भ
description: दो स्पैनों के बीच सामान्य प्रीफ़िक्स की लंबाई खोजता है।
type: docs
weight: 27
url: /hi/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन

दो स्पैन्स के बीच सामान्य प्रीफ़िक्स की लंबाई खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | पहला स्पैन |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | दूसरा स्पैन |

### वापसी मान

दोनों स्पैन्स की शुरुआत में मेल खाने वाले तत्वों की संख्या

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन

एक परिवर्तनीय स्पैन और एक केवल-पढ़ने योग्य स्पैन के बीच सामान्य प्रीफ़िक्स की लंबाई खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | परिवर्तनीय स्पैन |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | केवल-पढ़ने योग्य स्पैन |

### वापसी मान

दोनों स्पैन्स की शुरुआत में मेल खाने वाले तत्वों की संख्या

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) फ़ंक्शन

दो परिवर्तनीय स्पैन्स के बीच सामान्य प्रीफ़िक्स की लंबाई खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | पहला परिवर्तनीय स्पैन |
| other | const [Span](../../system/span/)\<T\>\& | दूसरा परिवर्तनीय स्पैन |

### वापसी मान

दोनों स्पैन्स की शुरुआत में मेल खाने वाले तत्वों की संख्या

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) फ़ंक्शन

दो स्पैन्स के बीच सामान्य प्रीफ़िक्स की लंबाई को एक कस्टम इक्क्वैलिटी कंपेयरर का उपयोग करके खोजता है।

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |
| TEqualityComparer | इक्क्वैलिटी कंपेयरर का प्रकार |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | पहला स्पैन |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | दूसरा स्पैन |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | तत्व तुलना के लिए उपयोग किया जाने वाला इक्क्वैलिटी कंपेयरर |

### वापसी मान

दोनों स्पैन्स की शुरुआत में मेल खाने वाले तत्वों की संख्या

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) फ़ंक्शन

एक परिवर्तनीय स्पैन और एक केवल-पढ़ने योग्य स्पैन के बीच सामान्य प्रीफ़िक्स की लंबाई को एक कस्टम इक्क्वैलिटी कंपेयरर का उपयोग करके खोजता है।

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |
| TEqualityComparer | इक्क्वैलिटी कंपेयरर का प्रकार |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | परिवर्तनीय स्पैन |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | केवल-पढ़ने योग्य स्पैन |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | तत्व तुलना के लिए उपयोग किया जाने वाला इक्क्वैलिटी कंपेयरर |

### वापसी मान

दोनों स्पैन्स की शुरुआत में मेल खाने वाले तत्वों की संख्या

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) फ़ंक्शन

दो परिवर्तनीय स्पैन्स के बीच सामान्य प्रीफ़िक्स की लंबाई को एक कस्टम इक्क्वैलिटी कंपेयरर का उपयोग करके खोजता है।

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |
| TEqualityComparer | इक्क्वैलिटी कंपेयरर का प्रकार |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | पहला परिवर्तनीय स्पैन |
| other | const [Span](../../system/span/)\<T\>\& | दूसरा परिवर्तनीय स्पैन |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | तत्व तुलना के लिए उपयोग किया जाने वाला इक्क्वैलिटी कंपेयरर |

### वापसी मान

दोनों स्पैन्स की शुरुआत में मेल खाने वाले तत्वों की संख्या

## देखिए भी

* Typedef [SharedPtr](../../system/sharedptr/)
* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [Span](../../system/span/)
* नेमस्पेस [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)