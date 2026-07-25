---
title: get_Value()
second_title: Aspose.Slides for C++ API リファレンス
description: "セルの値を取得します。System::Object を参照してください。"
type: docs
weight: 27
url: /ja/aspose.slides.charts/ichartdatacell/get_value/
---
## IChartDataCell::get_Value() メソッド


セルの値を取得します。[System::Object](../../../system/object/) を参照してください。

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Charts::IChartDataCell::get_Value()=0
```

## 備考


```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [IChartDataCell](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)