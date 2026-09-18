---
title: group method
second_title: Aspose.Slides dla Pythona poprzez .NET API Referencja
description: 
type: docs
url: /pl/aspose.slides.mathtext/mathnaryoperator/group/
weight: 80
---
## group(self) {#}
Umieszcza ten element w grupie przy użyciu dolnego nawiasu klamrowego

### Returns

Nowa instancja typu [`IMathGroupingCharacter`](/slides/python-net/pl/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Umieszcza ten element w grupie przy użyciu znaku grupującego, takiego jak dolny nawias klamrowy lub inny

### Returns

Nowa instancja typu [`IMathGroupingCharacter`](/slides/python-net/pl/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| character | **char** | Znak grupujący taki jak BOTTOM CURLY BRACKET (U+23DF) lub inny |
| position | [`MathTopBotPositions`](/slides/python-net/pl/aspose.slides.mathtext/mathtopbotpositions) | Pozycja znaku grupującego |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/pl/aspose.slides.mathtext/mathtopbotpositions) | Justowanie pionowe znaku grupującego.<br/><br/>            Określa wyrównanie obiektu względem linii bazowej.<br/><br/>            Na przykład, gdy znak grupujący znajduje się nad obiektem, <br/><br/>            VerticalJustification wartości Top oznacza, że górna krawędź obiektu znajduje się na linii bazowej;<br/><br/>            gdy VerticalJustification jest ustawione na Bottom, dolna krawędź obiektu znajduje się na linii bazowej |

### See Also
* klasa [`IMathGroupingCharacter`](/slides/python-net/pl/aspose.slides.mathtext/imathgroupingcharacter)
* klasa [`MathNaryOperator`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator)
* wyliczenie [`MathTopBotPositions`](/slides/python-net/pl/aspose.slides.mathtext/mathtopbotpositions)
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)