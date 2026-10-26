---
title: SetExternalHyperlinkClick()
second_title: Aspose.Slides C++ API 参考
description: 设置点击时的外部超链接。
type: docs
weight: 1
url: /zh/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) 方法


设置点击时的外部超链接。

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL。 |
## 备注



以下示例代码展示了如何使用 [Hyperlink](../../hyperlink/) 添加文本框。 
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// 获取演示文稿中的第一张幻灯片
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// 添加 AutoShape 对象，类型设为矩形
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// 访问与 AutoShape 关联的 ITextFrame 属性
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// 向框中添加一些文本
portion->set_Text(u"Aspose.Slides");

// 为文本段落设置超链接
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// 保存 PPTX 演示文稿
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IHyperlink](../../ihyperlink/)
* 类 [String](../../../system/string/)
* 类 [HyperlinkManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)