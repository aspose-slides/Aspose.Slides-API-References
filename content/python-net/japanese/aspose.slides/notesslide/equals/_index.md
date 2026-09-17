---
title: equals method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/notesslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
2つのIBaseSlideインスタンスが等しいかどうかを判断します。
返り値はスライドの構造と静的コンテンツに基づいて計算されます。
すべてのシェイプ、スタイル、テキスト、アニメーションおよびその他の設定等が等しい場合、2つのスライドは等しいとみなされます。比較は一意の識別子（例: SlideId）や動的コンテンツ（例: 日付プレースホルダーの現在の日付値）を考慮しません。

### 戻り値
**true** は、指定されたIBaseSlideが現在のIBaseSlideと等しい場合に返されます。そうでない場合は、**false** が返されます。

```python
def equals(self, slide):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide) | 現在のIBaseSlideと比較するIBaseSlide。 |

### 参照
* クラス [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)
* クラス [`NotesSlide`](/slides/python-net/ja/aspose.slides/notesslide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)