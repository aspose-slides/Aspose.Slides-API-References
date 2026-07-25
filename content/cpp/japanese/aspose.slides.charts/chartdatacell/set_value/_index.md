---
title: set_Value()
second_title: Aspose.Slides の C++ API リファレンス
description: "セルの値を設定します。System::Object を書き込みます。"
type: docs
weight: 40
url: /ja/aspose.slides.charts/chartdatacell/set_value/
---
## ChartDataCell::set_Value(System::SharedPtr\<System::Object\>) メソッド

セルの値を設定します。[System::Object](../../../system/object/) を書き込みます。

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Value(System::SharedPtr<System::Object> value) override
```

## 備考

```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [ChartDataCell](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)