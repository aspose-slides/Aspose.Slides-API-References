---
title: aspose.slides.ai
second_title: Aspose.Slides pour Python via .NET – Référence de l'API
description: 
type: docs
url: /fr/aspose.slides.ai/
---
Contient des classes qui offrent des fonctionnalités basées sur l'IA pour analyser et traiter les présentations PowerPoint.

## Classes

| Classe | Description |
| :- | :- |
| [`AsposeAIWebClient`](/slides/python-net/fr/aspose.slides.ai/asposeaiwebclient/) | Une implémentation [`IAIWebClient`](/slides/python-net/fr/aspose.slides.ai/iaiwebclient) intégrée qui se connecte au LLM propriétaire d'Aspose.<br/>            Ceci est le client par défaut utilisé par le constructeur **SlidesAIAgent.#ctor** sans paramètres. |
| [`IAIConversation`](/slides/python-net/fr/aspose.slides.ai/iaiconversation/) | Représente une instance de conversation. Contrairement aux appels d'IA réguliers, les conversations conservent tout le contexte. |
| [`IAIWebClient`](/slides/python-net/fr/aspose.slides.ai/iaiwebclient/) | Interface client Web d'IA. Cette interface permet de remplacer différents modèles de langage d'IA.<br/>            Les classes qui implémentent cette interface sont censées être utilisées avec `SlidesAIAgent`. |
| [`OpenAICompatibleWebClient`](/slides/python-net/fr/aspose.slides.ai/openaicompatiblewebclient/) | Une implémentation [`IAIWebClient`](/slides/python-net/fr/aspose.slides.ai/iaiwebclient) intégrée qui se connecte à un fournisseur de LLM compatible OpenAI<br/>            à une URL de base spécifiée. |
| [`OpenAIWebClient`](/slides/python-net/fr/aspose.slides.ai/openaiwebclient/) | Une implémentation [`IAIWebClient`](/slides/python-net/fr/aspose.slides.ai/iaiwebclient) intégrée qui se connecte à l'API OpenAI. |
| [`SlidesAIAgent`](/slides/python-net/fr/aspose.slides.ai/slidesaiagent/) | Fournit des fonctionnalités alimentées par l'IA pour le traitement des présentations. |
| [`SlidesAIAgentException`](/slides/python-net/fr/aspose.slides.ai/slidesaiagentexception/) | Représente les exceptions liées à Slides AI Agent. |

## Énumérations

| Énumération | Description |
| :- | :- |
| [`PresentationContentAmountType`](/slides/python-net/fr/aspose.slides.ai/presentationcontentamounttype/) | Spécifie la quantité de contenu inclus dans la présentation générée, influençant à la fois le nombre de diapositives et le niveau de détail par diapositive. |