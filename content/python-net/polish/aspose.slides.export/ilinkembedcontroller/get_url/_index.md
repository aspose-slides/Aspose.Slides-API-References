---
title: get_url method
second_title: Aspose.Slides dla Pythona – referencja API .NET
description: 
type: docs
url: /pl/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
Zwraca URL do obiektu zewnętrznego.
            Ta metoda jest zawsze wywoływana, jeśli **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** zwróciło [`LinkEmbedDecision.LINK`](/slides/python-net/pl/aspose.slides.export/linkembeddecision/LINK) i może być wywołana, jeśli **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** zwróciło [`LinkEmbedDecision.EMBED`](/slides/python-net/pl/aspose.slides.export/linkembeddecision/EMBED), ale osadzanie jest niemożliwe.
            Może być wywołana wielokrotnie dla tego samego identyfikatora obiektu.

### Zwraca

Url obiektu zewnętrznego lub None, jeśli ten obiekt powinien być zignorowany.



```python
def get_url(self, id, referrer):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| id | **int** | Identyfikator obiektu. Ten identyfikator jest unikalny w całej operacji zapisu. |
| referrer | **int** | Identyfikator odwołującego się obiektu lub 0, jeśli obiekt jest odwoływany przez dokument główny. Może być użyty do generowania względnego odnośnika. |



### Zobacz także
* klasa [`ILinkEmbedController`](/slides/python-net/pl/aspose.slides.export/ilinkembedcontroller)
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)