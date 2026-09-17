---
title: equals method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/masterslide/equals/
weight: 30
---
## equals(self, slide) {#ibaseslide}
2つのIBaseSlideインスタンスが等しいかどうかを判定します。
            返り値はスライドの構造と静的コンテンツに基づいて計算されます。
            すべてのシェイプ、スタイル、テキスト、アニメーション、その他の設定等が等しい場合、2つのスライドは等しいとみなされます。比較では、SlideId のような一意の識別子や、日付プレースホルダーの現在の日付値などの動的コンテンツは考慮されません。

### 戻り値

**true**  指定されたIBaseSlideが現在のIBaseSlideと等しい場合; 
            それ以外の場合は **false** .


```python
def equals(self, slide):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide) | 現在のIBaseSlideと比較するためのIBaseSlideです。 |


### 参照
* クラス [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)
* クラス [`MasterSlide`](/slides/python-net/ja/aspose.slides/masterslide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)