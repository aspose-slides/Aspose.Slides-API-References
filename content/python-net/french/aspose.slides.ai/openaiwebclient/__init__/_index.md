---
title: OpenAIWebClient constructor
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
Crée une instance du client Web OpenAI.

```python
def __init__(self, model, api_key, organization_id):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| model | **str** | Modèle de langage OpenAI. Valeurs possibles:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | Clé d'API OpenAI. |
| organization_id | **str** | ID d'organisation (facultatif). |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | La valeur de la clé API ne peut pas être None ou vide. |
| **RuntimeError(Proxy error(ArgumentException))** | La valeur du modèle texte ne peut pas être None ou vide. |

### Voir aussi
* classe [`OpenAIWebClient`](/slides/python-net/fr/aspose.slides.ai/openaiwebclient)
* module [`aspose.slides.ai`](/slides/python-net/fr/aspose.slides.ai)
* bibliothèque [`Aspose.Slides`](/slides/python-net)