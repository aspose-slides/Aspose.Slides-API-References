---
title: remove method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/layoutslide/remove/
weight: 60
---
## remove(self) {#}
プレゼンテーションから layout を削除します。

```python
def remove(self):
    ...
```

### 備考

PptxEditException のスローを回避するには、事前に layout の HasDependingSlides プロパティを確認してください。

### 例外

| 例外 | 説明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) | layout がすでにプレゼンテーションから削除されている場合、または layout がプレゼンテーションで使用されている場合（その HasDependingSlides プロパティが true のとき）にスローされます。 |

### 関連項目
* クラス [`LayoutSlide`](/slides/python-net/ja/aspose.slides/layoutslide)
* クラス [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)