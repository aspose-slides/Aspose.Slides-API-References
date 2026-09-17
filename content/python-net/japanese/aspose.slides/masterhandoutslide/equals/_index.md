---
title: equals method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/masterhandoutslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
2つの IBaseSlide インスタンスが等しいかどうかを判定します。
            返却値はスライドの構造と静的コンテンツに基づいて計算されます。
            すべてのシェイプ、スタイル、テキスト、アニメーションおよびその他の設定等が等しい場合、2つのスライドは等しいとみなされます。比較では SlideId などの一意識別子や、日付プレースホルダーの現在の日付値などの動的コンテンツは考慮されません。

### 戻り値

**true**  指定された IBaseSlide が現在の IBaseSlide と等しい場合は **true**、それ以外の場合は **false** です。



```python
def equals(self, slide):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide) | 現在の IBaseSlide と比較する対象の IBaseSlide です。 |



### 参照
* クラス [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)
* クラス [`MasterHandoutSlide`](/slides/python-net/ja/aspose.slides/masterhandoutslide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)