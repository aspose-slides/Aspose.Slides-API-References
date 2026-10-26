---
title: UnboxToNullable()
second_title: Aspose.Slides for C++ API संदर्भ
description: ऑब्जेक्ट को nullable प्रकार में अनबॉक्स करता है।
type: docs
weight: 79
url: /hi/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) पद्धति

ऑब्जेक्ट को nullable प्रकार में अनबॉक्स करता है।

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | गंतव्य प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) को अनबॉक्स करने के लिए। |
| safe | **bool** | यदि true हो, तो विफलता पर nullptr लौटाएगा, अन्यथा InvalidCastException फेंकेगा। |

### रिटर्न मान

अनबॉक्स्ड nullable मान (null हो सकता है)।  

## संबंधित देखें

* क्लास [Nullable](../../nullable/)
* क्लास [SmartPtr](../../smartptr/)
* क्लास [Object](../../object/)
* क्लास [ObjectExt](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)