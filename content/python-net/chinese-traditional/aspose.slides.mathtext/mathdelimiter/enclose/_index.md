---
title: enclose method
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---
## enclose(self) {#}
將數學元素用括號括起

### 回傳值

類型為 [`IMathDelimiter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathdelimiter) 的數學元素，包含括號



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
將數學元素以指定字元（例如括號或其他字元）作為框架包住

### 回傳值

如果 `beginning_character` 和 `ending_character` 為 None， 
            只會為相應屬性指派值，且不會建立新物件（回傳此實例）。
            否則，回傳類型為 Delimiter 的新數學元素，包含指定字元作為框架，且此 [`MathDelimiter`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter) 實例被框在其中。



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| beginning_character | **char** | 起始字元（通常為左括號） |
| ending_character | **char** | 結束字元（通常為右括號） |



### 另請參閱
* 類別 [`IMathDelimiter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathdelimiter)
* 類別 [`MathDelimiter`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)