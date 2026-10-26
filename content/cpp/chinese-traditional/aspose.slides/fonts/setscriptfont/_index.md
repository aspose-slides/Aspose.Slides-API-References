---
title: SetScriptFont()
second_title: Aspose.Slides for C++ API 參考
description: 將字體名稱指定給特定的腳本標籤，該標籤定義了簡報中該腳本文字的呈現方式。
type: docs
weight: 105
url: /zh-hant/aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) 方法


將字體名稱指派給特定的腳本標籤，該標籤定義了簡報中該腳本文字的呈現方式。

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | 用於識別書寫系統的 BCP-47 腳本代碼（例如「Arab」、「Hebr」、「Hans」）。 |
| fontName | [System::String](../../../system/string/) | 指派給指定腳本的字體名稱。 |
## 備註



以下範例示範如何將阿拉伯腳本的字體設定為「Segue UI」：
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## 另見

* 類別 [String](../../../system/string/)
* 類別 [Fonts](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)