---
title: use_cell property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartcategory/use_cell/
weight: 50
---
## use_cell プロパティ
true の場合は AsCell プロパティが有効です。言い換えると、ワークシートはカテゴリの保存に使用されます（このケースでは多層カテゴリがサポートされます）。
false の場合は AsLiteral プロパティが有効です。言い換えると、ワークシートはカテゴリの保存に使用されません（このケースでは多層カテゴリはサポートされません）。
読み取り専用 **bool**。

### 備考
このプロパティの値を変更するには（コレクション内のすべてのカテゴリに対して）ChartCategoryCollection.UseCells プロパティに新しい値を設定します。

### 定義:
```python
@property
def use_cell(self):
    ...
```

### 参照
* クラス [`ChartCategory`](/slides/python-net/ja/aspose.slides.charts/chartcategory)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)