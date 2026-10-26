---
title: CollectionsToMsg()
second_title: Aspose.Slides for C++ API संदर्भ
description: संदेश प्रतिनिधित्व के लिए दो संग्रहों को क्रमबद्ध करता है।
type: docs
weight: 53
url: /hi/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) विधि

दो संग्रहों को संदेश प्रतिनिधित्व के लिए क्रमबद्ध करता है।

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | अपेक्षित संग्रह तत्व प्रकार। |
| T2 | वास्तविक संग्रह तत्व प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | एक कस्टम स्ट्रिंग जो परिणामी संदेश में अपेक्षित मान से पहले सम्मिलित की जाती है। |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | अपेक्षित संग्रह। |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | वास्तविक संग्रह। |

### वापसी मान

संग्रहों की सामग्री पर उपयोगकर्ता-अनुकूल संदेश।

## देखें

* Typedef [SharedPtr](../../sharedptr/)
* क्लास [String](../../string/)
* क्लास [IEnumerable](../../../system.collections.generic/ienumerable/)
* संरचना [CollectionAssertHelper](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)