---
title: set_metered_key method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/metered/set_metered_key/
weight: 60
---
## set_metered_key(self, public_key, private_key) {#str-str}
            Nastavuje měřený veřejný a soukromý klíč.
            Pokud zakoupíte měřenou licenci, při spuštění aplikace by se toto API mělo zavolat, obvykle to stačí. 
            Nicméně pokud se vždy nepodaří nahrát data o spotřebě a překročí se 24 hodin, licence bude nastavena do stavu hodnocení, 
            abyste se takové situaci vyhnuli, měli byste pravidelně kontrolovat stav licence; pokud je ve stavu hodnocení, zavolejte toto API znovu.


```python
def set_metered_key(self, public_key, private_key):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| public_key | **str** | veřejný klíč |
| private_key | **str** | soukromý klíč |



### Viz také
* třída [`Metered`](/slides/python-net/cs/aspose.slides/metered)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)