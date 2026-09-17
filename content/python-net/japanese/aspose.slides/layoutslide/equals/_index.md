---
title: equals method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/layoutslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
2つの IBaseSlide インスタンスが等しいかどうかを判定します。  
戻り値はスライドの構造と静的コンテンツに基づいて計算されます。  
すべてのシェイプ、スタイル、テキスト、アニメーションおよびその他の設定などが等しい場合、2つのスライドは等しいとみなされます。比較は SlideId などの一意識別子や、日付プレースホルダーの現在の日付値などの動的コンテンツは考慮しません。

### 戻り値

**true** は、指定された IBaseSlide が現在の IBaseSlide と等しい場合です。そうでない場合は **false** です。

```python
def equals(self, slide):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide) | 現在の IBaseSlide と比較するための IBaseSlide。 |

### 参照
* クラス [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)
* クラス [`LayoutSlide`](/slides/python-net/ja/aspose.slides/layoutslide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)