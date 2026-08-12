---
title: ConstrainedCopy()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट स्रोत से शुरू होते हुए एक System.Array से तत्वों की सीमा को कॉपी करता है।
type: docs
weight: 716
url: /hi/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) विधि

निर्दिष्ट स्रोत से शुरू होते हुए एक [System.Array](../) से तत्वों की सीमा को कॉपी करता है।

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| SrcType | स्रोत ऐरे में तत्वों का प्रकार |
| DstType | गंतव्य ऐरे में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | स्रोत ऐरे |
| srcIndex | **int64_t** | स्रोत ऐरे में वह [Index](../../index/) जो कॉपी करने वाले आइटम्स की सीमा की शुरुआत को दर्शाता है |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | गंतव्य ऐरे |
| dstIndex | **int64_t** | गंतव्य ऐरे में [Index](../../index/) जहाँ कॉपी किए गए आइटम्स डालना शुरू किया जाता है |
| count | **int64_t** | कॉपी करने के लिए तत्वों की संख्या |

## टिप्पणी

अस्थायी कच्चा कार्यान्वयन बिना किसी अनडन के!

## देखें

* टाइपडिफ़ [ArrayPtr](../../arrayptr/)
* क्लास [Array](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)