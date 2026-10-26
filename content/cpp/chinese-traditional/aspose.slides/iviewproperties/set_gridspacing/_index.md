---
title: set_GridSpacing()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定應用於簡報文件底層格線的格線間距，單位為點。寫入 float.
type: docs
weight: 105
url: /zh-hant/aspose.slides/iviewproperties/set_gridspacing/
---
## IViewProperties::set_GridSpacing(float) 方法

設定應用於簡報文件底層格線的格線間距，單位為點。寫入 **float**.

```cpp
virtual void Aspose::Slides::IViewProperties::set_GridSpacing(float value)=0
```

## 備註

格線間距值必須為正數。典型的數值範圍為 1 mm（2.8349607 點）至 2 英吋（144 點）。

以下範例程式碼示範如何在 PowerPoint 簡報中變更格線間距。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## 另見

* 類別 [IViewProperties](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)