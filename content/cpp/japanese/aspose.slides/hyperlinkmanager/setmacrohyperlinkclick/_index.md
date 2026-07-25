---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides for C++ API リファレンス
description: クリック時にマクロハイパーリンクを設定します。
type: docs
weight: 79
url: /ja/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager::SetMacroHyperlinkClick(System::String) メソッド

クリック時にマクロハイパーリンクを設定します。

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetMacroHyperlinkClick(System::String macroName) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | マクロの名前 |

### 戻り値

[Hyperlink](../../hyperlink/) オブジェクト [IHyperlink](../../ihyperlink/)
## 備考



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IHyperlink](../../ihyperlink/)
* クラス [String](../../../system/string/)
* クラス [HyperlinkManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)