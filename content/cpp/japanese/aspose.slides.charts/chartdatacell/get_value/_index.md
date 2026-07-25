---
title: get_Value()
second_title: Aspose.Slides for C++ API リファレンス
description: "セルの値を取得します。System::Object を参照してください。"
type: docs
weight: 27
url: /ja/aspose.slides.charts/chartdatacell/get_value/
---
## ChartDataCell::get_Value() メソッド


セルの値を取得します。参照 [System::Object](../../../system/object/).

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Charts::ChartDataCell::get_Value() override
```

## 備考



```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [ChartDataCell](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)