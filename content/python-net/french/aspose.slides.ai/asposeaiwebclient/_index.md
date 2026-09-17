---
title: AsposeAIWebClient class
second_title: Aspose.Slides pour Python via l'API .NET
description: 
type: docs
url: /fr/aspose.slides.ai/asposeaiwebclient/
---
## AsposeAIWebClient classe

Une implémentation [`IAIWebClient`](/slides/python-net/fr/aspose.slides.ai/iaiwebclient) intégrée qui se connecte au LLM propre d'Aspose.
Ceci est le client par défaut utilisé par le constructeur **SlidesAIAgent.#ctor** sans paramètre.

Le type AsposeAIWebClient expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient/__init__/#) | Crée une instance du client web Aspose AI qui se connecte au point de terminaison LLM Aspose par défaut.<br/>            Il s'agit du client utilisé par le constructeur sans paramètre **SlidesAIAgent.#ctor**, donc le créer<br/>            explicitement n'est requis que lors du passage du client au constructeur **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**<br/>            directement. |
| [`__init__(self, url)`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient/__init__/#str) | Crée une instance du client web Aspose AI qui se connecte à une URL de point de terminaison personnalisée. Utilisez cette surcharge lorsque vous avez une URL fournie par l'équipe Aspose.Slides ; sinon, utilisez la surcharge **AsposeAIWebClient.#ctor** avec l'URL par défaut. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`create_conversation(self)`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient/create_conversation/#) | Crée une instance de conversation. Contrairement aux appels AI classiques, les conversations conservent tout le contexte. |


### Voir aussi
* classe [`IAIWebClient`](/slides/python-net/fr/aspose.slides.ai/iaiwebclient)
* module [`aspose.slides.ai`](/slides/python-net/fr/aspose.slides.ai)
* bibliothèque [`Aspose.Slides`](/slides/python-net)