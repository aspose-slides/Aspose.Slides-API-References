---
title: generate_presentation method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
Génère une instance de présentation à partir d'une description textuelle. Fournissez un sujet, des idées, des citations ou des extraits de texte dans la langue requise.


```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| description | **str** | Le sujet, les idées, les citations ou les extraits de texte. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/fr/aspose.slides.ai/presentationcontentamounttype) | La quantité de contenu dans la présentation résultante. |

### Remarques

L'exemple ci-dessous utilise le [`AsposeAIWebClient`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient) par défaut, qui est créé par le constructeur sans paramètres **SlidesAIAgent.#ctor** et se connecte au LLM propre d'Aspose. Pour utiliser un fournisseur d'IA différent, fournissez votre propre LLM, ou personnalisez la connexion (par exemple, en fournissant votre propre `HttpClient`), transmettez une implémentation [`IAIWebClient`](/slides/python-net/fr/aspose.slides.ai/iaiwebclient) au constructeur **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Les implémentations disponibles incluent :

* [`AsposeAIWebClient`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/fr/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/fr/aspose.slides.ai/openaicompatiblewebclient)

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | L'instruction de chat IA ne peut pas être None ou vide. |


## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
Génère une instance de présentation à partir d'une description textuelle. Fournissez un sujet, des idées, des citations ou des extraits de texte dans la langue requise.


```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| description | **str** | Le sujet, les idées, les citations ou les extraits de texte. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/fr/aspose.slides.ai/presentationcontentamounttype) | La quantité de contenu dans la présentation résultante. |
| presentation_template | [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation) | Une présentation à utiliser comme modèle pour la mise en page et le design, remplaçant le modèle par défaut. |

### Remarques

L'exemple ci-dessous utilise le [`AsposeAIWebClient`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient) par défaut, qui est créé par le constructeur sans paramètres **SlidesAIAgent.#ctor** et se connecte au LLM propre d'Aspose. Pour utiliser un fournisseur d'IA différent, fournissez votre propre LLM, ou personnalisez la connexion (par exemple, en fournissant votre propre `HttpClient`), transmettez une implémentation [`IAIWebClient`](/slides/python-net/fr/aspose.slides.ai/iaiwebclient) au constructeur **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Les implémentations disponibles incluent :

* [`AsposeAIWebClient`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/fr/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/fr/aspose.slides.ai/openaicompatiblewebclient)

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Le modèle de présentation n'est pas fourni. |
| **RuntimeError(Proxy error(ArgumentException))** | L'instruction de chat IA ne peut pas être None ou vide. |



### Voir aussi
* classe [`AsposeAIWebClient`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient)
* classe [`IAIWebClient`](/slides/python-net/fr/aspose.slides.ai/iaiwebclient)
* classe [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation)
* classe [`OpenAICompatibleWebClient`](/slides/python-net/fr/aspose.slides.ai/openaicompatiblewebclient)
* classe [`OpenAIWebClient`](/slides/python-net/fr/aspose.slides.ai/openaiwebclient)
* énumération [`PresentationContentAmountType`](/slides/python-net/fr/aspose.slides.ai/presentationcontentamounttype)
* classe [`SlidesAIAgent`](/slides/python-net/fr/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/fr/aspose.slides.ai)
* bibliothèque [`Aspose.Slides`](/slides/python-net)