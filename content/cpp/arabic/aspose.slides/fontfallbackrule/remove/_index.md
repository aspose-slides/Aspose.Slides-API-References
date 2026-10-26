---
title: Remove()
second_title: مرجع API Aspose.Slides للغة C++
description: يزيل الظهور الأول لخط FallBack محدد من القائمة.
type: docs
weight: 118
url: /ar/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) طريقة


يزيل الظهور الأول لخط FallBack معين من القائمة.

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```


### المعلمات

| معلمة | نوع | وصف |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | اسم الخط لإزالته من القائمة. |
## ملاحظات



```cpp
// إنشاء قاعدة تحتوي على قائمة خطوط.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// إزالة Tahoma من القائمة.
newRule->Remove(u"Tahoma");
```


## انظر أيضاً

* فئة [String](../../../system/string/)
* فئة [FontFallBackRule](../)
* مساحة أسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)