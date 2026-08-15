---
title: GetScriptFont()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得與簡報佈景主題中特定腳本標籤相關聯的字型名稱。
type: docs
weight: 92
url: /zh-hant/aspose.slides/fonts/getscriptfont/
---
## Fonts::GetScriptFont(System::String) 方法


取得與簡報佈景主題中特定腳本標籤相關聯的字型名稱。

```cpp
System::String Aspose::Slides::Fonts::GetScriptFont(System::String script) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | 用於識別書寫系統的 BCP-47 腳本代碼（例如 \"Latn\", \"Cyrl\", \"Jpan\"）。 |

### 返回值

指定腳本使用的字型名稱；如果未定義該腳本，則返回 **null**。

## 備註

此範例示範如何在簡報佈景主題中取得指派給西里爾文字腳本的字型。 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## 另見

* 類別 [String](../../../system/string/)
* 類別 [Fonts](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)