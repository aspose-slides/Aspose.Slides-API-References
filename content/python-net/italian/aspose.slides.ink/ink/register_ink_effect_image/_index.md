---
title: register_ink_effect_image method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
Registra un'immagine nella collezione di immagini personalizzate utilizzate per simulare effetti visivi per i pennini a inchiostro.  
Queste immagini vengono utilizzate durante il rendering dell'inchiostro con valori specifici [`InkEffectType`](/slides/python-net/it/aspose.slides.ink/inkeffecttype), come Galaxy, Rainbow, ecc. Fornendo le proprie immagini, è possibile controllare come appare ciascun effetto di inchiostro.


```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/it/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/it/aspose.slides/iimage) |  |

### Osservazioni

Questo metodo consente di sostituire le texture predefinite degli effetti di inchiostro con quelle definite dall'utente, il che è particolarmente utile quando le risorse predefinite sono limitate da licenze o non disponibili a runtime. Ogni coppia di valori registrata deve associare un valore [`InkEffectType`](/slides/python-net/it/aspose.slides.ink/inkeffecttype) a un oggetto [`IImage`](/slides/python-net/it/aspose.slides/iimage) corrispondente (ad es., Bitmap o un'interfaccia immagine Aspose).


### Vedi anche
* classe [`IImage`](/slides/python-net/it/aspose.slides/iimage)
* classe [`Ink`](/slides/python-net/it/aspose.slides.ink/ink)
* enumerazione [`InkEffectType`](/slides/python-net/it/aspose.slides.ink/inkeffecttype)
* modulo [`aspose.slides.ink`](/slides/python-net/it/aspose.slides.ink)
* libreria [`Aspose.Slides`](/slides/python-net)