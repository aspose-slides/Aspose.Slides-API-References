---
title: aspose.slides.ai
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides.ai/
---
Tartalmaz olyan osztályokat, amelyek AI-alapú funkciókat nyújtanak a PowerPoint prezentációk elemzéséhez és feldolgozásához.
## Osztályok

| Osztály | Leírás |
| :- | :- |
| [`AsposeAIWebClient`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient/) | Beépített [`IAIWebClient`](/slides/python-net/hu/aspose.slides.ai/iaiwebclient) megvalósítás, amely az Aspose saját LLM-jéhez csatlakozik.<br/>            Ez az alapértelmezett kliens, amely a paraméter nélküli **SlidesAIAgent.#ctor** konstruktor által használatos. |
| [`IAIConversation`](/slides/python-net/hu/aspose.slides.ai/iaiconversation/) | Beszélgetés példányt képvisel. A hagyományos AI hívásoktól eltérően a beszélgetések megőrzik a teljes kontextust. |
| [`IAIWebClient`](/slides/python-net/hu/aspose.slides.ai/iaiwebclient/) | AI webkliens interfész. Ez az interfész lehetővé teszi különböző AI nyelvi modellek helyettesítését.<br/>            Az ezt az interfészt megvalósító osztályok a `SlidesAIAgent`-tel együtt használatosak. |
| [`OpenAICompatibleWebClient`](/slides/python-net/hu/aspose.slides.ai/openaicompatiblewebclient/) | Beépített [`IAIWebClient`](/slides/python-net/hu/aspose.slides.ai/iaiwebclient) megvalósítás, amely egy OpenAI-kompatibilis LLM szolgáltatóhoz csatlakozik<br/>            egy megadott alap URL-hez. |
| [`OpenAIWebClient`](/slides/python-net/hu/aspose.slides.ai/openaiwebclient/) | Beépített [`IAIWebClient`](/slides/python-net/hu/aspose.slides.ai/iaiwebclient) megvalósítás, amely az OpenAI API-hoz csatlakozik. |
| [`SlidesAIAgent`](/slides/python-net/hu/aspose.slides.ai/slidesaiagent/) | AI-alapú funkciókat biztosít a prezentációk feldolgozásához. |
| [`SlidesAIAgentException`](/slides/python-net/hu/aspose.slides.ai/slidesaiagentexception/) | A Slides AI Agent-hez kapcsolódó kivételeket képviseli. |

## Enumerációk

| Enumeráció | Leírás |
| :- | :- |
| [`PresentationContentAmountType`](/slides/python-net/hu/aspose.slides.ai/presentationcontentamounttype/) | Meghatározza a generált prezentációban szereplő tartalom mennyiségét, befolyásolva ezzel a diák számát és a diánkénti részletezettség szintjét. |