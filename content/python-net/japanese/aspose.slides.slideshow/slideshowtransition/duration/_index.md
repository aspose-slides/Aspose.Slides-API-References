---
title: duration property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.slideshow/slideshowtransition/duration/
weight: 40
---
## duration プロパティ
スライド遷移効果の duration をミリ秒単位で取得または設定します。
            読み取り/書き込み **int**。

### 備考

PresentationML スキーマの `p:transition` 要素の `p14:dur` 属性に対応します。
設定されていない場合、duration は [`SlideShowTransition.speed`](/slides/python-net/ja/aspose.slides.slideshow/slideshowtransition/speed) プロパティと遷移タイプに基づいて自動的に決定されます。

### 定義:
```python
@property
def duration(self):
    ...

@duration.setter
def duration(self, value):
    ...
```

### 参照
* クラス [`SlideShowTransition`](/slides/python-net/ja/aspose.slides.slideshow/slideshowtransition)
* モジュール [`aspose.slides.slideshow`](/slides/python-net/ja/aspose.slides.slideshow)
* ライブラリ [`Aspose.Slides`](/slides/python-net)