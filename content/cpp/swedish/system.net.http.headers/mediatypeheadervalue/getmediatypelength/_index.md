---
title: GetMediaTypeLength()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar en given sträng från det angivna indexet till en instans av MediaTypeHeaderValue-klassen.
type: docs
weight: 144
url: /sv/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength(String, int32_t, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>>, System::SharedPtr<MediaTypeHeaderValue>&) metod

Konverterar en given sträng från den angivna indexen till en instans av [MediaTypeHeaderValue](../)-klassen.

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [String](../../../system/string/) | En sträng att tolka. |
| startIndex | **int32_t** | En startposition för tolkning. |
| mediaTypeCreator | [HeaderFunc](../../headerfunc/)<[System::SharedPtr](../../../system/sharedptr/)<[MediaTypeHeaderValue](../)>> | Delegaten som används för att skapa instanser av [MediaTypeHeaderValue](../)-klassen. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)<[MediaTypeHeaderValue](../)>& | En instans där ett analyserat objekt kommer att tilldelas. |

### Returvärde

Returnerar längden på en analyserad delsträng, annars 0.

## Se även

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [MediaTypeHeaderValue](../)
* Namnrymd [System::Net::Http::Headers](../../)
* Bibliotek [Aspose.Slides](../../../)