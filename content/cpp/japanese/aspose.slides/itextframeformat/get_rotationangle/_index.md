---
title: get_RotationAngle()
second_title: Aspose.Slides の C++ API リファレンス
description: バウンディングボックス内のテキストに適用されるカスタム回転を指定します。指定されていない場合は、付随するシェイプの回転が使用されます。指定された場合、シェイプとは独立して適用されます。つまり、シェイプに回転が適用されているだけでなく、テキスト自体にも回転が適用されることがあります。このプロパティとプロパティ TextVerticalType の事前定義された垂直タイプから要約された視覚的テキスト回転の結果値です。Read float.
type: docs
weight: 339
url: /ja/aspose.slides/itextframeformat/get_rotationangle/
---
## ITextFrameFormat::get_RotationAngle() メソッド

テキストがバウンディングボックス内に適用されるカスタム回転を指定します。指定されていない場合、付随するシェイプの回転が使用されます。指定された場合、シェイプとは独立して適用されます。つまり、シェイプに回転が適用されているだけでなく、テキスト自体にも回転が適用されることがあります。このプロパティとプロパティ TextVerticalType の事前定義された垂直タイプから要約される視覚的テキスト回転の結果値です。Read **float**。

```cpp
virtual float Aspose::Slides::ITextFrameFormat::get_RotationAngle()=0
```

## 備考

シェイプに時計回りに 90 度の回転が適用されているケースを考えてみます。さらに、テキスト本体自体に反時計回りに -90 度の回転が適用されている場合です。この場合、結果としてシェイプは回転しているように見えますが、内部のテキストはまったく回転していないかのように見えます。

## 関連項目

* クラス [ITextFrameFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)