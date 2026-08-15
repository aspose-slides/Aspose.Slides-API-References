---
title: WriteShapeEnd()
second_title: Aspose.Slides for C++ API 參考文件
description: 在形狀渲染之前呼叫。每個形狀呼叫一次。如果此函式向 generator 寫入任何內容，則當前投影片影像的產生將會結束，插入新增的 HTML 片段，並在先前的影像之上開始產生新的影像。
type: docs
weight: 66
url: /zh-hant/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---
## IHtmlFormattingController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) method

在形狀渲染之前呼叫。每個形狀呼叫一次。如果此函式向 generator 寫入任何內容，則當前投影片影像的產生將會結束，插入新增的 HTML 片段，並在先前的影像之上開始產生新的影像。

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | 輸出物件。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) 最後被渲染。 |

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IHtmlGenerator](../../ihtmlgenerator/)
* 類別 [IShape](../../../aspose.slides/ishape/)
* 類別 [IHtmlFormattingController](../)
* 命名空間 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)