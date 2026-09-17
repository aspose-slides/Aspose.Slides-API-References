---
title: SlidesAIAgent class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent classe

Fournit des fonctionnalités alimentées par l'IA pour le traitement des présentations.

Le type SlidesAIAgent expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/fr/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | Initialise une nouvelle instance de [`SlidesAIAgent`](/slides/python-net/fr/aspose.slides.ai/slidesaiagent) avec un client IA personnalisé.<br/>Utilisez cette surcharge pour spécifier le fournisseur d'IA, fournir votre propre LLM, ou personnaliser la connexion (par exemple, en fournissant votre propre `HttpClient`).<br/>Toute implémentation de [`IAIWebClient`](/slides/python-net/fr/aspose.slides.ai/iaiwebclient) peut être utilisée, y compris :<br/><br/>* [`AsposeAIWebClient`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/fr/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/fr/aspose.slides.ai/openaicompatiblewebclient)<br/><br/>Pour utiliser le [`AsposeAIWebClient`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient) intégré avec sa configuration par défaut, utilisez la surcharge **SlidesAIAgent.#ctor** à la place. |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.ai/slidesaiagent/__init__/#) | Initialise une nouvelle instance de [`SlidesAIAgent`](/slides/python-net/fr/aspose.slides.ai/slidesaiagent) en utilisant le [`AsposeAIWebClient`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient) intégré avec sa configuration par défaut.<br/>Le client se connecte au propre LLM d'Aspose et ne nécessite aucune configuration supplémentaire.<br/>Pour utiliser un client IA différent, utilisez la surcharge **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** à la place. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/fr/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | Génère une instance de présentation à partir d'une description textuelle. Fournissez un sujet, des idées, des citations ou des extraits de texte dans la langue requise. |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/fr/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | Génère une instance de présentation à partir d'une description textuelle. Fournissez un sujet, des idées, des citations ou des extraits de texte dans la langue requise. |
| [`translate(self, presentation, language)`](/slides/python-net/fr/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | Traduit une présentation vers la langue spécifiée en utilisant l'IA (version synchrone). |

### Voir aussi
* classe [`AsposeAIWebClient`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient)
* classe [`IAIWebClient`](/slides/python-net/fr/aspose.slides.ai/iaiwebclient)
* classe [`OpenAICompatibleWebClient`](/slides/python-net/fr/aspose.slides.ai/openaicompatiblewebclient)
* classe [`OpenAIWebClient`](/slides/python-net/fr/aspose.slides.ai/openaiwebclient)
* classe [`SlidesAIAgent`](/slides/python-net/fr/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/fr/aspose.slides.ai)
* bibliothèque [`Aspose.Slides`](/slides/python-net)