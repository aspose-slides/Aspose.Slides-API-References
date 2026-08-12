---
title: IterateOver()
second_title: Aspose.Slides for C++ API संदर्भ
description: "यह फ़ंक्शन प्रॉपर्टी enumerable (या iterable) ऑब्जेक्ट को रैप करती है ताकि इसे रेंज-आधारित for लूप के साथ उपयोग किया जा सके। यह ओवरलोड Enumerable के लिए है, जिसमें begin(), end() मेथड नहीं होते और target type आर्गुमेंट के साथ (auto& value : IterateOver<SomeType>(enumerable)) का उपयोग किया जाता है।"
type: docs
weight: 2471
url: /hi/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) function


यह फ़ंक्शन प्रॉपर्टी enumerable (या iterable) ऑब्जेक्ट को रैप करती है ताकि इसे रेंज-आधारित for लूप के साथ उपयोग किया जा सके। यह ओवरलोड Enumerable के लिए है, जिसमें begin(), end() मेथड नहीं होते और target type आर्गुमेंट के साथ (auto& value : IterateOver<SomeType>(enumerable)) के रूप में उपयोग किया जाता है।

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | लक्ष्य प्रकार, इसे iterator से लौटाया जाना चाहिए |
| Enumerable | रैप किए गए ऑब्जेक्ट का प्रकार |

## System::IterateOver(System::SmartPtr\<Enumerable\>) function


यह फ़ंक्शन प्रॉपर्टी enumerable (या iterable) ऑब्जेक्ट को रैप करती है ताकि इसे रेंज-आधारित for लूप के साथ उपयोग किया जा सके। यह ओवरलोड Enumerable के लिए है, जिसमें begin(), end() मेथड नहीं होते और डिफ़ॉल्ट target type आर्गुमेंट के साथ (auto& value : IterateOver(enumerable)) के रूप में उपयोग किया जाता है, जो निम्नलिखित C# कोड के समतुल्य है: foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Enumerable | रैप किए गए ऑब्जेक्ट का प्रकार |

## System::IterateOver(System::SmartPtr\<Enumerable\>) function


यह फ़ंक्शन प्रॉपर्टी enumerable (या iterable) ऑब्जेक्ट को रैप करती है ताकि इसे रेंज-आधारित for लूप के साथ उपयोग किया जा सके। यह ओवरलोड Enumerable के लिए है, जिसमें begin(), end() मेथड होते हैं और डिफ़ॉल्ट target type आर्गुमेंट के साथ (auto& value : IterateOver(enumerable)) के रूप में उपयोग किया जाता है।

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Enumerable | रैप किए गए ऑब्जेक्ट का प्रकार |

## System::IterateOver(System::SmartPtr\<Enumerable\>) function


यह फ़ंक्शन प्रॉपर्टी enumerable (या iterable) ऑब्जेक्ट को रैप करती है ताकि इसे रेंज-आधारित for लूप के साथ उपयोग किया जा सके। यह ओवरलोड Enumerable के लिए है, जिसमें begin(), end() मेथड होते हैं और target type iterator के मूल value_type के समान होता है।

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Enumerable | रैप किए गए ऑब्जेक्ट का प्रकार |
| T | लक्ष्य प्रकार, जिसे iterator से लौटाया जाना चाहिए |

## System::IterateOver(System::SmartPtr\<Enumerable\>) function


यह फ़ंक्शन प्रॉपर्टी enumerable (या iterable) ऑब्जेक्ट को रैप करती है ताकि इसे रेंज-आधारित for लूप के साथ उपयोग किया जा सके। यह ओवरलोड Enumerable के लिए है, जिसमें begin(), end() मेथड होते हैं और अलग target type तथा iterator के मूल value_type के साथ।

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Enumerable | रैप किए गए ऑब्जेक्ट का प्रकार |
| T | लक्ष्य प्रकार, जिसे iterator से लौटाया जाना चाहिए |

## System::IterateOver(const Enumerable *) function


यह फ़ंक्शन प्रॉपर्टी enumerable (या iterable) ऑब्जेक्ट को रैप करती है ताकि इसे रेंज-आधारित for लूप के साथ उपयोग किया जा सके। यह ओवरलोड Enumerable के लिए है, जिसमें डिफ़ॉल्ट target type होता है।

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Enumerable | रैप किए गए ऑब्जेक्ट का प्रकार |

## System::IterateOver(const Enumerable *) function


यह फ़ंक्शन प्रॉपर्टी enumerable (या iterable) ऑब्जेक्ट को रैप करती है ताकि इसे रेंज-आधारित for लूप के साथ उपयोग किया जा सके। यह ओवरलोड Enumerable के लिए है, जिसमें begin(), end() मेथड नहीं होते और target type आर्गुमेंट के साथ (auto& value : IterateOver<SomeType>(enumerable)) के रूप में उपयोग किया जाता है।

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | लक्ष्य प्रकार, इसे iterator से लौटाया जाना चाहिए |
| Enumerable | रैप किए गए ऑब्जेक्ट का प्रकार |

## See Also

* क्लास [SmartPtr](../smartptr/)
* स्ट्रक्ट [IsSmartPtr](../issmartptr/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)