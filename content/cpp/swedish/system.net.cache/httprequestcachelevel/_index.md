---
title: HttpRequestCacheLevel
second_title: Aspose.Slides för C++ API-referens
description: Enumet beskriver cacheinställningar för HTTP.
type: docs
weight: 40
url: /sv/system.net.cache/httprequestcachelevel/
---
## HttpRequestCacheLevel enum

Enumet beskriver cache-inställningar för HTTP.

```cpp
enum class HttpRequestCacheLevel
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Default | 0 | Uppfyller en förfrågan om en resurs antingen genom att använda den cachade kopian av resursen eller genom att skicka en förfrågan om resursen till servern. |
| BypassCache | 1 | Uppfyller en förfrågan genom att använda servern. |
| CacheOnly | 2 | Använder alltid klientcachen för att hämta en resurs. |
| CacheIfAvailable | 3 | Uppfyller en förfrågan om en resurs från cachen om resursen är tillgänglig, annars skickas en förfrågan till servern. |
| Revalidate | 4 | Använder en lokal kopia av en resurs om klientens tidsstämpel är samma som tidsstämpeln för resursen på servern. Annars laddas en resurs ner från en server. |
| Reload | 5 | En resurs laddas alltid ner från servern. |
| NoCacheNoStore | 6 | Uppfyller aldrig en förfrågan genom att använda resurser från cachen och lagrar inte resurser. |
| CacheOrNextCacheOnly | 7 | Uppfyller en förfrågan om en resurs antingen från den lokala datorns cache eller från en fjärrcache på LANet. |
| Refresh | 8 | Uppfyller en förfrågan genom att använda servern eller en annan cache än den lokala cachen. |

## Se också

* Namnrymd [System::Net::Cache](../)
* Bibliotek [Aspose.Slides](../../)