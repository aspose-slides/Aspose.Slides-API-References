---
title: SetScriptFont()
second_title: Aspose.Slides C++ API 參考
description: 將字型名稱指派給特定的腳本標籤，該標籤定義了演示文稿中此腳本文字的呈現方式。
type: docs
weight: 105
url: /zh-hant/aspose.slides/ifonts/setscriptfont/
---
## IFonts::SetScriptFont(System::String, System::String) 方法


將字型名稱指派給特定的腳本標籤，該標籤定義了演示文稿中該腳本文字的呈現方式。

```cpp
virtual void Aspose::Slides::IFonts::SetScriptFont(System::String script, System::String fontName)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | 識別文字系統的 BCP-47 腳本代碼 (例如 "Arab", "Hebr", "Hans") |
| fontName | [System::String](../../../system/string/) | 要指派給指定腳本的字型名稱 |
## 備註



此範例示範如何將阿拉伯腳本的字型設定為 "Segoe UI"： 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## 另見

* 類別 [String](../../../system/string/)
* 類別 [IFonts](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)