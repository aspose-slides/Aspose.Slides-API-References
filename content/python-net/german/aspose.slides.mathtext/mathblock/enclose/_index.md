---
title: enclose method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/mathblock/enclose/
weight: 100
---
## enclose(self) {#}
Schließt ein mathematisches Element in Klammern ein

### Returns
The math element of type [`IMathDelimiter`](/slides/python-net/de/aspose.slides.mathtext/imathdelimiter) which includes the parenthesis



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Schließt Kinderelemente dieses Blocks in angegebenen Zeichen, wie Klammern oder anderen Zeichen, als Rahmen ein

### Returns
The math element of type [`IMathDelimiter`](/slides/python-net/de/aspose.slides.mathtext/imathdelimiter) which includes specified characters as framing



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| beginning_character | **char** | Anfangszeichen (normalerweise linke Klammer) |
| ending_character | **char** | Endzeichen (normalerweise rechte Klammer) |


## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
Schließt Kinderelemente dieses Blocks in angegebenen Zeichen, wie Klammern oder anderen Zeichen, als Rahmen ein und grenzt sie mit einem Trennzeichen ab

### Returns
The math element of type [`IMathDelimiter`](/slides/python-net/de/aspose.slides.mathtext/imathdelimiter) which includes specified characters as framing and delimiter



```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| beginning_character | **char** | Anfangszeichen (normalerweise linke Klammer) |
| ending_character | **char** | Endzeichen (normalerweise rechte Klammer) |
| separator_character | **char** | Trennzeichen |



### Siehe auch
* Klasse [`IMathDelimiter`](/slides/python-net/de/aspose.slides.mathtext/imathdelimiter)
* Klasse [`MathBlock`](/slides/python-net/de/aspose.slides.mathtext/mathblock)
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)