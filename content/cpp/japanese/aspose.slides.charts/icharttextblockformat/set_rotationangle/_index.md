---
title: set_RotationAngle()
second_title: Aspose.Slides for C++ APIリファレンス
description: バウンディングボックス内のテキストに適用されるカスタム回転を指定します。指定されていない場合は、付随するシェイプの回転が使用されます。指定されている場合、この回転はシェイプとは独立して適用されます。つまり、シェイプに回転が適用されると同時に、テキスト自体にも回転が適用される可能性があります。このプロパティとプロパティ TextVerticalType の事前定義された垂直タイプから要約された視覚テキスト回転の結果値です。書き込み float.
type: docs
weight: 248
url: /ja/aspose.slides.charts/icharttextblockformat/set_rotationangle/
---
## IChartTextBlockFormat::set_RotationAngle(float) メソッド


バウンディングボックス内のテキストに適用されるカスタム回転を指定します。指定されていない場合は、付随するシェイプの回転が使用されます。指定されている場合、この回転はシェイプとは独立して適用されます。つまり、シェイプに回転が適用されると同時に、テキスト自体にも回転が適用される可能性があります。このプロパティとプロパティ TextVerticalType の事前定義された垂直タイプから要約された視覚テキスト回転の結果値です。書き込み **float**。

```cpp
virtual void Aspose::Slides::Charts::IChartTextBlockFormat::set_RotationAngle(float value)=0
```

## 備考


シェイプに時計回り 90 度の回転が適用されている場合を考えてみます。これに加えて、テキスト本体自体に反時計回り -90 度の回転が適用されているとします。その結果、シェイプは回転したように見えますが、内部のテキストはまったく回転していないかのように見えます。 

## 参照

* クラス [IChartTextBlockFormat](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)