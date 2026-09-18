---
title: group method
second_title: Aspose.Slides dla Pythona – odniesienie API .NET
description: 
type: docs
url: /pl/aspose.slides.mathtext/mathfraction/group/
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
Umieszcza ten element w grupie przy użyciu znaku grupującego, takiego jak dolny nawias klamrowy lub inny

### Zwraca

Nowa instancja typu [`IMathGroupingCharacter`](/slides/python-net/pl/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Typ | Opis |
| :- | :- | :- |
| character | **char** | Znak grupujący, taki jak BOTTOM CURLY BRACKET (U+23DF) lub dowolny inny |
| position | [`MathTopBotPositions`](/slides/python-net/pl/aspose.slides.mathtext/mathtopbotpositions) | Pozycja znaku grupującego |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/pl/aspose.slides.mathtext/mathtopbotpositions) | Justowanie pionowe znaku grupującego.<br/><br/>            Określa wyrównanie obiektu względem linii bazowej.<br/><br/>            Na przykład, gdy znak grupujący znajduje się nad obiektem, <br/><br/>            VerticalJustification of Top oznacza, że górna część obiektu znajduje się na linii bazowej;<br/><br/>            gdy VerticalJustification jest ustawione na Bottom, dolna część obiektu znajduje się na linii bazowej |



### Zobacz także
* klasa [`IMathGroupingCharacter`](/slides/python-net/pl/aspose.slides.mathtext/imathgroupingcharacter)
* klasa [`MathFraction`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction)
* enumeracja [`MathTopBotPositions`](/slides/python-net/pl/aspose.slides.mathtext/mathtopbotpositions)
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)