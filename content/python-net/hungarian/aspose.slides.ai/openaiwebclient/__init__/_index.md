---
title: OpenAIWebClient constructor
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozásán keresztül
description: 
type: docs
url: /hu/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
Létrehoz egy példányt az OpenAI webkliensből.


```python
def __init__(self, model, api_key, organization_id):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| model | **str** | OpenAI nyelvi modell. Lehetséges értékek:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | OpenAI API kulcs. |
| organization_id | **str** | Szervezet azonosító (nem kötelező). |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Az API-kulcs értéke nem lehet None vagy üres. |
| **RuntimeError(Proxy error(ArgumentException))** | A szöveges modell értéke nem lehet None vagy üres. |



### Lásd még
* osztály [`OpenAIWebClient`](/slides/python-net/hu/aspose.slides.ai/openaiwebclient)
* modul [`aspose.slides.ai`](/slides/python-net/hu/aspose.slides.ai)
* könyvtár [`Aspose.Slides`](/slides/python-net)