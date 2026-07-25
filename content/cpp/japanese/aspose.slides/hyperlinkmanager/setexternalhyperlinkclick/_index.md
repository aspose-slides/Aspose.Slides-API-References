---
title: SetExternalHyperlinkClick()
second_title: Aspose.Slides for C++ API リファレンス
description: クリック時に外部ハイパーリンクを設定します。
type: docs
weight: 1
url: /ja/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) メソッド

Set external hyperlink on click.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |

## 備考

以下のサンプルコードは、[Hyperlink](../../hyperlink/) を使用してテキスト ボックスを追加する方法を示しています。
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// プレゼンテーションの最初のスライドを取得
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// タイプが矩形に設定された AutoShape オブジェクトを追加
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// AutoShape に関連付けられた ITextFrame プロパティにアクセス
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// フレームにテキストを追加
portion->set_Text(u"Aspose.Slides");

// 項目テキストのハイパーリンクを設定
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// PPTX プレゼンテーションを保存
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```


## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IHyperlink](../../ihyperlink/)
* クラス [String](../../../system/string/)
* クラス [HyperlinkManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)