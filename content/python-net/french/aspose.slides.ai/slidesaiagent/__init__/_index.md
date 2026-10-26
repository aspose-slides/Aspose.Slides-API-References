---
title: SlidesAIAgent constructor
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
Crée une nouvelle instance de [`SlidesAIAgent`](/slides/python-net/fr/aspose.slides.ai/slidesaiagent) en utilisant le [`AsposeAIWebClient`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient) intégré avec sa configuration par défaut. Le client se connecte au LLM d'Aspose et ne nécessite aucune configuration supplémentaire. Pour utiliser un autre client IA, utilisez la surcharge **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**.

```python
def __init__(self):
    ...
```



## __init__(self, ai_client) {#iaiwebclient}
Crée une nouvelle instance de [`SlidesAIAgent`](/slides/python-net/fr/aspose.slides.ai/slidesaiagent) avec un client IA personnalisé. Utilisez cette surcharge pour spécifier le fournisseur IA, fournir votre propre LLM ou personnaliser la connexion (par exemple, en fournissant votre propre `HttpClient`). Toute implémentation de [`IAIWebClient`](/slides/python-net/fr/aspose.slides.ai/iaiwebclient) peut être utilisée, y compris :

* [`AsposeAIWebClient`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/fr/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/fr/aspose.slides.ai/openaicompatiblewebclient)

Pour utiliser le [`AsposeAIWebClient`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient) intégré avec sa configuration par défaut, utilisez la surcharge **SlidesAIAgent.#ctor**.

```python
def __init__(self, ai_client):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/fr/aspose.slides.ai/iaiwebclient) | instance du client IA. Toute implémentation de [`IAIWebClient`](/slides/python-net/fr/aspose.slides.ai/iaiwebclient) peut être utilisée. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | L'instance du client IA n'est pas fournie. |



### Voir aussi
* classe [`AsposeAIWebClient`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient)
* classe [`IAIWebClient`](/slides/python-net/fr/aspose.slides.ai/iaiwebclient)
* classe [`OpenAICompatibleWebClient`](/slides/python-net/fr/aspose.slides.ai/openaicompatiblewebclient)
* classe [`OpenAIWebClient`](/slides/python-net/fr/aspose.slides.ai/openaiwebclient)
* classe [`SlidesAIAgent`](/slides/python-net/fr/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/fr/aspose.slides.ai)
* bibliothèque [`Aspose.Slides`](/slides/python-net)