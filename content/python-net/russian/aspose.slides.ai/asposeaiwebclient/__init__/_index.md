---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
Создает экземпляр веб-клиента Aspose AI, который подключается к конечной точке Aspose LLM по умолчанию.
            Этот клиент используется конструктором без параметров **SlidesAIAgent.#ctor**, поэтому создавать
            его явно необходимо только при передаче клиента непосредственно в конструктор **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**.

```python
def __init__(self):
    ...
```



## __init__(self, url) {#str}
Создает экземпляр веб-клиента Aspose AI, который подключается к пользовательскому URL-адресу конечной точки. Используйте эту
            перегрузку, когда у вас есть URL, предоставленный командой Aspose.Slides; в противном случае используйте
            перегрузку **AsposeAIWebClient.#ctor** с URL-адресом по умолчанию.

```python
def __init__(self, url):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| url | **str** | URL-адрес конечной точки Aspose LLM, предоставленный командой Aspose.Slides. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | URL не может быть None или пустым. |



### Смотрите также
* класс [`AsposeAIWebClient`](/slides/python-net/ru/aspose.slides.ai/asposeaiwebclient)
* модуль [`aspose.slides.ai`](/slides/python-net/ru/aspose.slides.ai)
* библиотека [`Aspose.Slides`](/slides/python-net)