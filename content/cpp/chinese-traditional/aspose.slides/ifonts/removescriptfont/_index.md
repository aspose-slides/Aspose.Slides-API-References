---
title: RemoveScriptFont()
second_title: Aspose.Slides for C++ API 參考
description: 從主題的字型集合中移除與特定腳本標籤相關聯的字型設定。
type: docs
weight: 118
url: /zh-hant/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) 方法


移除與特定腳本標籤相關聯的字型設定，從主題的字型集合中。

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | 應移除其字型設定的 BCP-47 腳本代碼。 |
## 備註



此範例示範如何移除希伯來語腳本的字型映射：
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## 另見

* 類別 [String](../../../system/string/)
* 類別 [IFonts](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)