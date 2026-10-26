---
title: AddFallBackFonts()
second_title: Aspose.Slides for C++ API 參考
description: 將新字型（多個）新增至備援字型清單。
type: docs
weight: 40
url: /zh-hant/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) 方法

將新字型（多個）新增至備援字型清單。

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | 用於備援的字型名稱或多個名稱（以逗號分隔） |
## 備註



```cpp
//建立 FantFallBackRule 的新實例
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//將第二個字型加入規則
newRule->AddFallBackFonts(u"MS Gothic");
//將第三與第四個字型加入規則
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) 方法

將新字型新增至備援字型清單。

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | 用於備援的字型名稱或多個名稱（以逗號分隔） |
## 備註



```cpp
//建立 FontFallBackRule 的新實例
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//將另外三個字型加入規則
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [IFontFallBackRule](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)