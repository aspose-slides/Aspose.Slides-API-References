---
title: WriteShapeEnd()
second_title: Aspose.Slides for C++ API リファレンス
description: shape のレンダリング前に呼び出されます。shape ごとに一度呼び出されます。この関数が generator に何かを書き込むと、現在のスライド画像の生成が終了し、追加された HTML フラグメントが挿入され、前の画像の上に新しい画像が開始されます。
type: docs
weight: 79
url: /ja/aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---
## EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) メソッド

shape のレンダリング前に呼び出されます。shape ごとに一度呼び出されます。この関数が generator に何かを書き込むと、現在のスライド画像の生成が終了し、追加された html フラグメントが挿入され、前の画像の上に新しい画像が開始されます。

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | 出力オブジェクト。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) が最後にレンダリングされる。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IHtmlGenerator](../../ihtmlgenerator/)
* クラス [IShape](../../../aspose.slides/ishape/)
* クラス [EmbedAllFontsHtmlController](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)