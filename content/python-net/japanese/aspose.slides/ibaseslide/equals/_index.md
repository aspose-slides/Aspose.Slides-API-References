---
title: equals method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ibaseslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
2つのIBaseSlideインスタンスが等しいかどうかを判定します。
            返却値はスライドの構造と静的コンテンツに基づいて計算されます。
            すべてのシェイプ、スタイル、テキスト、アニメーションおよびその他の設定などが等しい場合、スライドは等しいとみなされます。比較はSlideIdなどの固有識別子や、日付プレースホルダーの現在の日付値などの動的コンテンツは考慮しません。

### 戻り値

**true**  指定されたIBaseSlideが現在のIBaseSlideと等しい場合;
            それ以外の場合は、**false** .



```python
def equals(self, slide):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide) | 現在のIBaseSlideと比較するIBaseSlideです。 |



### 参照
* クラス [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)