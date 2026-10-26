---
title: enclose method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathaccent/enclose/
weight: 50
---
## enclose(self) {#}
数式要素を括弧で囲みます

### 戻り値
括弧を含む [`IMathDelimiter`](/slides/python-net/ja/aspose.slides.mathtext/imathdelimiter) 型の数式要素

```python
def enclose(self):
    ...
```

## enclose(self, beginning_character, ending_character) {#char-char}
数式要素を括弧やその他の文字でフレームとして囲みます

### 戻り値
指定された文字でフレームされた [`IMathDelimiter`](/slides/python-net/ja/aspose.slides.mathtext/imathdelimiter) 型の数式要素

```python
def enclose(self, beginning_character, ending_character):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| beginning_character | **char** | 開始文字（通常は左括弧） |
| ending_character | **char** | 終了文字（通常は右括弧） |

### 参照
* class [`IMathDelimiter`](/slides/python-net/ja/aspose.slides.mathtext/imathdelimiter)
* class [`MathAccent`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent)
* module [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)