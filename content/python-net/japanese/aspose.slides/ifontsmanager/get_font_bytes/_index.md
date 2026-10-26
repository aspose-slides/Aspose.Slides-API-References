---
title: get_font_bytes method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ifontsmanager/get_font_bytes/
weight: 30
---
## get_font_bytes(self, font_data, font_style) {#ifontdata-fontstyletype}
指定されたフォントスタイルとフォントデータのフォントデータを表すバイト配列を取得します。

### 戻り値
指定されたフォントスタイルのフォントデータを含むバイト配列。フォントデータまたはスタイルが見つからない場合は None を返します。

```python
def get_font_bytes(self, font_data, font_style):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| font_data | [`IFontData`](/slides/python-net/ja/aspose.slides/ifontdata) | フォント [`IFontData`](/slides/python-net/ja/aspose.slides/ifontdata) に関する情報を含むフォントデータオブジェクト。 |
| font_style | [`FontStyleType`](/slides/python-net/ja/aspose.slides/fontstyletype) | データを取得するフォントのスタイル [`FontStyleType`](/slides/python-net/ja/aspose.slides/fontstyletype)。 |

### 参照
* enumeration [`FontStyleType`](/slides/python-net/ja/aspose.slides/fontstyletype)
* class [`IFontData`](/slides/python-net/ja/aspose.slides/ifontdata)
* class [`IFontsManager`](/slides/python-net/ja/aspose.slides/ifontsmanager)
* module [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)