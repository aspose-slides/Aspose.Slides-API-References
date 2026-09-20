---
title: aspose.slides.ai
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.ai/
---
Obsahuje třídy, které poskytují funkce založené na AI pro analýzu a zpracování prezentací PowerPoint.
## Třídy

| Třída | Popis |
| :- | :- |
| [`AsposeAIWebClient`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient/) | Vestavěná implementace [`IAIWebClient`](/slides/python-net/cs/aspose.slides.ai/iaiwebclient), která se připojuje k vlastnímu LLM společnosti Aspose.<br/>            Toto je výchozí klient používaný konstruktoru **SlidesAIAgent.#ctor** bez parametrů. |
| [`IAIConversation`](/slides/python-net/cs/aspose.slides.ai/iaiconversation/) | Představuje instanci konverzace. Na rozdíl od běžných AI volání konverzace zachovávají celý kontext. |
| [`IAIWebClient`](/slides/python-net/cs/aspose.slides.ai/iaiwebclient/) | Rozhraní AI webového klienta. Toto rozhraní umožňuje nahradit různé modely AI jazyků.<br/>            Třídy, které implementují toto rozhraní, by měly být používány spolu s `SlidesAIAgent`. |
| [`OpenAICompatibleWebClient`](/slides/python-net/cs/aspose.slides.ai/openaicompatiblewebclient/) | Vestavěná implementace [`IAIWebClient`](/slides/python-net/cs/aspose.slides.ai/iaiwebclient), která se připojuje k poskytovateli LLM kompatibilnímu s OpenAI<br/>            na zadaném základním URL. |
| [`OpenAIWebClient`](/slides/python-net/cs/aspose.slides.ai/openaiwebclient/) | Vestavěná implementace [`IAIWebClient`](/slides/python-net/cs/aspose.slides.ai/iaiwebclient), která se připojuje k OpenAI API. |
| [`SlidesAIAgent`](/slides/python-net/cs/aspose.slides.ai/slidesaiagent/) | Poskytuje funkce poháněné AI pro zpracování prezentací. |
| [`SlidesAIAgentException`](/slides/python-net/cs/aspose.slides.ai/slidesaiagentexception/) | Představuje výjimky související s Slides AI Agent. |

## Výčty

| Výčet | Popis |
| :- | :- |
| [`PresentationContentAmountType`](/slides/python-net/cs/aspose.slides.ai/presentationcontentamounttype/) | Určuje množství obsahu zahrnutého do vygenerované prezentace, ovlivňující jak počet snímků, tak úroveň podrobností na snímek. |