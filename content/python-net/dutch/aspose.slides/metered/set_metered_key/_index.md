---
title: set_metered_key method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/metered/set_metered_key/
weight: 60
---
## set_metered_key(self, public_key, private_key) {#str-str}
Stelt de gemeten openbare en privésleutel in.
Als u een metered-licentie aanschaft, moet deze API bij het starten van de applicatie worden aangeroepen; normaal gesproken is dit voldoende. 
Echter, als het altijd mislukt om consumptiegegevens te uploaden en 24 uur wordt overschreden, wordt de licentie ingesteld op evaluatiestatus, 
om een dergelijk geval te voorkomen, moet u regelmatig de licentiestatus controleren; als deze evaluatiestatus is, roept u deze API opnieuw aan.


```python
def set_metered_key(self, public_key, private_key):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| public_key | **str** | openbare sleutel |
| private_key | **str** | privésleutel |



### Zie ook
* klasse [`Metered`](/slides/python-net/nl/aspose.slides/metered)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)