---
title: init_format_scheme_from method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.theme/ioverridetheme/init_format_scheme_from/
weight: 100
---
## init_format_scheme_from(self, format_scheme) {#iformatscheme}
InheritedTheme の FormatScheme を上書きするために、新しいオブジェクトで FormatScheme を初期化します。


```python
def init_format_scheme_from(self, format_scheme):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| format_scheme | [`IFormatScheme`](/slides/python-net/ja/aspose.slides.theme/iformatscheme) | 初期化元データ。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | FormatScheme がすでに初期化されている場合にスローされます（None ではありません）。 |
| **RuntimeError(Proxy error(ArgumentNullException))** | formatScheme パラメータが None の場合にスローされます。 |



### 参照
* クラス [`IFormatScheme`](/slides/python-net/ja/aspose.slides.theme/iformatscheme)
* クラス [`IOverrideTheme`](/slides/python-net/ja/aspose.slides.theme/ioverridetheme)
* モジュール [`aspose.slides.theme`](/slides/python-net/ja/aspose.slides.theme)
* ライブラリ [`Aspose.Slides`](/slides/python-net)