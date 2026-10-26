---
title: RemoveScriptFont()
second_title: Aspose.Slides for C++ API 參考
description: 從主題的字體集合中移除與特定腳本標記相關聯的字體設定。
type: docs
weight: 118
url: /zh-hant/aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) 方法

從主題的字體集合中移除與特定腳本標記相關聯的字體設定。

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | 要移除其字體設定的 BCP-47 腳本代碼。 |
## 備註

此範例示範如何移除希伯來文腳本的字體對應關係： 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [Fonts](../)
* 名稱空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)