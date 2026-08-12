---
title: Dictionary()
second_title: Aspose.Slides for C++ API संदर्भ
description: खाली शब्दकोश बनाता है।
type: docs
weight: 1
url: /hi/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() कंस्ट्रक्टर

खाली शब्दकोश बनाता है।

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) कंस्ट्रक्टर

मैप से डेटा की प्रतिलिपि बनाता है।

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | डेटा कॉपी करने के लिए मैप। |

## Dictionary::Dictionary(int) कंस्ट्रक्टर

एक ओवरलोड जो प्री-एलोकेटेड शब्दकोश बनाने के अनुरूप है; वास्तव में कोई आवंटन नहीं करता।

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| capacity | int | आवंटित करने की क्षमता; अनदेखी। |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) कंस्ट्रक्टर

कॉपी कंस्ट्रक्टर।

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../) से डेटा कॉपी करने के लिए। |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) कंस्ट्रक्टर

कॉपी कंस्ट्रक्टर।

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | स्रोत शब्दकोश। |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) ऑब्जेक्ट उपयोग करने के लिए। |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) कंस्ट्रक्टर

खाली शब्दकोश बनाता है।

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) उपयोग करने के लिए। |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) कंस्ट्रक्टर

खाली शब्दकोश बनाता है।

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| capacity | int | [Dictionary](../) निर्माण के बाद क्षमता; अनदेखी। |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) उपयोग करने के लिए। |

## संबंधित देखें

* Typedef [map_t](../map_t/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Dictionary](../)
* क्लास [IDictionary](../../idictionary/)
* क्लास [IEqualityComparer](../../iequalitycomparer/)
* नेमस्पेस [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)