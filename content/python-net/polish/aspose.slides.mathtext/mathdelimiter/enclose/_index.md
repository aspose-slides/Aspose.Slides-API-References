---
title: enclose method
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---
## enclose(self) {#}
Otacza element matematyczny nawiasami

### Zwraca

Element matematyczny typu [`IMathDelimiter`](/slides/python-net/pl/aspose.slides.mathtext/imathdelimiter) zawierający nawiasy



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Otacza element matematyczny w określonych znakach, takich jak nawiasy lub inne znaki jako ramkę

### Zwraca

Jeśli `beginning_character` i `ending_character` są None,
odpowiednie właściwości są przypisywane tylko wartościom i nie tworzony jest nowy obiekt (zwraca tę instancję).
W przeciwnym razie, zwraca nowy element matematyczny typu Delimiter, który zawiera określone znaki jako ramkę i tę instancję [`MathDelimiter`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter) otoczoną w środku.



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| beginning_character | **char** | Początkowy znak (zazwyczaj lewy nawias) |
| ending_character | **char** | Końcowy znak (zazwyczaj prawy nawias) |



### Zobacz także
* klasa [`IMathDelimiter`](/slides/python-net/pl/aspose.slides.mathtext/imathdelimiter)
* klasa [`MathDelimiter`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter)
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)