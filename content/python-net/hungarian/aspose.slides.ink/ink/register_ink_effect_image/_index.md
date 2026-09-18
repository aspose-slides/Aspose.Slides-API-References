---
title: register_ink_effect_image method
second_title: Aspose.Slides Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
Regisztrál egy képet a saját képek gyűjteményébe, amelyet a tinta ecsetek vizuális hatásainak szimulálásához használnak.
            Ezeket a képeket a tinta renderelésekor használják a specifikus [`InkEffectType`](/slides/python-net/hu/aspose.slides.ink/inkeffecttype) értékekkel,
            például Galaxy, Rainbow stb. Saját képekkel szabályozhatja, hogy egyes tintahatások hogyan jelennek meg.


```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/hu/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/hu/aspose.slides/iimage) |  |

### Megjegyzések

Ez a metódus lehetővé teszi az alapértelmezett tintahatás-textúrák felhasználó által definiáltakra cseréjét,
            ami különösen hasznos, ha az alapértelmezett eszközöket licencelés korlátozza vagy futásidőben nem érhetők el.
            Minden regisztrált értékpárnak egy [`InkEffectType`](/slides/python-net/hu/aspose.slides.ink/inkeffecttype) értéket kell hozzárendelnie egy megfelelő
            [`IImage`](/slides/python-net/hu/aspose.slides/iimage) objektumhoz (például Bitmap vagy egy Aspose kép interfész).


### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* osztály [`Ink`](/slides/python-net/hu/aspose.slides.ink/ink)
* enumeráció [`InkEffectType`](/slides/python-net/hu/aspose.slides.ink/inkeffecttype)
* modul [`aspose.slides.ink`](/slides/python-net/hu/aspose.slides.ink)
* könyvtár [`Aspose.Slides`](/slides/python-net)