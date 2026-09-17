---
title: get_presentation_text method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ipresentationfactory/get_presentation_text/
weight: 30
---
## get_presentation_text(self, file, mode) {#str-textextractionarrangingmode}
スライドから生テキストを取得します

### 戻り値

生スライドテキストを表す SlideText 配列を含む PresentationText のインスタンス



```python
def get_presentation_text(self, file, mode):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file | **str** | 入力ファイル |
| mode | [`TextExtractionArrangingMode`](/slides/python-net/ja/aspose.slides/textextractionarrangingmode) | 抽出モード |


## get_presentation_text(self, stream, mode) {#iorawiobase-textextractionarrangingmode}
スライドから生テキストを取得します

### 戻り値

生スライドテキストを表す SlideText 配列を含む PresentationText のインスタンス



```python
def get_presentation_text(self, stream, mode):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 入力ストリーム |
| mode | [`TextExtractionArrangingMode`](/slides/python-net/ja/aspose.slides/textextractionarrangingmode) | 抽出モード |


## get_presentation_text(self, stream, mode, options) {#iorawiobase-textextractionarrangingmode-iloadoptions}
スライドから生テキストを取得します

### 戻り値

生スライドテキストを表す SlideText 配列を含む PresentationText のインスタンス



```python
def get_presentation_text(self, stream, mode, options):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 入力ストリーム |
| mode | [`TextExtractionArrangingMode`](/slides/python-net/ja/aspose.slides/textextractionarrangingmode) | 抽出モード |
| options | [`ILoadOptions`](/slides/python-net/ja/aspose.slides/iloadoptions) | ロードオプション |



### 参照
* クラス [`ILoadOptions`](/slides/python-net/ja/aspose.slides/iloadoptions)
* クラス [`IPresentationFactory`](/slides/python-net/ja/aspose.slides/ipresentationfactory)
* クラス [`IPresentationText`](/slides/python-net/ja/aspose.slides/ipresentationtext)
* 列挙 [`TextExtractionArrangingMode`](/slides/python-net/ja/aspose.slides/textextractionarrangingmode)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)