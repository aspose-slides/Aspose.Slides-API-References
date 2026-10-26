---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides dla Pythona przez .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
Tworzy instancję klienta internetowego Aspose AI, który łączy się z domyślnym punktem końcowym Aspose LLM.
            Ten klient jest używany przez konstruktor **SlidesAIAgent.#ctor** bez parametrów, więc tworzenie
            go ręcznie jest wymagane tylko wtedy, gdy przekazujemy klienta do konstruktora **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**
            bezpośrednio.

```python
def __init__(self):
    ...
```

## __init__(self, url) {#str}
Tworzy instancję klienta internetowego Aspose AI, który łączy się z własnym adresem URL punktu końcowego. Użyj tego
            przeciążenia, gdy posiadasz URL dostarczony przez zespół Aspose.Slides; w przeciwnym razie użyj
            przeciążenia **AsposeAIWebClient.#ctor** z domyślnym URL.

```python
def __init__(self, url):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| url | **str** | URL punktu końcowego Aspose LLM, dostarczony przez zespół Aspose.Slides. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | URL nie może być None ani pusty. |

### Zobacz także
* klasa [`AsposeAIWebClient`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient)
* moduł [`aspose.slides.ai`](/slides/python-net/pl/aspose.slides.ai)
* biblioteka [`Aspose.Slides`](/slides/python-net)