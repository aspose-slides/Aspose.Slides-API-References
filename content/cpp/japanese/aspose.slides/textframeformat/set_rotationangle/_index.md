---
title: set_RotationAngle()
second_title: Aspose.Slides for C++ API リファレンス
description: バウンディングボックス内のテキストに適用される回転をカスタムで指定します。指定されていない場合は、付随するシェイプの回転が使用されます。指定された場合、この回転はシェイプとは独立して適用されます。つまり、シェイプに回転が適用されている上で、テキスト自体にも回転が適用されることがあります。このプロパティとプロパティ TextVerticalType の事前定義された垂直タイプから要約された視覚的テキスト回転の結果値です。float を書き込みます。
type: docs
weight: 313
url: /ja/aspose.slides/textframeformat/set_rotationangle/
---
## TextFrameFormat::set_RotationAngle(float) メソッド

バウンディングボックス内のテキストに適用される回転をカスタムで指定します。指定されていない場合は、付随するシェイプの回転が使用されます。指定された場合、この回転はシェイプとは独立して適用されます。つまり、シェイプに回転が適用されている上で、テキスト自体にも回転が適用されることがあります。このプロパティとプロパティ TextVerticalType の事前定義された垂直タイプから要約された視覚的テキスト回転の結果値です。**float** を書き込みます。

```cpp
void Aspose::Slides::TextFrameFormat::set_RotationAngle(float value) override
```

## 備考

シェイプに時計回り 90 度の回転が適用されている場合を考えてみてください。さらに、テキスト本体自体に反時計回り -90 度の回転が適用されます。この場合、シェイプ自体は回転して見えますが、内部のテキストはまるで回転していないかのように表示されます。

## 関連項目

* クラス [TextFrameFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)