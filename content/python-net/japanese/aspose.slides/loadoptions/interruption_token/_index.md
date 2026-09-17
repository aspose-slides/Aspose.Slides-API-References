---
title: interruption_token property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/loadoptions/interruption_token/
weight: 90
---
## interruption_token プロパティ
中断要求を監視するトークンです。
            
            このトークンは [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation) インスタンス全体の存続期間を管理します。ロードやプレゼンテーションの保存などの長時間実行される操作は、[`InterruptionTokenSource`](/slides/python-net/ja/aspose.slides/interruptiontokensource) の [`InterruptionTokenSource.interrupt`](/slides/python-net/ja/aspose.slides/interruptiontokensource/interrupt) メソッドを呼び出すことで中断されます。

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
* クラス [`InterruptionTokenSource`](/slides/python-net/ja/aspose.slides/interruptiontokensource)
* クラス [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)
* クラス [`LoadOptions`](/slides/python-net/ja/aspose.slides/loadoptions)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)