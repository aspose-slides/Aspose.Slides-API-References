---
title: equals method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/masternotesslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
2つの IBaseSlide インスタンスが等しいかどうかを判定します。  
戻り値はスライドの構造と静的コンテンツに基づいて計算されます。  
すべてのシェイプ、スタイル、テキスト、アニメーション、その他の設定などが等しい場合、2つのスライドは等しいとみなされます。比較では一意の識別子値（例: SlideId）や動的コンテンツ（例: 日付プレースホルダーの現在の日付値）は考慮されません。

### 戻り値

**true** が指定された IBaseSlide が現在の IBaseSlide と等しい場合;  
それ以外の場合は **false** 。

```python
def equals(self, slide):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide) | 現在の IBaseSlide と比較するための IBaseSlide。 |

### 参照
* クラス [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)
* クラス [`MasterNotesSlide`](/slides/python-net/ja/aspose.slides/masternotesslide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)