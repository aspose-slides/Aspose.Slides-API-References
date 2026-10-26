---
title: get_RotationAngle()
second_title: Aspose.Slides for C++ API リファレンス
description: バウンディングボックス内のテキストに適用されるカスタム回転を指定します。指定されていない場合は、付随するシェイプの回転が使用されます。指定されている場合、この回転はシェイプとは独立して適用されます。つまり、シェイプに回転が適用されている状態に加えて、テキスト自体にも回転が適用される可能性があります。このプロパティとプロパティ TextVerticalType の事前定義された縦方向タイプから要約された視覚テキスト回転の結果値です。Read **float**.
type: docs
weight: 235
url: /ja/aspose.slides.charts/icharttextblockformat/get_rotationangle/
---
## IChartTextBlockFormat::get_RotationAngle() メソッド


バウンディングボックス内のテキストに適用されるカスタム回転を指定します。指定されていない場合は、付随するシェイプの回転が使用されます。指定されている場合、この回転はシェイプとは独立して適用されます。つまり、シェイプに回転が適用されている状態に加えて、テキスト自体にも回転が適用される可能性があります。このプロパティとプロパティ TextVerticalType の事前定義された縦方向タイプから要約された視覚テキスト回転の結果値です。読み取り **float**.

```cpp
virtual float Aspose::Slides::Charts::IChartTextBlockFormat::get_RotationAngle()=0
```

## 備考


シェイプに 90 度の時計回りの回転が適用されている場合を考えてみます。さらに、テキスト本体自体に -90 度の反時計回りの回転が適用されます。この場合、結果としてシェイプは回転したように見えますが、その内部のテキストはまるで回転していないかのように表示されます。 
## 参照

* クラス [IChartTextBlockFormat](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)