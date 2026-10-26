---
title: GetUrl()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: "Zwraca URL do zewnętrznego obiektu. Ta metoda jest zawsze wywoływana, jeśli ILinkEmbedController::GetObjectStoringLocation zwrócił LinkEmbedDecision::Link i może być wywołana, jeśli ILinkEmbedController::GetObjectStoringLocation zwrócił LinkEmbedDecision::Embed, ale osadzenie jest niemożliwe. Może być wywoływana wielokrotnie dla tego samego identyfikatora obiektu."
type: docs
weight: 14
url: /pl/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) metoda

Zwraca URL do zewnętrznego obiektu. Ta metoda zawsze jest wywoływana, jeśli [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) zwrócił [LinkEmbedDecision::Link](../../linkembeddecision/) i może być wywołana, jeśli [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) zwrócił [LinkEmbedDecision::Embed](../../linkembeddecision/), ale osadzenie jest niemożliwe. Może być wywołana wielokrotnie dla tego samego identyfikatora obiektu.

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| id | **int32_t** | Identyfikator obiektu. Ten identyfikator jest unikalny w całej operacji. |
| referrer | **int32_t** | id obiektu odwołującego się lub 0, jeśli obiekt jest odwoływany przez dokument główny. Może być użyte do wygenerowania linku względnego. |

### Wartość zwracana

URL zewnętrznego obiektu lub null, jeśli ten obiekt powinien zostać zignorowany.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [ILinkEmbedController](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)