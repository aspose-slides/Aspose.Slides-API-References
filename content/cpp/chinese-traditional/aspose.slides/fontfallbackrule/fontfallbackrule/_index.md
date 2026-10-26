---
title: FontFallBackRule()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立新實例。
type: docs
weight: 66
url: /zh-hant/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) 建構子

建立新實例。

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | **uint32_t** | Unicode 範圍的起始索引 |
| endIndex | **uint32_t** | Unicode 範圍的結束索引 |
| fontNames | [System::String](../../../system/string/) | 回退使用的字體名稱或多個名稱（以逗號分隔） |
## 備註

```cpp
// 建立 FantFallBackRule 的新實例，使用單一字體。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// 建立 FantFallBackRule 的新實例，使用多個字體。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```

## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) 建構子

建立新實例。

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | **uint32_t** | Unicode 範圍的起始索引 |
| endIndex | **uint32_t** | Unicode 範圍的結束索引 |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | 回退使用的字體名稱或多個名稱（以逗號分隔） |
## 備註

```cpp
// 建立 FantFallBackRule 的新實例，使用兩個字體
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// 建立 FantFallBackRule 的新實例，使用多個字體。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## 參見

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [FontFallBackRule](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)