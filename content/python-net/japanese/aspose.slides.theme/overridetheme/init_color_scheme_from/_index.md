---
title: init_color_scheme_from method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.theme/overridetheme/init_color_scheme_from/
weight: 40
---
## init_color_scheme_from(self, color_scheme) {#icolorscheme}
InheritedTheme の ColorScheme を上書きするために、新しいオブジェクトで ColorScheme を初期化します。


```python
def init_color_scheme_from(self, color_scheme):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| color_scheme | [`IColorScheme`](/slides/python-net/ja/aspose.slides.theme/icolorscheme) | 初期化に使用するデータ。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | ColorScheme が既に初期化されている場合 (None ではない)、例外がスローされます。 |
| **RuntimeError(Proxy error(ArgumentNullException))** | colorScheme パラメーターが None の場合、例外がスローされます。 |



### 参照
* クラス [`IColorScheme`](/slides/python-net/ja/aspose.slides.theme/icolorscheme)
* クラス [`OverrideTheme`](/slides/python-net/ja/aspose.slides.theme/overridetheme)
* モジュール [`aspose.slides.theme`](/slides/python-net/ja/aspose.slides.theme)
* ライブラリ [`Aspose.Slides`](/slides/python-net)