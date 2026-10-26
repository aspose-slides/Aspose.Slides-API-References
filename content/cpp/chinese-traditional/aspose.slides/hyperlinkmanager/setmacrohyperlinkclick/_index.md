---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides for C++ API 參考文件
description: 在點擊時設定宏超連結。
type: docs
weight: 79
url: /zh-hant/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager::SetMacroHyperlinkClick(System::String) 方法


設定宏超連結於點擊時。

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetMacroHyperlinkClick(System::String macroName) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | 宏的名稱 |

### 返回值

[Hyperlink](../../hyperlink/) object [IHyperlink](../../ihyperlink/)
## 備註



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```


## 另見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IHyperlink](../../ihyperlink/)
* 類別 [String](../../../system/string/)
* 類別 [HyperlinkManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)