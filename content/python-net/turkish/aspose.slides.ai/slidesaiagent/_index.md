---
title: SlidesAIAgent class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent sınıfı

Sunumları işlemek için AI destekli özellikler sağlar.

SlidesAIAgent tipi aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/tr/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | Özel bir AI istemcisiyle [`SlidesAIAgent`](/slides/python-net/tr/aspose.slides.ai/slidesaiagent)'ın yeni bir örneğini başlatır.<br/>            Bu aşırı yüklemeyi AI sağlayıcısını belirtmek, kendi LLM'nizi sağlamak veya bağlantıyı özelleştirmek için kullanın<br/>            (örneğin, kendi `HttpClient`'inizi sağlayarak).<br/>            [`IAIWebClient`](/slides/python-net/tr/aspose.slides.ai/iaiwebclient)'nin herhangi bir uygulanması, şunları içerebilir:<br/>            <br/>* [`AsposeAIWebClient`](/slides/python-net/tr/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/tr/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/tr/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>            Yerleşik [`AsposeAIWebClient`](/slides/python-net/tr/aspose.slides.ai/asposeaiwebclient)'yi varsayılan yapılandırmasıyla kullanmak için,<br/>            **SlidesAIAgent.#ctor** aşırı yüklemesini kullanın. |
| [`__init__(self)`](/slides/python-net/tr/aspose.slides.ai/slidesaiagent/__init__/#) | [`AsposeAIWebClient`](/slides/python-net/tr/aspose.slides.ai/asposeaiwebclient)'nin varsayılan yapılandırmasıyla [`SlidesAIAgent`](/slides/python-net/tr/aspose.slides.ai/slidesaiagent)'ın yeni bir örneğini başlatır.<br/>            İstemci, Aspose'un kendi LLM'sine bağlanır ve ek yapılandırma gerektirmez.<br/>            Farklı bir AI istemcisi kullanmak için, **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** aşırı yüklemesini kullanın. |

## Metotlar

| Metot | Açıklama |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/tr/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | Metin açıklamasından bir sunum örneği üretir. Gerekli dilde bir konu, fikir, alıntı veya metin parçacığı sağlayın. |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/tr/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | Metin açıklamasından bir sunum örneği üretir. Gerekli dilde bir konu, fikir, alıntı veya metin parçacığı sağlayın. |
| [`translate(self, presentation, language)`](/slides/python-net/tr/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | AI kullanarak bir sunumu belirtilen dile çevirir (senkron sürüm). |

### Ayrıca Bakınız
* sınıf [`AsposeAIWebClient`](/slides/python-net/tr/aspose.slides.ai/asposeaiwebclient)
* sınıf [`IAIWebClient`](/slides/python-net/tr/aspose.slides.ai/iaiwebclient)
* sınıf [`OpenAICompatibleWebClient`](/slides/python-net/tr/aspose.slides.ai/openaicompatiblewebclient)
* sınıf [`OpenAIWebClient`](/slides/python-net/tr/aspose.slides.ai/openaiwebclient)
* sınıf [`SlidesAIAgent`](/slides/python-net/tr/aspose.slides.ai/slidesaiagent)
* modül [`aspose.slides.ai`](/slides/python-net/tr/aspose.slides.ai)
* kütüphane [`Aspose.Slides`](/slides/python-net)