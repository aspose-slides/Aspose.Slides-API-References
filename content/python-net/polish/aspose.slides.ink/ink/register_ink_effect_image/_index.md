---
title: register_ink_effect_image method
second_title: Aspose.Slides dla Pythona – referencja API .NET
description: 
type: docs
url: /pl/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
Rejestruje obraz w kolekcji własnych obrazów używanych do symulacji efektów wizualnych dla pędzli atramentu.
            Te obrazy są używane podczas renderowania atramentu z określonymi wartościami [`InkEffectType`](/slides/python-net/pl/aspose.slides.ink/inkeffecttype),
            takimi jak Galaxy, Rainbow itp. Dostarczając własne obrazy, możesz kontrolować, jak każdy efekt atramentu się pojawia.


```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/pl/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/pl/aspose.slides/iimage) |  |

### Uwagi

Ta metoda pozwala zastąpić domyślne tekstury efektów atramentu własnymi,
            co jest szczególnie przydatne, gdy domyślne zasoby są ograniczone licencją lub niedostępne w czasie działania.
            Każda zarejestrowana para wartości musi powiązać wartość [`InkEffectType`](/slides/python-net/pl/aspose.slides.ink/inkeffecttype) z odpowiadającym obiektem [`IImage`](/slides/python-net/pl/aspose.slides/iimage)
            (np. Bitmap, lub interfejsem obrazu Aspose).



### Zobacz także
* klasa [`IImage`](/slides/python-net/pl/aspose.slides/iimage)
* klasa [`Ink`](/slides/python-net/pl/aspose.slides.ink/ink)
* enumeracja [`InkEffectType`](/slides/python-net/pl/aspose.slides.ink/inkeffecttype)
* moduł [`aspose.slides.ink`](/slides/python-net/pl/aspose.slides.ink)
* biblioteka [`Aspose.Slides`](/slides/python-net)