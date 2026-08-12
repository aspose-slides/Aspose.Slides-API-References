---
title: MakeDiff()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: दो संग्रहों के बीच 'diff' की गणना करता है। प्रत्येक संग्रह के प्रत्येक तत्व को कुंजी के रूप में ले कर परिणाम मान सकारात्मक होगा यदि तत्व \"expected\" संग्रह में अधिक बार प्रकट होता है, नकारात्मक होगा यदि तत्व \"actual\" संग्रह में अधिक बार प्रकट होता है, और शून्य होगा यदि तत्व दोनों संग्रहों में समान संख्या में प्रकट होता है।
type: docs
weight: 1
url: /hi/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) मेथड


दो संग्रहों के बीच 'diff' की गणना करता है। प्रत्येक संग्रह के प्रत्येक तत्व को कुंजी के रूप में लेते हुए परिणाम मान तब सकारात्मक होगा जब तत्व "expected" संग्रह में अधिक बार प्रकट हो, नकारात्मक होगा जब तत्व "actual" संग्रह में अधिक बार प्रकट हो, और शून्य होगा जब तत्व दोनों संग्रहों में समान बार प्रकट हो।

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```


### टेम्प्लेट पैरामीटर

| Parameter | Description |
| --- | --- |
| T1 | अपेक्षित संग्रह तत्व प्रकार। |
| T2 | वास्तविक संग्रह तत्व प्रकार। |

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | अपेक्षित संग्रह। |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | वास्तविक संग्रह। |

### रिटर्न वैल्यू

ऊपर बताए नियमों के अनुसार प्रत्येक मान तुलना परिणामों का मानचित्र।

## संबंधित देखें

* Typedef [SharedPtr](../../sharedptr/)
* Class [Dictionary](../../../system.collections.generic/dictionary/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)