---
title: group method
second_title: Referencja API Aspose.Slides dla Pythona via .NET
description: 
type: docs
url: /pl/aspose.slides.mathtext/mathborderbox/group/
weight: 80
---
## group(self) {#}
Umieszcza ten element w grupie przy użyciu dolnego nawiasu klamrowego

### Zwraca

Nowa instancja typu [`IMathGroupingCharacter`](/slides/python-net/pl/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Umieszcza ten element w grupie przy użyciu znaku grupowania, takiego jak dolny nawias klamrowy lub inny

### Zwraca

Nowa instancja typu [`IMathGroupingCharacter`](/slides/python-net/pl/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| character | **char** | Znak grupowania, taki jak DOLNY NAWIAS KLAMROWY (U+23DF) lub dowolny inny |
| position | [`MathTopBotPositions`](/slides/python-net/pl/aspose.slides.mathtext/mathtopbotpositions) | Pozycja znaku grupowania |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/pl/aspose.slides.mathtext/mathtopbotpositions) | Justowanie pionowe znaku grupy.<br/><br/>            Określa wyrównanie obiektu względem linii bazowej.<br/><br/>            Na przykład, gdy znak grupy znajduje się nad obiektem, <br/><br/>            VerticalJustification ustawione na Top oznacza, że górna krawędź obiektu znajduje się na linii bazowej;<br/><br/>            gdy VerticalJustification jest ustawione na Bottom, dolna krawędź obiektu znajduje się na linii bazowej |



### Zobacz także
* klasa [`IMathGroupingCharacter`](/slides/python-net/pl/aspose.slides.mathtext/imathgroupingcharacter)
* klasa [`MathBorderBox`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox)
* enumeracja [`MathTopBotPositions`](/slides/python-net/pl/aspose.slides.mathtext/mathtopbotpositions)
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)