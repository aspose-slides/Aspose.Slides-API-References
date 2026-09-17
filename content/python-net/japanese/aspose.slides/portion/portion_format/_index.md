---
title: portion_format property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/portion/portion_format/
weight: 90
---
## portion_format プロパティ
Returns oformatting bject which contains explicitly set formatting properties of the text portion with no inheritance applied.
            読み取り専用 [`IPortionFormat`](/slides/python-net/ja/aspose.slides/iportionformat).

### 備考

The formatting object contains the formatting parameters defined for the current portion only, inherited data is not applied.

In order to get the effective values including inherited ones use the [`PortionFormat.get_effective`](/slides/python-net/ja/aspose.slides/portionformat/get_effective) method.

### 定義:
```python
@property
def portion_format(self):
    ...
```

### 参照
* クラス [`IPortionFormat`](/slides/python-net/ja/aspose.slides/iportionformat)
* クラス [`Portion`](/slides/python-net/ja/aspose.slides/portion)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)