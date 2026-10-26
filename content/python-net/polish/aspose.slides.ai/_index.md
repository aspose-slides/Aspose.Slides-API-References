---
title: aspose.slides.ai
second_title: Aspose.Slides dla Pythona poprzez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides.ai/
---
Zawiera klasy zapewniające funkcje oparte na AI do analizy i przetwarzania prezentacji PowerPoint.
## Klasy

| Klasa | Opis |
| :- | :- |
| [`AsposeAIWebClient`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient/) | Wbudowana implementacja [`IAIWebClient`](/slides/python-net/pl/aspose.slides.ai/iaiwebclient) łącząca się z własnym LLM firmy Aspose.<br/>            Jest to domyślny klient używany przez konstruktor bezparametrowy **SlidesAIAgent.#ctor**. |
| [`IAIConversation`](/slides/python-net/pl/aspose.slides.ai/iaiconversation/) | Reprezentuje instancję konwersacji. W odróżnieniu od zwykłych wywołań AI, konwersacje zachowują cały kontekst. |
| [`IAIWebClient`](/slides/python-net/pl/aspose.slides.ai/iaiwebclient/) | Interfejs klienta AI Web. Ten interfejs umożliwia podmianę różnych modeli językowych AI.<br/>            Klasy implementujące ten interfejs powinny być używane razem z `SlidesAIAgent`. |
| [`OpenAICompatibleWebClient`](/slides/python-net/pl/aspose.slides.ai/openaicompatiblewebclient/) | Wbudowana implementacja [`IAIWebClient`](/slides/python-net/pl/aspose.slides.ai/iaiwebclient) łącząca się z dostawcą LLM kompatybilnym z OpenAI<br/>            pod określonym bazowym adresem URL. |
| [`OpenAIWebClient`](/slides/python-net/pl/aspose.slides.ai/openaiwebclient/) | Wbudowana implementacja [`IAIWebClient`](/slides/python-net/pl/aspose.slides.ai/iaiwebclient) łącząca się z API OpenAI. |
| [`SlidesAIAgent`](/slides/python-net/pl/aspose.slides.ai/slidesaiagent/) | Udostępnia funkcje oparte na AI do przetwarzania prezentacji. |
| [`SlidesAIAgentException`](/slides/python-net/pl/aspose.slides.ai/slidesaiagentexception/) | Reprezentuje wyjątki związane z Slides AI Agent. |

## Wyliczenia

| Wyliczenie | Opis |
| :- | :- |
| [`PresentationContentAmountType`](/slides/python-net/pl/aspose.slides.ai/presentationcontentamounttype/) | Określa ilość treści uwzględnionej w generowanej prezentacji, wpływając zarówno na liczbę slajdów, jak i poziom szczegółowości każdego slajdu. |