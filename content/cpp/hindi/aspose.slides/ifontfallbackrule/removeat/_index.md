---
title: RemoveAt()
second_title: Aspose.Slides for C++ API संदर्भ
description: सूची में निर्दिष्ट अनुक्रमणिका पर FallBack फ़ॉन्ट को हटाता है।
type: docs
weight: 92
url: /hi/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) method


सूची में निर्दिष्ट अनुक्रमणिका पर FallBack फ़ॉन्ट को हटाता है।

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | फ़ॉन्ट को हटाने के लिए शून्य-आधारित अनुक्रमणिका। |
## Remarks



```cpp
// एक नियम बनाता है जिसमें फ़ॉन्ट्स की सूची होती है।
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//सूची से Tahoma को हटाना
newRule->RemoveAt(2);
```


## See Also

* वर्ग [IFontFallBackRule](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)