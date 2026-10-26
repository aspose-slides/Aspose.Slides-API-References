---
title: register_ink_effect_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
インクブラシの視覚効果をシミュレートするために使用されるカスタム画像のコレクションに画像を登録します。
            これらの画像は、Galaxy、Rainbowなどの特定の [`InkEffectType`](/slides/python-net/ja/aspose.slides.ink/inkeffecttype) 値でインクをレンダリングする際に使用されます。独自の画像を提供することで、各インク効果の表示方法を制御できます。


```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/ja/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/ja/aspose.slides/iimage) |  |

### 備考

このメソッドは、デフォルトのインク効果テクスチャをユーザー定義のものに置き換えることを可能にし、ライセンスで制限されている、または実行時に利用できないデフォルトのアセットに特に有用です。各登録された値のペアは、[`InkEffectType`](/slides/python-net/ja/aspose.slides.ink/inkeffecttype) 値を対応する [`IImage`](/slides/python-net/ja/aspose.slides/iimage) オブジェクト（例: Bitmap、または Aspose 画像インターフェイス）と関連付ける必要があります。



### 関連項目
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* クラス [`Ink`](/slides/python-net/ja/aspose.slides.ink/ink)
* 列挙型 [`InkEffectType`](/slides/python-net/ja/aspose.slides.ink/inkeffecttype)
* モジュール [`aspose.slides.ink`](/slides/python-net/ja/aspose.slides.ink)
* ライブラリ [`Aspose.Slides`](/slides/python-net)