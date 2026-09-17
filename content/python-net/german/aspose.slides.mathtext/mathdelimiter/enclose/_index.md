---
title: enclose method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---
## enclose(self) {#}
Schließt ein mathematisches Element in Klammern ein

### Rückgabe

Das mathematische Element vom Typ [`IMathDelimiter`](/slides/python-net/de/aspose.slides.mathtext/imathdelimiter) das die Klammern enthält



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Schließt ein mathematisches Element in angegebenen Zeichen, wie Klammern oder anderen Zeichen, als Rahmen ein

### Rückgabe

Wenn `beginning_character` und `ending_character` None sind, werden die entsprechenden Eigenschaften nur zugewiesen und es wird kein neues Objekt erstellt (gibt diese Instanz zurück). Andernfalls wird ein neues mathematisches Element vom Typ Delimiter zurückgegeben, das die angegebenen Zeichen als Rahmen enthält und diese Instanz von [`MathDelimiter`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter) darin eingerahmt ist.



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| beginning_character | **char** | Anfangszeichen (in der Regel linke Klammer) |
| ending_character | **char** | Endzeichen (in der Regel rechte Klammer) |



### Siehe auch
* Klasse [`IMathDelimiter`](/slides/python-net/de/aspose.slides.mathtext/imathdelimiter)
* Klasse [`MathDelimiter`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter)
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)