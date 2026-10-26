---
title: interruption_token property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## interruption_token プロパティ
中断要求を監視するトークンです。

このトークンは、[`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation) インスタンス全体のライフタイムを管理します。プレゼンテーションのロードや保存などの長時間実行される操作は、[`IInterruptionTokenSource`](/slides/python-net/ja/aspose.slides/iinterruptiontokensource) の [`IInterruptionTokenSource.interrupt`](/slides/python-net/ja/aspose.slides/iinterruptiontokensource/interrupt) メソッドを呼び出すことで中断されます。

### 定義:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```

### 参照
* クラス [`IInterruptionTokenSource`](/slides/python-net/ja/aspose.slides/iinterruptiontokensource)
* クラス [`ILoadOptions`](/slides/python-net/ja/aspose.slides/iloadoptions)
* クラス [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)