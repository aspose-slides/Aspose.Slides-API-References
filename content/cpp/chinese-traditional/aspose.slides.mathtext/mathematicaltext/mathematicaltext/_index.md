---
title: MathematicalText()
second_title: Aspose.Slides for C++ API 參考
description: "預設建構子（建立 String::Empty 值）"
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() 建構子


預設建構子（建立 String::Empty 值）

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## 備註


範例： 
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) 建構子


建立 [MathText](../../)，使用單一符號

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathSymbol | char16_t | 單一符號 |
## 備註



範例： 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) 建構子


從文字建立 [MathematicalText](../)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 文字值 |
## 備註



範例： 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) 建構子


從文字與格式設定建立 [MathematicalText](../)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 文字值 |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | 文字格式設定 |
## 備註



範例： 
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [MathematicalText](../)
* 類別 [String](../../../system/string/)
* 類別 [IPortionFormat](../../../aspose.slides/iportionformat/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)