---
title: FontFallBackRule()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया इंस्टेंस बनाता है।
type: docs
weight: 66
url: /hi/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) कंस्ट्रक्टर

एक नया इंस्टेंस बनाता है।

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```

### आर्ग्युमेंट्स

| परामीटर | टाइप | वर्णन |
| --- | --- | --- |
| startIndex | **uint32_t** | Unicode रेंज का प्रारंभिक सूचकांक |
| endIndex | **uint32_t** | Unicode रेंज का अंत सूचकांक |
| fontNames | [System::String](../../../system/string/) | फ़ॉन्ट का नाम या नाम (कॉमा द्वारा विभाजित) फ़ॉलबैक के लिए |
## टिप्पणियाँ

```cpp
// FantFallBackRule का एक फ़ॉन्ट के साथ नया इंस्टेंस बनाएं।
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// FantFallBackRule के कई फ़ॉन्ट के साथ नया इंस्टेंस बनाएं।
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```

## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) कंस्ट्रक्टर

एक नया इंस्टेंस बनाता है।

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```

### आर्ग्युमेंट्स

| परामीटर | टाइप | वर्णन |
| --- | --- | --- |
| startIndex | **uint32_t** | Unicode रेंज का प्रारंभिक सूचकांक |
| endIndex | **uint32_t** | Unicode रेंज का अंत सूचकांक |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | फ़ॉन्ट का नाम या नाम (कॉमा द्वारा विभाजित) फ़ॉलबैक के लिए |
## टिप्पणियाँ

```cpp
// दो फ़ॉन्ट के साथ FantFallBackRule का नया इंस्टेंस बनाएं
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// कई फ़ॉन्ट के साथ FantFallBackRule का नया इंस्टेंस बनाएं।
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## संबंधित देखें

* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* क्लास [String](../../../system/string/)
* क्लास [FontFallBackRule](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)