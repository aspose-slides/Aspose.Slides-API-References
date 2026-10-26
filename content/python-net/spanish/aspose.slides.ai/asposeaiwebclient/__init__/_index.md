---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides para Python vía referencia de API .NET
description: 
type: docs
url: /es/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
Crea una instancia del cliente web Aspose AI que se conecta al endpoint predeterminado de Aspose LLM.  
Este es el cliente usado por el constructor sin parámetros **SlidesAIAgent.#ctor**, por lo que crearlo explícitamente solo es necesario al pasar el cliente al constructor **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** directamente.


```python
def __init__(self):
    ...
```



## __init__(self, url) {#str}
Crea una instancia del cliente web Aspose AI que se conecta a una URL de endpoint personalizada. Use esta sobrecarga cuando tenga una URL proporcionada por el equipo de Aspose.Slides; de lo contrario, use la sobrecarga **AsposeAIWebClient.#ctor** con la URL predeterminada.


```python
def __init__(self, url):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| url | **str** | URL del endpoint de Aspose LLM, proporcionada por el equipo de Aspose.Slides. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | La URL no puede ser None o estar vacía. |



### Ver también
* clase [`AsposeAIWebClient`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient)
* módulo [`aspose.slides.ai`](/slides/python-net/es/aspose.slides.ai)
* biblioteca [`Aspose.Slides`](/slides/python-net)