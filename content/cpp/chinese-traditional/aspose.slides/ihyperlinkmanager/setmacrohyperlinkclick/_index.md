---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定點擊時的巨集超連結。
type: docs
weight: 79
url: /zh-hant/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick(System::String) 方法


設定點擊時的巨集超連結。

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | 巨集的名稱 |

### 回傳值

[Hyperlink](../../hyperlink/) 物件 [IHyperlink](../../ihyperlink/)
## 備註



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```




## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IHyperlink](../../ihyperlink/)
* 類別 [String](../../../system/string/)
* 類別 [IHyperlinkManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)