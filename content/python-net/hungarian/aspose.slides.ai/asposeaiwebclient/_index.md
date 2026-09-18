---
title: AsposeAIWebClient class
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.ai/asposeaiwebclient/
---
## AsposeAIWebClient osztály

Beépített [`IAIWebClient`](/slides/python-net/hu/aspose.slides.ai/iaiwebclient) megvalósítás, amely az Aspose saját LLM-jéhez csatlakozik. Ez az alapértelmezett kliens, amelyet a paraméter nélküli **SlidesAIAgent.#ctor** konstruktor használ.

Az AsposeAIWebClient típus a következő tagokat teszi közzé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient/__init__/#) | Az Aspose AI webkliens egy példányát hozza létre, amely a alapértelmezett Aspose LLM végponthoz kapcsolódik.<br/>            Ez a kliens a paraméter nélküli **SlidesAIAgent.#ctor** konstruktor által használt, ezért explicit módon csak akkor szükséges létrehozni, ha a klienst közvetlenül a **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** konstruktorba adja át. |
| [`__init__(self, url)`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient/__init__/#str) | Az Aspose AI webkliens egy példányát hozza létre, amely egy egyéni végpont URL-hez csatlakozik. Használja ezt a túlterhelést, ha az Aspose.Slides csapat által biztosított URL áll rendelkezésre; egyébként használja a **AsposeAIWebClient.#ctor** túlterhelést az alapértelmezett URL-lel. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`create_conversation(self)`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient/create_conversation/#) | Konverzációs példányt hoz létre. A rendszeres AI hívásokkal ellentétben a beszélgetések megtartják a teljes kontextust. |

### Lásd még
* osztály [`IAIWebClient`](/slides/python-net/hu/aspose.slides.ai/iaiwebclient)
* modul [`aspose.slides.ai`](/slides/python-net/hu/aspose.slides.ai)
* könyvtár [`Aspose.Slides`](/slides/python-net)