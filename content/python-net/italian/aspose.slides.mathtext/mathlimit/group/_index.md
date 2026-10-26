---
title: group method
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.mathtext/mathlimit/group/
weight: 80
---
## group(self) {#}
Posiziona questo elemento in un gruppo usando una parentesi graffa chiusa verso il basso

### Restituisce

Nuova istanza del tipo [`IMathGroupingCharacter`](/slides/python-net/it/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Posiziona questo elemento in un gruppo usando un carattere di raggruppamento come parentesi graffa chiusa verso il basso o un altro

### Restituisce

Nuova istanza del tipo [`IMathGroupingCharacter`](/slides/python-net/it/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Tipo | Descrizione |
| :- | :- | :- |
| character | **char** | Carattere di raggruppamento come BOTTOM CURLY BRACKET (U+23DF) o qualsiasi altro |
| position | [`MathTopBotPositions`](/slides/python-net/it/aspose.slides.mathtext/mathtopbotpositions) | Posizione del carattere di raggruppamento |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/it/aspose.slides.mathtext/mathtopbotpositions) | Giustificazione verticale del carattere di gruppo.<br/><br/>            Specifica l'allineamento dell'oggetto rispetto alla linea di base.<br/><br/>            Ad esempio, quando il carattere di gruppo è sopra l'oggetto, <br/><br/>            VerticalJustification of Top indica che la parte alta dell'oggetto cade sulla linea di base;<br/><br/>            quando VerticalJustification è impostata a Bottom, la parte bassa dell'oggetto è sulla linea di base |



### Vedi anche
* classe [`IMathGroupingCharacter`](/slides/python-net/it/aspose.slides.mathtext/imathgroupingcharacter)
* classe [`MathLimit`](/slides/python-net/it/aspose.slides.mathtext/mathlimit)
* enumerazione [`MathTopBotPositions`](/slides/python-net/it/aspose.slides.mathtext/mathtopbotpositions)
* modulo [`aspose.slides.mathtext`](/slides/python-net/it/aspose.slides.mathtext)
* libreria [`Aspose.Slides`](/slides/python-net)