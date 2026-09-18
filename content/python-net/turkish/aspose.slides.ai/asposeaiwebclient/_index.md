---
title: AsposeAIWebClient class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.ai/asposeaiwebclient/
---
## AsposeAIWebClient sınıfı

Aspose'ın kendi LLM'sine bağlanan yerleşik [`IAIWebClient`](/slides/python-net/tr/aspose.slides.ai/iaiwebclient) uygulaması.  
Bu, parametresiz **SlidesAIAgent.#ctor** yapıcısı tarafından kullanılan varsayılan istemcidir.

AsposeAIWebClient türü aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self)`](/slides/python-net/tr/aspose.slides.ai/asposeaiwebclient/__init__/#) | Aspose AI web istemcisinin, varsayılan Aspose LLM uç noktasına bağlanan bir örneğini oluşturur.<br/>            Bu, parametresiz **SlidesAIAgent.#ctor** yapıcısı tarafından kullanılan istemcidir; bu nedenle istemciyi **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** yapıcısına doğrudan geçirmek istendiğinde açıkça oluşturulması gerekir. |
| [`__init__(self, url)`](/slides/python-net/tr/aspose.slides.ai/asposeaiwebclient/__init__/#str) | Aspose AI web istemcisinin, özel bir uç nokta URL'sine bağlanan bir örneğini oluşturur. Bu aşırı yüklemeyi, Aspose.Slides ekibi tarafından sağlanan bir URL'niz olduğunda kullanın; aksi takdirde varsayılan URL ile **AsposeAIWebClient.#ctor** aşırı yüklemesini kullanın. |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`create_conversation(self)`](/slides/python-net/tr/aspose.slides.ai/asposeaiwebclient/create_conversation/#) | Bir konuşma örneği oluşturur. Normal AI çağrılarının aksine, konuşmalar tüm bağlamı korur. |

### İlgili
* sınıf [`IAIWebClient`](/slides/python-net/tr/aspose.slides.ai/iaiwebclient)
* modül [`aspose.slides.ai`](/slides/python-net/tr/aspose.slides.ai)
* kütüphane [`Aspose.Slides`](/slides/python-net)