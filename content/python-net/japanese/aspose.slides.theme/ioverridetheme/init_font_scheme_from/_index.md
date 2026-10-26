---
title: init_font_scheme_from method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.theme/ioverridetheme/init_font_scheme_from/
weight: 70
---
## init_font_scheme_from(self, font_scheme) {#ifontscheme}
InheritedTheme の FontScheme を上書きするために、新しいオブジェクトで FontScheme を初期化します。

```python
def init_font_scheme_from(self, font_scheme):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| font_scheme | [`IFontScheme`](/slides/python-net/ja/aspose.slides.theme/ifontscheme) | 初期化に使用するデータ。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | FontScheme がすでに初期化されている場合 (None ではない) にスローされます。 |
| **RuntimeError(Proxy error(ArgumentNullException))** | fontScheme パラメータが None の場合にスローされます。 |

### 参照
* クラス [`IFontScheme`](/slides/python-net/ja/aspose.slides.theme/ifontscheme)
* クラス [`IOverrideTheme`](/slides/python-net/ja/aspose.slides.theme/ioverridetheme)
* モジュール [`aspose.slides.theme`](/slides/python-net/ja/aspose.slides.theme)
* ライブラリ [`Aspose.Slides`](/slides/python-net)