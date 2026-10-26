---
title: translate method
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
Traduit une présentation dans la langue spécifiée à l'aide de l'IA (version synchrone).


```python
def translate(self, presentation, language):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation) | Présentation cible |
| language | **str** | Langue cible |

### Remarques

L'exemple ci-dessous utilise le [`AsposeAIWebClient`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient) par défaut, qui est créé par le constructeur sans paramètre **SlidesAIAgent.#ctor** et se connecte au LLM propre d'Aspose. Pour utiliser un fournisseur d'IA différent, fournissez votre propre LLM, ou personnalisez la connexion (par exemple, en fournissant votre propre `HttpClient`), passez une implémentation [`IAIWebClient`](/slides/python-net/fr/aspose.slides.ai/iaiwebclient) au constructeur **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Les implémentations disponibles incluent :

* [`AsposeAIWebClient`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/fr/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/fr/aspose.slides.ai/openaicompatiblewebclient)

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | L'instance de présentation n'est pas fournie |
| **RuntimeError(Proxy error(ArgumentException))** | La valeur de langue ne peut pas être None ou vide |

### Voir aussi
* classe [`AsposeAIWebClient`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient)
* classe [`IAIWebClient`](/slides/python-net/fr/aspose.slides.ai/iaiwebclient)
* classe [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation)
* classe [`OpenAICompatibleWebClient`](/slides/python-net/fr/aspose.slides.ai/openaicompatiblewebclient)
* classe [`OpenAIWebClient`](/slides/python-net/fr/aspose.slides.ai/openaiwebclient)
* classe [`SlidesAIAgent`](/slides/python-net/fr/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/fr/aspose.slides.ai)
* bibliothèque [`Aspose.Slides`](/slides/python-net)