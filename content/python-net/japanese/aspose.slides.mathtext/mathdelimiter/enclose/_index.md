---
title: enclose method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---
## enclose(self) {#}
数式要素を丸括弧で囲みます

### 戻り値

丸括弧を含む[`IMathDelimiter`](/slides/python-net/ja/aspose.slides.mathtext/imathdelimiter)型の数式要素



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
数式要素を丸括弧やその他の文字で枠付けする指定文字で囲みます

### 戻り値

If `beginning_character` と `ending_character` が None,
            対応するプロパティに値が割り当てられるだけで新しいオブジェクトは作成されません（このインスタンスを返します）。
            それ以外の場合、指定された文字で枠付けされた Delimiter 型の新しい数式要素を返し、[`MathDelimiter`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter) のこのインスタンスが内部で枠付けされます。



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| beginning_character | **char** | 開始文字（通常は左括弧） |
| ending_character | **char** | 終了文字（通常は右括弧） |



### 参照
* クラス [`IMathDelimiter`](/slides/python-net/ja/aspose.slides.mathtext/imathdelimiter)
* クラス [`MathDelimiter`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)