---
title: enclose method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---
## enclose(self) {#}
Obalí matematický prvek do závorek

### Návratová hodnota

Matematický prvek typu [`IMathDelimiter`](/slides/python-net/cs/aspose.slides.mathtext/imathdelimiter), který zahrnuje závorky



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Obalí matematický prvek ve specifikovaných znacích, například závorkami nebo jinými znaky jako rámec

### Návratová hodnota

Pokud jsou `beginning_character` a `ending_character` nastaveny na None, příslušné vlastnosti jsou pouze přiřazeny a není vytvořen žádný nový objekt (vrací tuto instanci). Jinak se vrátí nový matematický prvek typu Delimiter, který zahrnuje specifikované znaky jako rámec a tato instance [`MathDelimiter`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter) je uvnitř obalena.



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| beginning_character | **char** | Počáteční znak (obvykle levá závorka) |
| ending_character | **char** | Koncový znak (obvykle pravá závorka) |



### Viz také
* třída [`IMathDelimiter`](/slides/python-net/cs/aspose.slides.mathtext/imathdelimiter)
* třída [`MathDelimiter`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)