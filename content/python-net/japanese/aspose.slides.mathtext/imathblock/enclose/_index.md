---
title: enclose method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/imathblock/enclose/
weight: 90
---
## enclose(self) {#}



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| beginning_character | **char** |  |
| ending_character | **char** |  |


## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
このブロックの子要素を、括弧などの指定された文字で囲み、区切り文字で区切ります

### 戻り値

[`IMathDelimiter`](/slides/python-net/ja/aspose.slides.mathtext/imathdelimiter)型の数式要素で、指定された文字がフレームと区切りとして含まれます



```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| beginning_character | **char** | 開始文字（通常は左括弧） |
| ending_character | **char** | 終了文字（通常は右括弧） |
| separator_character | **char** | 区切り文字 |



### 参照
* class [`IMathBlock`](/slides/python-net/ja/aspose.slides.mathtext/imathblock)
* class [`IMathDelimiter`](/slides/python-net/ja/aspose.slides.mathtext/imathdelimiter)
* module [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)