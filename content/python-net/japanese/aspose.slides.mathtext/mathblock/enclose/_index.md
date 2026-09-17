---
title: enclose method
second_title: Aspose.Slides の Python 用 .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathblock/enclose/
weight: 100
---
## enclose(self) {#}
数式要素を丸括弧で囲みます

### 戻り値

[`IMathDelimiter`](/slides/python-net/ja/aspose.slides.mathtext/imathdelimiter) 型の数式要素で、丸括弧が含まれます



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
このブロックの子要素を、丸括弧やその他の文字でフレームとして囲みます

### 戻り値

[`IMathDelimiter`](/slides/python-net/ja/aspose.slides.mathtext/imathdelimiter) 型の数式要素で、指定された文字がフレームとして含まれます



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| beginning_character | **char** | 開始文字（通常は左括弧） |
| ending_character | **char** | 終了文字（通常は右括弧） |


## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
このブロックの子要素を、丸括弧やその他の文字でフレームとして囲み、区切り文字で区切ります

### 戻り値

[`IMathDelimiter`](/slides/python-net/ja/aspose.slides.mathtext/imathdelimiter) 型の数式要素で、指定された文字がフレームとして含まれ、区切り文字で区切られます



```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| beginning_character | **char** | 開始文字（通常は左括弧） |
| ending_character | **char** | 終了文字（通常は右括弧） |
| separator_character | **char** | 区切り文字 |



### 参照
* クラス [`IMathDelimiter`](/slides/python-net/ja/aspose.slides.mathtext/imathdelimiter)
* クラス [`MathBlock`](/slides/python-net/ja/aspose.slides.mathtext/mathblock)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)