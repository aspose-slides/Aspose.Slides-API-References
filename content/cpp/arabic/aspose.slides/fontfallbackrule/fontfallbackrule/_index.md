---
title: FontFallBackRule()
second_title: Aspose.Slides لمرجع واجهة برمجة التطبيقات C++
description: ينشئ نسخة جديدة.
type: docs
weight: 66
url: /ar/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) constructor

ينشئ نسخة جديدة.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | **uint32_t** | فهرس البداية لنطاق Unicode |
| endIndex | **uint32_t** | فهرس النهاية لنطاق Unicode |
| fontNames | [System::String](../../../system/string/) | اسم الخط أو الأسماء (مفصولة بفواصل) للعودة الافتراضية |

## ملاحظات

```cpp
// إنشاء نسخة جديدة من FantFallBackRule بخط واحد.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// إنشاء نسخة جديدة من FantFallBackRule بعدة خطوط.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```

## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) constructor

ينشئ نسخة جديدة.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | **uint32_t** | فهرس البداية لنطاق Unicode |
| endIndex | **uint32_t** | فهرس النهاية لنطاق Unicode |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | اسم الخط أو الأسماء (مفصولة بفواصل) للعودة الافتراضية |

## ملاحظات

```cpp
// إنشاء نسخة جديدة من FantFallBackRule بخطين
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// إنشاء نسخة جديدة من FantFallBackRule بعدة خطوط.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [FontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)