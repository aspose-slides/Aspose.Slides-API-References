---
title: SlidesAIAgent constructor
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
Inicializuje novou instanci [`SlidesAIAgent`](/slides/python-net/cs/aspose.slides.ai/slidesaiagent) pomocí vestavěného
            [`AsposeAIWebClient`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient) s výchozí konfigurací. Klient se připojuje k
            vlastnímu LLM společnosti Aspose a nevyžaduje žádnou další konfiguraci.
            Chcete-li použít jiného AI klienta, použijte **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** přetížení místo toho.


```python
def __init__(self):
    ...
```



## __init__(self, ai_client) {#iaiwebclient}
Inicializuje novou instanci [`SlidesAIAgent`](/slides/python-net/cs/aspose.slides.ai/slidesaiagent) s vlastním AI klientem.
            Použijte toto přetížení k určení poskytovatele AI, zadání vlastního LLM nebo přizpůsobení
            spojení (například poskytnutím vlastního `HttpClient`).
            Lze použít libovolnou implementaci [`IAIWebClient`](/slides/python-net/cs/aspose.slides.ai/iaiwebclient), včetně:
            
* [`AsposeAIWebClient`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/cs/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/cs/aspose.slides.ai/openaicompatiblewebclient)


            Chcete-li použít vestavěný [`AsposeAIWebClient`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient) s výchozí konfigurací,
            použijte přetížení **SlidesAIAgent.#ctor** místo toho.


```python
def __init__(self, ai_client):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/cs/aspose.slides.ai/iaiwebclient) | Instance AI klienta. Lze použít libovolnou implementaci [`IAIWebClient`](/slides/python-net/cs/aspose.slides.ai/iaiwebclient). |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Instance AI klienta není poskytnuta. |



### Viz také
* třída [`AsposeAIWebClient`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient)
* třída [`IAIWebClient`](/slides/python-net/cs/aspose.slides.ai/iaiwebclient)
* třída [`OpenAICompatibleWebClient`](/slides/python-net/cs/aspose.slides.ai/openaicompatiblewebclient)
* třída [`OpenAIWebClient`](/slides/python-net/cs/aspose.slides.ai/openaiwebclient)
* třída [`SlidesAIAgent`](/slides/python-net/cs/aspose.slides.ai/slidesaiagent)
* modul [`aspose.slides.ai`](/slides/python-net/cs/aspose.slides.ai)
* knihovna [`Aspose.Slides`](/slides/python-net)