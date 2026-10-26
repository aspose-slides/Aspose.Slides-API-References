---
title: WriteShapeEnd()
second_title: Aspose.Slides for C++ API 參考
description: 在形狀渲染之前被呼叫。每個形狀呼叫一次。如果此函式寫入任何內容到產生器，則目前投影片影像的產生將結束，加入的 HTML 片段會被插入，並且新的影像會在先前的影像之上開始。
type: docs
weight: 79
url: /zh-hant/aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---
## EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) 方法


在形狀渲染之前呼叫。每個形狀呼叫一次。若此函式向產生器寫入任何內容，則目前投影片影像的產生將結束，加入的 HTML 片段將被插入，並且新的影像會在先前的影像上方開始。

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | 輸出物件。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) 為最後渲染的。 |

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IHtmlGenerator](../../ihtmlgenerator/)
* 類別 [IShape](../../../aspose.slides/ishape/)
* 類別 [EmbedAllFontsHtmlController](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)