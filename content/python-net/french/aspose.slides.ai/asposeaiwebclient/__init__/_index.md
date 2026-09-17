---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides pour Python via l'API de référence .NET
description: 
type: docs
url: /fr/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
Crée une instance du client web Aspose AI qui se connecte au point de terminaison LLM Aspose par défaut.
            Il s'agit du client utilisé par le constructeur sans paramètres **SlidesAIAgent.#ctor**, donc le créer explicitement n'est requis que lorsqu'on transmet le client au constructeur **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** directement.


```python
def __init__(self):
    ...
```



## __init__(self, url) {#str}
Crée une instance du client web Aspose AI qui se connecte à une URL de point de terminaison personnalisée. Utilisez cette surcharge lorsque vous disposez d'une URL fournie par l'équipe Aspose.Slides ; sinon, utilisez la surcharge **AsposeAIWebClient.#ctor** avec l'URL par défaut.


```python
def __init__(self, url):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| url | **str** | URL du point de terminaison LLM Aspose, fournie par l'équipe Aspose.Slides. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | L'URL ne peut pas être None ou vide. |



### Voir aussi
* classe [`AsposeAIWebClient`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient)
* module [`aspose.slides.ai`](/slides/python-net/fr/aspose.slides.ai)
* bibliothèque [`Aspose.Slides`](/slides/python-net)