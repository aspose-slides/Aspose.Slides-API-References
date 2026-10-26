---
title: group method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.mathtext/basescript/group/
weight: 70
---
## group(self) {#}
Posiziona questo elemento in un gruppo usando una graffa inferiore

### Restituisce

Nuova istanza del tipo [`IMathGroupingCharacter`](/slides/python-net/it/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Posiziona questo elemento in un gruppo usando un carattere di raggruppamento, come una graffa inferiore o un altro

### Restituisce

Nuova istanza del tipo [`IMathGroupingCharacter`](/slides/python-net/it/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | Carattere di raggruppamento come GRAFFA INFERIORE (U+23DF) o qualsiasi altro |
| position | [`MathTopBotPositions`](/slides/python-net/it/aspose.slides.mathtext/mathtopbotpositions) | Posizione del carattere di raggruppamento |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/it/aspose.slides.mathtext/mathtopbotpositions) | Justificazione verticale del carattere di raggruppamento.<br/><br/>            Specifica l'allineamento dell'oggetto rispetto alla linea di base.<br/><br/>            Ad esempio, quando il carattere di raggruppamento è sopra l'oggetto, <br/><br/>            VerticalJustification di Top indica che la parte superiore dell'oggetto si trova sulla linea di base;<br/><br/>            quando VerticalJustification è impostato su Bottom, la parte inferiore dell'oggetto è sulla linea di base |



### Vedi anche
* classe [`BaseScript`](/slides/python-net/it/aspose.slides.mathtext/basescript)
* classe [`IMathGroupingCharacter`](/slides/python-net/it/aspose.slides.mathtext/imathgroupingcharacter)
* enumerazione [`MathTopBotPositions`](/slides/python-net/it/aspose.slides.mathtext/mathtopbotpositions)
* modulo [`aspose.slides.mathtext`](/slides/python-net/it/aspose.slides.mathtext)
* libreria [`Aspose.Slides`](/slides/python-net)