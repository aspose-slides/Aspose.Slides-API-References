---
title: SetExternalHyperlinkClick()
second_title: Aspose.Slides C++ API 參考
description: 在點擊時設定外部超連結。
type: docs
weight: 1
url: /zh-hant/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) 方法

設定點擊時的外部超連結。

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |

## 備註

以下範例程式碼示範如何使用 [Hyperlink](../../hyperlink/) 新增文字方塊。

```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// 取得簡報中的第一張投影片
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// 新增一個 AutoShape 物件，類型設為 Rectangle
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// 取得與 AutoShape 相關聯的 ITextFrame 屬性
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// 向框架加入一些文字
portion->set_Text(u"Aspose.Slides");

// 設定此段文字的超連結
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// 儲存 PPTX 簡報
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IHyperlink](../../ihyperlink/)
* 類別 [String](../../../system/string/)
* 類別 [HyperlinkManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)