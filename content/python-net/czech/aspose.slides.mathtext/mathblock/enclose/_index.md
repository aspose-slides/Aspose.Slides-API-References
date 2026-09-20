---
title: enclose method
second_title: Aspose.Slides pro Python přes .NET API
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathblock/enclose/
weight: 100
---
## enclose(self) {#}
Uzavře matematický prvek do závorek

### Returns

Matematický prvek typu [`IMathDelimiter`](/slides/python-net/cs/aspose.slides.mathtext/imathdelimiter), který zahrnuje závorky



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Obaluje podřízené prvky tohoto bloku ve specifikovaných znacích, například závorkách nebo jiných znacích jako rámování

### Returns

Matematický prvek typu [`IMathDelimiter`](/slides/python-net/cs/aspose.slides.mathtext/imathdelimiter), který zahrnuje specifikované znaky jako rámování



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| beginning_character | **char** | Začáteční znak (obvykle levá závorka) |
| ending_character | **char** | Koncový znak (obvykle pravá závorka) |


## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
Obaluje podřízené prvky tohoto bloku ve specifikovaných znacích, například závorkách nebo jiných, jako rámování a odděluje je znakem oddělovače

### Returns

Matematický prvek typu [`IMathDelimiter`](/slides/python-net/cs/aspose.slides.mathtext/imathdelimiter), který zahrnuje specifikované znaky jako rámování a oddělovač



```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| beginning_character | **char** | Začáteční znak (obvykle levá závorka) |
| ending_character | **char** | Koncový znak (obvykle pravá závorka) |
| separator_character | **char** | Oddělovač |



### See Also
* třída [`IMathDelimiter`](/slides/python-net/cs/aspose.slides.mathtext/imathdelimiter)
* třída [`MathBlock`](/slides/python-net/cs/aspose.slides.mathtext/mathblock)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)