---
title: enclose method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---
## enclose(self) {#}
Omvat een wiskundig element in haakjes

### Retourwaarde

Het wiskundige element van het type [`IMathDelimiter`](/slides/python-net/nl/aspose.slides.mathtext/imathdelimiter) dat de haakjes bevat



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Omvat een wiskundig element in opgegeven tekens, zoals haakjes of andere tekens als kader

### Retourwaarde

Als `beginning_character` en `ending_character` None zijn, 
            krijgen de overeenkomstige eigenschappen alleen waarden toegewezen en wordt er geen nieuw object gemaakt (returnt deze instantie).
            Anders returnt een nieuw wiskundig element van het type Delimiter dat de opgegeven tekens als kader bevat 
            en deze instantie van [`MathDelimiter`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter) binnen het kader.



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| beginning_character | **char** | Beginteken (meestal linker haakje) |
| ending_character | **char** | Eindteken (meestal rechter haakje) |



### Zie ook
* klasse [`IMathDelimiter`](/slides/python-net/nl/aspose.slides.mathtext/imathdelimiter)
* klasse [`MathDelimiter`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* bibliotheek [`Aspose.Slides`](/slides/python-net)