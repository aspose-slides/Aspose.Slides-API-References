---
title: AreEqual()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: नॉन-पॉइंटर्स वाले एरे की तुलना करता है।
type: docs
weight: 1
url: /hi/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) method

नॉन-पॉइंटर्स वाले एरे की तुलना करता है।

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | पहले एरे तत्व प्रकार। |
| U | दूसरे एरे तत्व प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | बाएँ हाथ का एरे। |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | दाएँ हाथ का एरे। |

### वापसी मान

सही यदि एरे का आकार और डेटा मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) method

पॉइंटर्स वाले एरे की तुलना करता है।

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | पहले एरे के पॉइंटेड प्रकार। |
| U | दूसरे एरे के पॉइंटेड प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | बाएँ हाथ का एरे। |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | दाएँ हाथ का एरे। |

### वापसी मान

सही यदि एरे का आकार और ऑब्जेक्ट मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method

नॉन-पॉइंटर्स वाली सूची की तुलना करता है।

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | पहले सूची तत्व प्रकार। |
| U | दूसरे सूची तत्व प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | बाएँ हाथ की सूची। |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | दाएँ हाथ की सूची। |

### वापसी मान

सही यदि आकार और डेटा मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method

पॉइंटर्स वाली सूची की तुलना करता है।

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | पहले सूची के पॉइंटेड प्रकार। |
| U | दूसरे सूची के पॉइंटेड प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | बाएँ हाथ की सूची। |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | दाएँ हाथ की सूची। |

### वापसी मान

सही यदि सूची का आकार और ऑब्जेक्ट मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) method

नॉन-पॉइंटर्स तत्वों वाली सूची और एरे की तुलना करता है।

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | सूची तत्व प्रकार। |
| U | [Array](../../array/) तत्व प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | सूची। |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/)। |

### वापसी मान

सही यदि आकार और डेटा मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method

नॉन-पॉइंटर्स तत्वों वाली सूची और एरे की तुलना करता है।

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | [Array](../../array/) तत्व प्रकार। |
| U | सूची तत्व प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/)। |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | सूची। |

### वापसी मान

सही यदि आकार और डेटा मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method

पॉइंटर्स वाले तत्वों वाली सूची और एरे की तुलना करता है।

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | [Array](../../array/) पॉइंटेड प्रकार। |
| U | सूची पॉइंटेड प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/)। |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | सूची। |

### वापसी मान

सही यदि आकार और ऑब्जेक्ट मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) method

पॉइंटर्स वाले तत्वों वाली सूची और एरे की तुलना करता है।

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | सूची पॉइंटेड प्रकार। |
| U | [Array](../../array/) पॉइंटेड प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | सूची। |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/)। |

### वापसी मान

सही यदि आकार और ऑब्जेक्ट मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) method

नॉन-पॉइंटर मैप्ड प्रकारों वाले डिक्शनरी की तुलना करता है।

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| K | कुंजी प्रकार। |
| U | मैप्ड प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | बाएँ हाथ का डिक्शनरी। |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | दाएँ हाथ का डिक्शनरी। |

### वापसी मान

सही यदि डिक्शनरी का आकार और डेटा मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&) method

पॉइंटर मैप्ड प्रकारों वाले डिक्शनरी की तुलना करता है।

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| K | कुंजी प्रकार। |
| U | मैप्ड पॉइंटेड प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | बाएँ हाथ का डिक्शनरी। |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | दाएँ हाथ का डिक्शनरी। |

### वापसी मान

सही यदि डिक्शनरी का आकार और डेटा मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) method

विभिन्न प्रकारों वाले डिक्शनरी की तुलना करता है।

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| K1 | बाएँ हाथ के डिक्शनरी कुंजी प्रकार। |
| U1 | बाएँ हाथ के डिक्शनरी मैप्ड प्रकार। |
| K2 | दाएँ हाथ के डिक्शनरी कुंजी प्रकार। |
| U2 | दाएँ हाथ के डिक्शनरी मैप्ड प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | बाएँ हाथ का डिक्शनरी। |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | दाएँ हाथ का डिक्शनरी। |

### वापसी मान

हमेशा गलत लौटाता है क्योंकि यहाँ प्रकार रूपांतरण वर्जित है।

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) method

नॉन-पॉइंटर्स वाले हैशसेट की तुलना करता है।

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | पहला हैशसेट तत्व प्रकार। |
| U | दूसरा हैशसेट तत्व प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | बाएँ हाथ का हैशसेट। |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | दाएँ हाथ का हैशसेट। |

### वापसी मान

सही यदि हैशसेट का आकार और डेटा मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>\&) method

पॉइंटर्स वाले हैशसेट की तुलना करता है।

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | पहला हैशसेट पॉइंटेड प्रकार। |
| U | दूसरा हैशसेट पॉइंटेड प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | बाएँ हाथ का हैशसेट। |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | दाएँ हाथ का हैशसेट। |

### वापसी मान

सही यदि हैशसेट का आकार और डेटा मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) method

नॉन-पॉइंटर्स वाली क्यू की तुलना करता है।

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | पहला क्यू तत्व प्रकार। |
| U | दूसरा क्यू तत्व प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | बाएँ हाथ की क्यू। |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | दाएँ हाथ की क्यू। |

### वापसी मान

सही यदि क्यू का आकार और डेटा मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) method

पॉइंटर्स वाली क्यू की तुलना करता है।

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | पहला क्यू पॉइंटेड प्रकार। |
| U | दूसरा क्यू पॉइंटेड प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | बाएँ हाथ की क्यू। |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | दाएँ हाथ की क्यू। |

### वापसी मान

सही यदि क्यू का आकार और डेटा मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) method

नॉन-पॉइंटर्स वाले स्टैक की तुलना करता है।

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | पहला स्टैक तत्व प्रकार। |
| U | दूसरा स्टैक तत्व प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | बाएँ हाथ का स्टैक। |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | दाएँ हाथ का स्टैक। |

### वापसी मान

सही यदि स्टैक का आकार और डेटा मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>\&) method

पॉइंटर्स वाले स्टैक की तुलना करता है।

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | पहला स्टैक पॉइंटेड प्रकार। |
| U | दूसरा स्टैक पॉइंटेड प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | बाएँ हाथ का स्टैक। |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | दाएँ हाथ का स्टैक। |

### वापसी मान

सही यदि स्टैक का आकार और डेटा मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) method

नॉन-पॉइंटर मैप्ड प्रकारों वाले सॉर्टेड डिक्शनरी की तुलना करता है।

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| K | कुंजी प्रकार। |
| U | मैप्ड प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | बाएँ हाथ का डिक्शनरी। |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | दाएँ हाथ का डिक्शनरी। |

### वापसी मान

सही यदि डिक्शनरी का आकार और डेटा मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&) method

पॉइंटर मैप्ड प्रकारों वाले सॉर्टेड डिक्शनरी की तुलना करता है।

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| K | कुंजी प्रकार। |
| U | मैप्ड पॉइंटेड प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | बाएँ हाथ का डिक्शनरी। |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | दाएँ हाथ का डिक्शनरी। |

### वापसी मान

सही यदि डिक्शनरी का आकार और डेटा मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) method

विभिन्न प्रकारों वाले सॉर्टेड डिक्शनरी की तुलना करता है।

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| K1 | बाएँ हाथ के डिक्शनरी कुंजी प्रकार। |
| U1 | बाएँ हाथ के डिक्शनरी मैप्ड प्रकार। |
| K2 | दाएँ हाथ के डिक्शनरी कुंजी प्रकार। |
| U2 | दाएँ हाथ के डिक्शनरी मैप्ड प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | बाएँ हाथ का डिक्शनरी। |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | दाएँ हाथ का डिक्शनरी। |

### वापसी मान

हमेशा गलत लौटाता है क्योंकि यहाँ प्रकार रूपांतरण वर्जित है।

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) method

नॉन-पॉइंटर मैप्ड प्रकारों वाली सॉर्टेड सूची की तुलना करता है।

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| K | कुंजी प्रकार। |
| U | मैप्ड प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | बाएँ हाथ की सूची। |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | दाएँ हाथ की सूची। |

### वापसी मान

सही यदि सूची का आकार और डेटा मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&) method

पॉइंटर मैप्ड प्रकारों वाली सॉर्टेड सूची की तुलना करता है।

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| K | कुंजी प्रकार। |
| U | मैप्ड पॉइंटेड प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | बाएँ हाथ की सूची। |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | दाएँ हाथ की सूची। |

### वापसी मान

सही यदि सूची का आकार और डेटा मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) method

विभिन्न प्रकारों वाली सॉर्टेड सूची की तुलना करता है।

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| K1 | बाएँ हाथ की सूची कुंजी प्रकार। |
| U1 | बाएँ हाथ की सूची मैप्ड प्रकार। |
| K2 | दाएँ हाथ की सूची कुंजी प्रकार। |
| U2 | दाएँ हाथ की सूची मैप्ड प्रकार। |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | बाएँ हाथ की सूची। |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | दाएँ हाथ की सूची। |

### वापसी मान

हमेशा गलत लौटाता है क्योंकि यहाँ प्रकार रूपांतरण वर्जित है।

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) method

स्ट्रिंग कलेक्शन की तुलना करता है।

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | बाएँ हाथ का कलेक्शन। |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | दाएँ हाथ का कलेक्शन। |

### वापसी मान

सही यदि आकार और डेटा मेल खाता है, अन्यथा गलत।

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) method

IEnumerable इंस्टेंस की तुलना करता है।

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | बाएँ हाथ का एने्यूमेरेबल ऑब्जेक्ट। |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | दाएँ हाथ का एने्यूमेरेबल ऑब्जेक्ट। |

### वापसी मान

सही यदि आकार और डेटा मेल खाता है, अन्यथा गलत।

## देखें भी

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../../array/)
* Class [List](../../../system.collections.generic/list/)
* Class [Dictionary](../../../system.collections.generic/dictionary/)
* Class [HashSet](../../../system.collections.generic/hashset/)
* Class [QueuePtr](../../../system.collections.generic/queueptr/)
* Class [Stack](../../../system.collections.generic/stack/)
* Class [SortedDictionary](../../../system.collections.generic/sorteddictionary/)
* Class [SortedList](../../../system.collections.generic/sortedlist/)
* Class [StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [TestCompare](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)