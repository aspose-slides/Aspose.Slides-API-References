---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/masterslidecollection/remove_at/
weight: 40
---
## remove_at(self, index) {#int}
コレクションの指定されたインデックスにある要素を削除します。

```python
def remove_at(self, index):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 削除する要素のゼロベースインデックスです。 |

### 備考

PptxEditException のスローを回避するには、事前にマスターの HasDependingSlides プロパティを確認してください。

### 例外

| 例外 | 説明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) | 削除対象のマスターがプレゼンテーションで使用されている場合にスローされます（HasDependingSlides プロパティが true の場合）。 |

### 関連項目
* class [`MasterSlideCollection`](/slides/python-net/ja/aspose.slides/masterslidecollection)
* class [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)