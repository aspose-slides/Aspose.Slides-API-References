---
title: WriteShapeStart()
second_title: Aspose.Slides for C++ API 參考
description: 在圖形渲染之前呼叫。每個圖形呼叫一次。如果此函式向產生器寫入任何內容，則當前投影片影像的產生將會結束，插入新增的 HTML 片段，並在先前的影像上方開始產生新影像。
type: docs
weight: 53
url: /zh-hant/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) 方法

在圖形渲染之前呼叫。每個圖形呼叫一次。如果此函式向產生器寫入任何內容，則當前投影片影像的產生將會結束，插入新增的 HTML 片段，並在先前的影像上方開始產生新影像。

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | 輸出物件。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | 即將渲染的 [Shape](../../../aspose.slides/shape/)。 |

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IHtmlGenerator](../../ihtmlgenerator/)
* 類別 [IShape](../../../aspose.slides/ishape/)
* 類別 [IHtmlFormattingController](../)
* 名稱空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)