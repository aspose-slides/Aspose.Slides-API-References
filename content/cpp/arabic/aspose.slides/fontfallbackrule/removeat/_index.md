---
title: RemoveAt()
second_title: مرجع API Aspose.Slides للـ C++
description: يزيل خط FallBack في الفهرس المحدد من القائمة.
type: docs
weight: 131
url: /ar/aspose.slides/fontfallbackrule/removeat/
---
## طريقة FontFallBackRule::RemoveAt(int32_t)

يزيل الخط FallBack في الفهرس المحدد من القائمة.

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري للخط المراد إزالته. |
## ملاحظات



```cpp
// إنشاء قاعدة تحتوي على قائمة من الخطوط.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// إزالة Tahoma من القائمة.
newRule->RemoveAt(2);
```


## انظر أيضًا

* الفئة [FontFallBackRule](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)