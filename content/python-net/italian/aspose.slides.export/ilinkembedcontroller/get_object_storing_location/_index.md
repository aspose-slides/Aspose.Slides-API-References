---
title: get_object_storing_location method
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
Determina dove l'oggetto dovrebbe essere memorizzato.
Questo metodo viene chiamato una volta per ogni ID dell'oggetto.
Non è garantito che non possano esistere due oggetti con gli stessi dati, semanticName e contentType ma con ID diversi.

### Restituisce
Decisione

```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| id | **int** | ID dell'oggetto. Questo ID è unico a livello dell'operazione di salvataggio. |
| entity_data | **bytes** | Dati binari dell'oggetto. Questo parametro può essere None, se i dati binari dell'oggetto non sono ancora generati. |
| semantic_name | **str** | Testo breve che descrive il significato dell'oggetto. Il controller può usare questo come parte del nome esterno dell'oggetto, ma spetta al dispatcher garantire che i nomi siano unici e contengano solo caratteri consentiti. |
| content_type | **str** | Tipo MIME dell'oggetto. |
| recomended_extension | **str** | Estensione del nome file, consigliata per questo tipo MIME. |

### Vedi anche
* classe [`ILinkEmbedController`](/slides/python-net/it/aspose.slides.export/ilinkembedcontroller)
* enumerazione [`LinkEmbedDecision`](/slides/python-net/it/aspose.slides.export/linkembeddecision)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)