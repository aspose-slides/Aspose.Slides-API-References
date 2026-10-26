---
title: set_metered_key method
second_title: Aspose.Slides dla Pythona poprzez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides/metered/set_metered_key/
weight: 60
---
## set_metered_key(self, public_key, private_key) {#str-str}
Ustawia klucz publiczny i prywatny dla licencji zliczanej.  
Jeśli zakupisz licencję zliczającą, przy uruchamianiu aplikacji to API powinno zostać wywołane; zazwyczaj to wystarczy.  
Jednakże, jeśli ciągle nie udaje się przesłać danych zużycia i przekroczą 24 godziny, licencja zostanie ustawiona w statusie ewaluacyjnym,  
Aby uniknąć takiej sytuacji, powinieneś regularnie sprawdzać status licencji; jeśli znajduje się w stanie ewaluacyjnym, ponownie wywołaj to API.


```python
def set_metered_key(self, public_key, private_key):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| public_key | **str** | klucz publiczny |
| private_key | **str** | klucz prywatny |



### Zobacz także
* klasa [`Metered`](/slides/python-net/pl/aspose.slides/metered)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)