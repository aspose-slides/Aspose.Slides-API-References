---
title: WriteShapeStart()
second_title: Aspose.Slides for C++ API 參考文件
description: 在形狀渲染之前呼叫。每個形狀呼叫一次。如果此函式寫入任何內容到 generator，則目前投影片圖像的產生將結束，插入已新增的 HTML 片段，並在先前的圖像之上開始產生新圖像。
type: docs
weight: 66
url: /zh-hant/aspose.slides.export/embedallfontshtmlcontroller/writeshapestart/
---
## EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) 方法

在形狀渲染之前呼叫。每個形狀呼叫一次。如果此函式寫入任何內容到 generator，則目前投影片的圖像產生將結束，插入已新增的 HTML 片段，並在先前圖像之上開始產生新的圖像。

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | 輸出物件。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) 正在渲染。 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IHtmlGenerator](../../ihtmlgenerator/)
* 類別 [IShape](../../../aspose.slides/ishape/)
* 類別 [EmbedAllFontsHtmlController](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 程式庫 [Aspose.Slides](../../../)