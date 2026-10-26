---
title: name property
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/color/name/
weight: 190
---
## name proprietà
Restituisce il nome di questo colore.<br/>            Per un colore con nome (una costante con nome come `Color.red`, o un colore creato con [`from_name`](/slides/python-net/it/aspose.slides/color/from_name/)) viene restituito il nome .NET, ad es. `"Red"` o `"LightBlue"`.<br/>            Per qualsiasi altro colore viene restituito il valore ARGB come esadecimale minuscolo senza riempimento di zeri, ad es. `"ffff0000"`. `Color.empty.name` è `"0"`.
            Solo lettura **str**.

### Definizione:
```python
@property
def name(self):
    ...
```

### Vedi anche
* classe [`Color`](/slides/python-net/it/aspose.slides/color)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)