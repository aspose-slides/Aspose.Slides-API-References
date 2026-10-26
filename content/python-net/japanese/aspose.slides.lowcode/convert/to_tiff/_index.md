---
title: to_tiff method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
入力プレゼンテーションを TIFF 形式の画像セットに変換します。  
            出力ファイル名が "myPath/myFilename.tiff" の場合、結果は "myPath/myFilename_N.tiff" ファイルのセットとして保存されます。N はスライド番号です。


```python
@staticmethod
def to_tiff(pres, output_file_name):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ja/aspose.slides/presentation) | 入力プレゼンテーション。 |
| output_file_name | **str** | 出力ファイル名。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
入力プレゼンテーションをカスタムオプションで TIFF 形式に変換します。  
            出力ファイル名が "myPath/myFilename.tiff" で `multipage` が `false` の場合、結果は "myPath/myFilename_N.tiff" ファイルのセットとして保存されます。N はスライド番号です。  
            それ以外の場合、`multipage` が `true` のとき、結果はマルチページの "myPath/myFilename.tiff" ドキュメントとなります。


```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ja/aspose.slides/presentation) | 入力プレゼンテーション。 |
| output_file_name | **str** | 出力ファイル名。 |
| options | [`ITiffOptions`](/slides/python-net/ja/aspose.slides.export/itiffoptions) | TIFF 保存オプション。 |
| multipage | **bool** | 生成された TIFF ドキュメントがマルチページであるかどうかを指定します。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### 関連項目
* クラス [`Convert`](/slides/python-net/ja/aspose.slides.lowcode/convert)
* クラス [`ITiffOptions`](/slides/python-net/ja/aspose.slides.export/itiffoptions)
* クラス [`Presentation`](/slides/python-net/ja/aspose.slides/presentation)
* モジュール [`aspose.slides.lowcode`](/slides/python-net/ja/aspose.slides.lowcode)
* ライブラリ [`Aspose.Slides`](/slides/python-net)