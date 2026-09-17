---
title: generate_presentation method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
Erzeugt eine Präsentationsinstanz aus einer Textbeschreibung. Geben Sie ein Thema, Ideen, Zitate oder Textausschnitte in der gewünschten Sprache an.

```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| description | **str** | Das Thema, Ideen, Zitate oder Textausschnitte. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/de/aspose.slides.ai/presentationcontentamounttype) | Die Menge an Inhalt in der resultierenden Präsentation. |

### Bemerkungen

Das nachstehende Beispiel verwendet das Standard [`AsposeAIWebClient`](/slides/python-net/de/aspose.slides.ai/asposeaiwebclient), das durch den parameterlosen **SlidesAIAgent.#ctor**-Konstruktor erstellt wird und eine Verbindung zu Asposes eigenem LLM herstellt. Um einen anderen KI-Anbieter zu verwenden, geben Sie Ihr eigenes LLM an oder passen Sie die Verbindung an (zum Beispiel, indem Sie Ihren eigenen `HttpClient` bereitstellen), übergeben Sie eine [`IAIWebClient`](/slides/python-net/de/aspose.slides.ai/iaiwebclient)-Implementierung an den **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**-Konstruktor. Verfügbare Implementierungen sind:
* [`AsposeAIWebClient`](/slides/python-net/de/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/de/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/de/aspose.slides.ai/openaicompatiblewebclient)

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | AI-Chat-Anweisung darf nicht None oder leer sein. |


## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
Erzeugt eine Präsentationsinstanz aus einer Textbeschreibung. Geben Sie ein Thema, Ideen, Zitate oder Textausschnitte in der gewünschten Sprache an.

```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| description | **str** | Das Thema, Ideen, Zitate oder Textausschnitte. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/de/aspose.slides.ai/presentationcontentamounttype) | Die Menge an Inhalt in der resultierenden Präsentation. |
| presentation_template | [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation) | Eine Präsentation, die als Vorlage für Layout und Design verwendet wird und die Standardvorlage ersetzt. |

### Bemerkungen

Das nachstehende Beispiel verwendet das Standard [`AsposeAIWebClient`](/slides/python-net/de/aspose.slides.ai/asposeaiwebclient), das durch den parameterlosen **SlidesAIAgent.#ctor**-Konstruktor erstellt wird und eine Verbindung zu Asposes eigenem LLM herstellt. Um einen anderen KI-Anbieter zu verwenden, geben Sie Ihr eigenes LLM an oder passen Sie die Verbindung an (zum Beispiel, indem Sie Ihren eigenen `HttpClient` bereitstellen), übergeben Sie eine [`IAIWebClient`](/slides/python-net/de/aspose.slides.ai/iaiwebclient)-Implementierung an den **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**-Konstruktor. Verfügbare Implementierungen sind:
* [`AsposeAIWebClient`](/slides/python-net/de/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/de/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/de/aspose.slides.ai/openaicompatiblewebclient)

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Präsentationsvorlage wurde nicht bereitgestellt. |
| **RuntimeError(Proxy error(ArgumentException))** | AI-Chat-Anweisung darf nicht None oder leer sein. |



### Siehe auch
* Klasse [`AsposeAIWebClient`](/slides/python-net/de/aspose.slides.ai/asposeaiwebclient)
* Klasse [`IAIWebClient`](/slides/python-net/de/aspose.slides.ai/iaiwebclient)
* Klasse [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation)
* Klasse [`OpenAICompatibleWebClient`](/slides/python-net/de/aspose.slides.ai/openaicompatiblewebclient)
* Klasse [`OpenAIWebClient`](/slides/python-net/de/aspose.slides.ai/openaiwebclient)
* Aufzählung [`PresentationContentAmountType`](/slides/python-net/de/aspose.slides.ai/presentationcontentamounttype)
* Klasse [`SlidesAIAgent`](/slides/python-net/de/aspose.slides.ai/slidesaiagent)
* Modul [`aspose.slides.ai`](/slides/python-net/de/aspose.slides.ai)
* Bibliothek [`Aspose.Slides`](/slides/python-net)