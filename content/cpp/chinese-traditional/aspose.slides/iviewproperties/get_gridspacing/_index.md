---
title: get_GridSpacing()
second_title: Aspose.Slides for C++ API 參考
description: 傳回應在簡報文件底層使用的格線間距（以點為單位）。讀取 float.
type: docs
weight: 92
url: /zh-hant/aspose.slides/iviewproperties/get_gridspacing/
---
## IViewProperties::get_GridSpacing() 方法


傳回應在簡報文件底層使用的格線間距（以點為單位）。讀取 **float**.

```cpp
virtual float Aspose::Slides::IViewProperties::get_GridSpacing()=0
```

## 備註


格線間距值必須是正數。典型的值範圍是從 1 mm（2.8349607 點）到 2 英吋（144 點）。

以下範例程式碼示範如何在 PowerPoint 簡報中變更格線間距。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## 參見

* 類別 [IViewProperties](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)