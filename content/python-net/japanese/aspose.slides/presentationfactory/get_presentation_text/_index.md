---
title: get_presentation_text method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/presentationfactory/get_presentation_text/
weight: 40
---
## get_presentation_text(self, file, mode) {#str-textextractionarrangingmode}
スライドから生のテキストを取得します

### 戻り値

スライドの生テキストを表す SlideText 配列を含む PresentationText のインスタンス



```python
def get_presentation_text(self, file, mode):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file | **str** | 入力ファイル |
| mode | [`TextExtractionArrangingMode`](/slides/python-net/ja/aspose.slides/textextractionarrangingmode) | 抽出モード |


## get_presentation_text(self, stream, mode) {#iorawiobase-textextractionarrangingmode}
スライドから生のテキストを取得します

### 戻り値

スライドの生テキストを表す SlideText 配列を含む PresentationText のインスタンス



```python
def get_presentation_text(self, stream, mode):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 入力ストリーム |
| mode | [`TextExtractionArrangingMode`](/slides/python-net/ja/aspose.slides/textextractionarrangingmode) | 抽出モード |


## get_presentation_text(self, stream, mode, options) {#iorawiobase-textextractionarrangingmode-iloadoptions}
スライドから生のテキストを取得します

### 戻り値

スライドの生テキストを表す SlideText 配列を含む PresentationText のインスタンス



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
* クラス [`IPresentationText`](/slides/python-net/ja/aspose.slides/ipresentationtext)
* クラス [`PresentationFactory`](/slides/python-net/ja/aspose.slides/presentationfactory)
* 列挙型 [`TextExtractionArrangingMode`](/slides/python-net/ja/aspose.slides/textextractionarrangingmode)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)