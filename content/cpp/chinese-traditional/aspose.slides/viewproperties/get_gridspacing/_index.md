---
title: get_GridSpacing()
second_title: Aspose.Slides for C++ API 參考
description: 返回應用於簡報文件底層網格的網格間距，單位為點。讀取 float。
type: docs
weight: 92
url: /zh-hant/aspose.slides/viewproperties/get_gridspacing/
---
## ViewProperties::get_GridSpacing() 方法

返回應用於簡報文件底層網格的網格間距，單位為點。讀取 **float**。

```cpp
float Aspose::Slides::ViewProperties::get_GridSpacing() override
```

## 備註

網格間距值必須為正數。典型的取值範圍是 1 mm（2.8349607 點）到 2 英吋（144 點）。

以下範例程式碼示範如何在 PowerPoint 簡報中變更網格間距。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## 另請參閱

* 類別 [ViewProperties](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)