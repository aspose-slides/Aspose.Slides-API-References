---
title: GetScriptFont()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得與簡報主題中特定腳本標記相關聯的字型名稱。
type: docs
weight: 92
url: /zh-hant/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) 方法


取得與簡報主題中特定腳本標記相關聯的字型名稱。

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | 用於辨識書寫系統的 BCP-47 腳本代碼（例如 "Latn", "Cyrl", "Jpan"）。 |

### 返回值

指定腳本所使用的字型名稱；如果未定義該腳本，則返回 **null**。
## 備註



此範例示範如何從簡報主題中取得指派給西里爾字母腳本的字型。 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## 參見

* 類別 [String](../../../system/string/)
* 類別 [IFonts](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)