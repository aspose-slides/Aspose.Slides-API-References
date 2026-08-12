---
title: NotNullAreEqual()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: मान प्रकारों की डिक्शनरीज़ की समान-तुलना करता है।
type: docs
weight: 53
url: /hi/system.testpredicates.details.sharedptrasserts/notnullareequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&) फ़ंक्शन

मान प्रकारों की डिक्शनरीज़ की समान-तुलना करता है।

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &rhs)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| K | कुंजी प्रकार। |
| V | मूल्य प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | बाएँ हाथ की अभिव्यक्ति। |
| rhs_expr | const char * | दाएँ हाथ की अभिव्यक्ति। |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | बाएँ हाथ का मान। |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | दाएँ हाथ का मान। |

### रिटर्न वैल्यू

gtest-शैली वाला अभिकथन परिणाम।

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\&) फ़ंक्शन

शेयर किए गए पॉइंटर्स की डिक्शनरीज़ की समान-तुलना करता है।

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &rhs)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| K | कुंजी प्रकार। |
| V | मूल्य प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | बाएँ हाथ की अभिव्यक्ति। |
| rhs_expr | const char * | दाएँ हाथ की अभिव्यक्ति। |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | बाएँ हाथ का मान। |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | दाएँ हाथ का मान। |

### रिटर्न वैल्यू

gtest-शैली वाला अभिकथन परिणाम।

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::HashSet\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::HashSet\<T2\>\>\&) फ़ंक्शन

हैशसेट्स की समान-तुलना करता है।

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::HashSet<T1>> &lhs, const SharedPtr<System::Collections::Generic::HashSet<T2>> &rhs)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | बाएँ हाथ कंटेनर तत्व प्रकार। |
| T2 | दाएँ हाथ कंटेनर तत्व प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | बाएँ हाथ की अभिव्यक्ति। |
| rhs_expr | const char * | दाएँ हाथ की अभिव्यक्ति। |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T1\>\>\& | बाएँ हाथ का मान। |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T2\>\>\& | दाएँ हाथ का मान। |

### रिटर्न वैल्यू

gtest-शैली वाला अभिकथन परिणाम।

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Queue\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Queue\<T2\>\>\&) फ़ंक्शन

क्यूज़ की समान-तुलना करता है।

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Queue<T1>> &lhs, const SharedPtr<System::Collections::Generic::Queue<T2>> &rhs)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | बाएँ हाथ कंटेनर तत्व प्रकार। |
| T2 | दाएँ हाथ कंटेनर तत्व प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | बाएँ हाथ की अभिव्यक्ति। |
| rhs_expr | const char * | दाएँ हाथ की अभिव्यक्ति। |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T1\>\>\& | बाएँ हाथ का मान। |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T2\>\>\& | दाएँ हाथ का मान। |

### रिटर्न वैल्यू

gtest-शैली वाला अभिकथन परिणाम।

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Stack\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Stack\<T2\>\>\&) फ़ंक्शन

स्टैक्स की समान-तुलना करता है।

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Stack<T1>> &lhs, const SharedPtr<System::Collections::Generic::Stack<T2>> &rhs)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | बाएँ हाथ कंटेनर तत्व प्रकार। |
| T2 | दाएँ हाथ कंटेनर तत्व प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | बाएँ हाथ की अभिव्यक्ति। |
| rhs_expr | const char * | दाएँ हाथ की अभिव्यक्ति। |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T1\>\>\& | बाएँ हाथ का मान। |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T2\>\>\& | दाएँ हाथ का मान। |

### रिटर्न वैल्यू

gtest-शैली वाला अभिकथन परिणाम।

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&) फ़ंक्शन

मान प्रकारों के क्रमबद्ध डिक्शनरीज़ की समान-तुलना करता है।

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &rhs)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| K | कुंजी प्रकार। |
| V | मूल्य प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | बाएँ हाथ की अभिव्यक्ति। |
| rhs_expr | const char * | दाएँ हाथ की अभिव्यक्ति। |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | बाएँ हाथ का मान। |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | दाएँ हाथ का मान। |

### रिटर्न वैल्यू

gtest-शैली वाला अभिकथन परिणाम।

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>) फ़ंक्शन

शेयर किए गए पॉइंटर्स के क्रमबद्ध डिक्शनरीज़ की समान-तुलना करता है।

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &rhs)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| K | कुंजी प्रकार। |
| V | मूल्य प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | बाएँ हाथ की अभिव्यक्ति। |
| rhs_expr | const char * | दाएँ हाथ की अभिव्यक्ति। |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | बाएँ हाथ का मान। |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | दाएँ हाथ का मान। |

### रिटर्न वैल्यू

gtest-शैली वाला अभिकथन परिणाम।

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&) फ़ंक्शन

मान प्रकारों की क्रमबद्ध सूचियों की समान-तुलना करता है।

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &rhs)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| K | कुंजी प्रकार। |
| V | मूल्य प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | बाएँ हाथ की अभिव्यक्ति। |
| rhs_expr | const char * | दाएँ हाथ की अभिव्यक्ति। |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | बाएँ हाथ का मान। |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | दाएँ हाथ का मान। |

### रिटर्न वैल्यू

gtest-शैली वाला अभिकथन परिणाम।

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>) फ़ंक्शन

शेयर किए गए पॉइंटर्स की क्रमबद्ध सूचियों की समान-तुलना करता है।

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &rhs)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| K | कुंजी प्रकार। |
| V | मूल्य प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | बाएँ हाथ की अभिव्यक्ति। |
| rhs_expr | const char * | दाएँ हाथ की अभिव्यक्ति। |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | बाएँ हाथ का मान। |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | दाएँ हाथ का मान। |

### रिटर्न वैल्यू

gtest-शैली वाला अभिकथन परिणाम।

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::BitArray\>\&, const SharedPtr\<System::Collections::BitArray\>\&) फ़ंक्शन

बिट एरेज़ की समान-तुलना करता है।

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::BitArray> &lhs, const SharedPtr<System::Collections::BitArray> &rhs)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | बाएँ हाथ की अभिव्यक्ति। |
| rhs_expr | const char * | दाएँ हाथ की अभिव्यक्ति। |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | बाएँ हाथ का मान। |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | दाएँ हाथ का मान। |

### रिटर्न वैल्यू

gtest-शैली वाला अभिकथन परिणाम।

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&) फ़ंक्शन

स्ट्रिंग संग्रहों की समान-तुलना करता है।

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Specialized::StringCollection> &lhs, const SharedPtr<System::Collections::Specialized::StringCollection> &rhs)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | बाएँ हाथ की अभिव्यक्ति। |
| rhs_expr | const char * | दाएँ हाथ की अभिव्यक्ति। |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | बाएँ हाथ का मान। |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | दाएँ हाथ का मान। |

### रिटर्न वैल्यू

gtest-शैली वाला अभिकथन परिणाम।

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) फ़ंक्शन

एब्स्ट्रैक्ट संग्रहों की समान-तुलना करता है।

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | तत्व प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | बाएँ हाथ की अभिव्यक्ति। |
| rhs_expr | const char * | दाएँ हाथ की अभिव्यक्ति। |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | बाएँ हाथ का मान। |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | दाएँ हाथ का मान। |

### रिटर्न वैल्यू

gtest-शैली वाला अभिकथन परिणाम।

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<Object\>\&, const SharedPtr\<Object\>\&) फ़ंक्शन

दो [Object](../../system/object/) प्रकारों की समान-तुलना करता है।

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<Object> &lhs, const SharedPtr<Object> &rhs)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | बाएँ हाथ की अभिव्यक्ति। |
| rhs_expr | const char * | दाएँ हाथ की अभिव्यक्ति। |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | बाएँ हाथ का मान। |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | दाएँ हाथ का मान। |

### रिटर्न वैल्यू

gtest-शैली वाला अभिकथन परिणाम।

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<T1\>\&, const SharedPtr\<T2\>\&) फ़ंक्शन

अज्ञात प्रकारों की समान-तुलना करता है।

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<T1> &lhs, const SharedPtr<T2> &rhs)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | बाएँ हाथ ऑब्जेक्ट प्रकार। |
| T2 | दाएँ हाथ ऑब्जेक्ट प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs_expr | const char * | बाएँ हाथ की अभिव्यक्ति। |
| rhs_expr | const char * | दाएँ हाथ की अभिव्यक्ति। |
| lhs | const [SharedPtr](../../system/sharedptr/)\<T1\>\& | बाएँ हाथ का मान। |
| rhs | const [SharedPtr](../../system/sharedptr/)\<T2\>\& | दाएँ हाथ का मान। |

### रिटर्न वैल्यू

gtest-शैली वाला अभिकथन परिणाम।

## संबंधित देखें

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Dictionary](../../system.collections.generic/dictionary/)
* Class [HashSet](../../system.collections.generic/hashset/)
* Class [Queue](../../system.collections.generic/queue/)
* Class [Stack](../../system.collections.generic/stack/)
* Class [SortedDictionary](../../system.collections.generic/sorteddictionary/)
* Class [SortedList](../../system.collections.generic/sortedlist/)
* Class [BitArray](../../system.collections/bitarray/)
* Class [StringCollection](../../system.collections.specialized/stringcollection/)
* Class [ICollection](../../system.collections.generic/icollection/)
* Class [Object](../../system/object/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)