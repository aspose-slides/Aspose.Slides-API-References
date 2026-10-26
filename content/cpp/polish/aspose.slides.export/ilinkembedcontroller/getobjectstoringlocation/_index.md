---
title: GetObjectStoringLocation()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Określa, gdzie obiekt powinien być przechowywany. Ta metoda jest wywoływana raz dla każdego identyfikatora obiektu. Nie jest gwarantowane, że nie będą dwa obiekty z takimi samymi danymi, semanticName i contentType, ale o różnym identyfikatorze.
type: docs
weight: 1
url: /pl/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) metoda


Określa, gdzie obiekt powinien być przechowywany. Ta metoda jest wywoływana raz dla każdego identyfikatora obiektu. Nie jest gwarantowane, że nie będą dwa obiekty z takimi samymi danymi, semanticName i contentType, ale o różnym identyfikatorze.

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| id | **int32_t** | Identyfikator obiektu. Ten identyfikator jest unikalny w całej operacji zapisu. |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dane binarne obiektu. Ten parametr może być null, jeśli dane binarne obiektu nie zostały jeszcze wygenerowane. |
| semanticName | [System::String](../../../system/string/) | Krótki tekst opisujący znaczenie obiektu. Kontroler może używać tego jako części zewnętrznej nazwy obiektu, ale to do dyspozytora należy zapewnienie, że nazwy będą unikalne i zawierały wyłącznie dozwolone znaki. |
| contentType | [System::String](../../../system/string/) | Typ MIME obiektu. |
| recomendedExtension | [System::String](../../../system/string/) | Rozszerzenie nazwy pliku, zalecane dla tego typu MIME. |

### Wartość zwracana

Decyzja

## Zobacz także

* Enum [LinkEmbedDecision](../../linkembeddecision/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [String](../../../system/string/)
* Klasa [ILinkEmbedController](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)