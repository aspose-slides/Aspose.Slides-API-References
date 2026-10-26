---
title: translate method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
Übersetzt eine Präsentation in die angegebene Sprache mithilfe von KI (synchroner Version).


```python
def translate(self, presentation, language):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation) | Zielpräsentation |
| language | **str** | Zielsprache |

### Anmerkungen

Das nachstehende Beispiel verwendet das Standard-[`AsposeAIWebClient`](/slides/python-net/de/aspose.slides.ai/asposeaiwebclient), das durch den parameterlosen **SlidesAIAgent.#ctor**-Konstruktor erstellt wird und sich mit Asposes eigenem LLM verbindet. Um einen anderen KI-Anbieter zu nutzen, stellen Sie Ihr eigenes LLM bereit oder passen Sie die Verbindung an (zum Beispiel, indem Sie Ihren eigenen `HttpClient` bereitstellen), übergeben Sie eine [`IAIWebClient`](/slides/python-net/de/aspose.slides.ai/iaiwebclient)-Implementierung an den **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**-Konstruktor. Verfügbare Implementierungen umfassen:
             
* [`AsposeAIWebClient`](/slides/python-net/de/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/de/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/de/aspose.slides.ai/openaicompatiblewebclient)

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Präsentationsinstanz wurde nicht bereitgestellt |
| **RuntimeError(Proxy error(ArgumentException))** | Sprachwert darf nicht None oder leer sein |



### Siehe auch
* Klasse [`AsposeAIWebClient`](/slides/python-net/de/aspose.slides.ai/asposeaiwebclient)
* Klasse [`IAIWebClient`](/slides/python-net/de/aspose.slides.ai/iaiwebclient)
* Klasse [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation)
* Klasse [`OpenAICompatibleWebClient`](/slides/python-net/de/aspose.slides.ai/openaicompatiblewebclient)
* Klasse [`OpenAIWebClient`](/slides/python-net/de/aspose.slides.ai/openaiwebclient)
* Klasse [`SlidesAIAgent`](/slides/python-net/de/aspose.slides.ai/slidesaiagent)
* Modul [`aspose.slides.ai`](/slides/python-net/de/aspose.slides.ai)
* Bibliothek [`Aspose.Slides`](/slides/python-net)