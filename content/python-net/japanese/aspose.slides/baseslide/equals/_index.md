---
title: equals method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/baseslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
2 つの IBaseSlide インスタンスが等しいかどうかを判定します。  
戻り値はスライドの構造と静的コンテンツに基づいて計算されます。  
すべてのシェイプ、スタイル、テキスト、アニメーション、その他の設定等が等しい場合、2 つのスライドは等しいとみなされます。比較では、SlideId のような固有識別子の値や、日付プレースホルダーの現在の日付値のような動的コンテンツは考慮されません。

### 戻り値

**true**  指定された IBaseSlide が現在の IBaseSlide と等しい場合; それ以外の場合は **false** .


```python
def equals(self, slide):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide) | 現在の IBaseSlide と比較する対象の IBaseSlide。 |

### 参照
* クラス [`BaseSlide`](/slides/python-net/ja/aspose.slides/baseslide)
* クラス [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)