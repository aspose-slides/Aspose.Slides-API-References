---
title: register_ink_effect_image method
second_title: Aspose.Slides pro Python – referenční příručka .NET API
description: 
type: docs
url: /cs/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
Zaregistruje obrázek do kolekce vlastních obrázků používaných k simulaci vizuálních efektů pro inkové štětce.
            Tyto obrázky se používají při vykreslování ink s konkrétními hodnotami [`InkEffectType`](/slides/python-net/cs/aspose.slides.ink/inkeffecttype),
            například Galaxy, Rainbow atd. Poskytnutím vlastních obrázků můžete ovlivnit, jak se každý ink efekt zobrazí.


```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/cs/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/cs/aspose.slides/iimage) |  |

### Poznámky

Tato metoda umožňuje nahradit výchozí textury ink efektů uživatelem definovanými,
            což je zvláště užitečné, když jsou výchozí zdroje omezeny licencí nebo nejsou v době běhu k dispozici.
            Každý registrovaný pár hodnot musí spojovat hodnotu [`InkEffectType`](/slides/python-net/cs/aspose.slides.ink/inkeffecttype) s odpovídajícím
            objektem [`IImage`](/slides/python-net/cs/aspose.slides/iimage) (např. Bitmap nebo rozhraní Aspose image).


### Viz také
* třída [`IImage`](/slides/python-net/cs/aspose.slides/iimage)
* třída [`Ink`](/slides/python-net/cs/aspose.slides.ink/ink)
* výčtový typ [`InkEffectType`](/slides/python-net/cs/aspose.slides.ink/inkeffecttype)
* modul [`aspose.slides.ink`](/slides/python-net/cs/aspose.slides.ink)
* knihovna [`Aspose.Slides`](/slides/python-net)