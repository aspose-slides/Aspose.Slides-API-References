---
title: WriteShapeStart()
second_title: Aspose.Slides for C++ API リファレンス
description: シェイプのレンダリング前に呼び出されます。各シェイプにつき一度呼び出されます。この関数がジェネレーターに何かを書き込むと、現在のスライド画像の生成が完了し、追加された HTML フラグメントが挿入され、前の画像の上に新しい画像が開始されます。
type: docs
weight: 66
url: /ja/aspose.slides.export/embedallfontshtmlcontroller/writeshapestart/
---
## EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) メソッド

シェイプのレンダリング前に呼び出されます。各シェイプにつき一度呼び出されます。この関数がジェネレーターに何かを書き込むと、現在のスライド画像生成が完了し、追加した HTML フラグメントが挿入され、前の画像の上に新しい画像が開始されます。

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | 出力オブジェクト。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) はレンダリングされようとしている。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IHtmlGenerator](../../ihtmlgenerator/)
* クラス [IShape](../../../aspose.slides/ishape/)
* クラス [EmbedAllFontsHtmlController](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)