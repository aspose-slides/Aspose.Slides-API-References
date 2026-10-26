---
title: set_RotationAngle()
second_title: Aspose.Slides for C++ API リファレンス
description: バウンディング ボックス内のテキストに適用されるカスタム回転を指定します。指定されていない場合は、付随するシェイプの回転が使用されます。指定されている場合、この回転はシェイプとは独立して適用されます。つまり、シェイプに回転が適用されるのに加えて、テキスト自体にも回転が適用されることがあります。このプロパティとプロパティ TextVerticalType の事前定義された垂直タイプから要約された視覚的テキスト回転の結果値です。float を書き込みます。
type: docs
weight: 352
url: /ja/aspose.slides/itextframeformat/set_rotationangle/
---
## ITextFrameFormat::set_RotationAngle(float) メソッド

バウンディング ボックス内のテキストに適用されるカスタム回転を指定します。指定されていない場合は、付随するシェイプの回転が使用されます。指定されている場合、この回転はシェイプとは独立して適用されます。つまり、シェイプに回転が適用されている上で、テキスト自体にも回転が適用されることがあります。このプロパティとプロパティ TextVerticalType の事前定義された垂直タイプから要約された視覚的テキスト回転の結果値です。**float** を書き込みます。

```cpp
virtual void Aspose::Slides::ITextFrameFormat::set_RotationAngle(float value)=0
```

## 備考

シェイプに 90 度の時計回りの回転が適用されているケースを考えてみます。さらに、テキスト本体自体に -90 度の反時計回りの回転が適用されている場合です。この場合、結果としてシェイプは回転しているように見えますが、内部のテキストはまるで回転していないかのように表示されます。

## 参照

* クラス [ITextFrameFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)