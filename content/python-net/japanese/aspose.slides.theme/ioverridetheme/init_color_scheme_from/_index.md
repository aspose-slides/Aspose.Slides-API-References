---
title: init_color_scheme_from method
second_title: Aspose.Slides の Python 用 (.NET) API リファレンス
description: 
type: docs
url: /ja/aspose.slides.theme/ioverridetheme/init_color_scheme_from/
weight: 40
---
## init_color_scheme_from(self, color_scheme) {#icolorscheme}
新しいオブジェクトで ColorScheme を初期化し、InheritedTheme の ColorScheme を上書きします。

```python
def init_color_scheme_from(self, color_scheme):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| color_scheme | [`IColorScheme`](/slides/python-net/ja/aspose.slides.theme/icolorscheme) | 初期化に使用するデータ。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | ColorScheme がすでに初期化されている場合 (None ではない) にスローされます。 |
| **RuntimeError(Proxy error(ArgumentNullException))** | colorScheme パラメータが None の場合にスローされます。 |



### 参照
* クラス [`IColorScheme`](/slides/python-net/ja/aspose.slides.theme/icolorscheme)
* クラス [`IOverrideTheme`](/slides/python-net/ja/aspose.slides.theme/ioverridetheme)
* モジュール [`aspose.slides.theme`](/slides/python-net/ja/aspose.slides.theme)
* ライブラリ [`Aspose.Slides`](/slides/python-net)