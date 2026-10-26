---
title: WriteShapeEnd()
second_title: Aspose.Slides for C++ API リファレンス
description: シェイプの描画前に呼び出されます。シェイプごとに一度呼び出されます。この関数がジェネレーターに何かを書き込むと、現在のスライド画像の生成が完了し、HTMLフラグメントが挿入され、前の画像の上に新しい画像が開始されます。
type: docs
weight: 66
url: /ja/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---
## IHtmlFormattingController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) メソッド

シェイプの描画前に呼び出されます。シェイプごとに1回呼び出されます。この関数がジェネレーターに何かを書き込むと、現在のスライド画像の生成が終了し、HTMLフラグメントが挿入され、前の画像の上に新しい画像が開始されます。

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### 引数

| Parameter | Type | 説明 |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | 出力オブジェクト。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) が最後にレンダリングされます。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IHtmlGenerator](../../ihtmlgenerator/)
* クラス [IShape](../../../aspose.slides/ishape/)
* クラス [IHtmlFormattingController](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)