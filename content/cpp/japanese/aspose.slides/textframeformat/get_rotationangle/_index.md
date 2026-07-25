---
title: get_RotationAngle()
second_title: Aspose.Slides for C++ API リファレンス
description: バウンディングボックス内のテキストに適用される回転をカスタムで指定します。指定されていない場合は、付随するシェイプの回転が使用されます。指定された場合、この回転はシェイプとは独立して適用されます。つまり、シェイプに回転が適用されている上で、テキスト自体にも回転が適用されることがあります。このプロパティとプロパティ TextVerticalType の事前定義された縦方向タイプから合成された視覚的テキスト回転の結果値です。float を取得します。
type: docs
weight: 300
url: /ja/aspose.slides/textframeformat/get_rotationangle/
---
## TextFrameFormat::get_RotationAngle() method

バウンディングボックス内のテキストに適用される回転をカスタムで指定します。指定されていない場合は、付随するシェイプの回転が使用されます。指定された場合、この回転はシェイプとは独立して適用されます。つまり、シェイプに回転が適用されている上で、テキスト自体にも回転が適用されることがあります。視覚的なテキスト回転の結果値は、このプロパティとプロパティ TextVerticalType の事前定義された縦方向タイプから合成されます。戻り値は **float** です。

```cpp
float Aspose::Slides::TextFrameFormat::get_RotationAngle() override
```

## 備考

シェイプに 90 度時計回りの回転が適用されている場合を考えてみてください。さらに、テキスト本体自体にも -90 度反時計回りの回転が適用されているとします。この場合、シェイプは回転したように見えますが、その内部のテキストはまるで回転していないかのように表示されます。

## 参照

* クラス [TextFrameFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)