---
title: AddFallBackFonts()
second_title: Aspose.Slides C++ API 參考
description: 將新的字型（可複數）加入 FallBack 字型清單。
type: docs
weight: 79
url: /zh-hant/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) 方法

將新的字型（可複數）加入 FallBack 字型清單。

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | 用於 FallBack 的字型名稱，若有多個則以逗號分隔 |
## 備註



```cpp
// 建立 FontFallBackRule 的新實例
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//新增第二個字型至規則
newRule->AddFallBackFonts(u"MS Gothic");
//新增第三與第四個字型至規則
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) 方法

將新的字型加入 FallBack 字型清單。

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | 用於 FallBack 的字型名稱，若有多個則以逗號分隔 |
## 備註



```cpp
//建立 FontFallBackRule 的新實例
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//新增另外三個字型至規則
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [FontFallBackRule](../)
* 名稱空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)