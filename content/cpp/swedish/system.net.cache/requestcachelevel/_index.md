---
title: RequestCacheLevel
second_title: Aspose.Slides för C++ API-referens
description: Enumet beskriver cacheinställningar som är tillämpliga för alla WebRequest.
type: docs
weight: 27
url: /sv/system.net.cache/requestcachelevel/
---
## RequestCacheLevel enum

Enumet beskriver cache-inställningar som är tillämpliga för alla [WebRequest](../../system.net/webrequest/).

```cpp
enum class RequestCacheLevel
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Default | 0 | Uppfyller en begäran om en resurs antingen genom att använda den cachade kopian av resursen eller genom att skicka en begäran om resursen till servern. |
| BypassCache | 1 | Uppfyller en begäran genom att använda servern. Inga poster tas från cachen. |
| CacheOnly | 2 | Uppfyller en begäran om en resurs endast från cachen. WebException kommer att kastas när en resurs inte finns i klientens cache. |
| CacheIfAvailable | 3 | Uppfyller en begäran om en resurs från cachen om resursen är tillgänglig, annars skickas en begäran till servern. |
| Revalidate | 4 | Använder en lokal kopia av en resurs om klientens tidsstämpel är densamma som tidsstämpeln för resursen på servern. Annars laddas en resurs ner från en server. |
| Reload | 5 | En resurs laddas alltid ner från servern. |
| NoCacheNoStore | 6 | Uppfyller aldrig en begäran genom att använda resurser från cachen och cachar inte resurser. |

## Se även

* Namnrymd [System::Net::Cache](../)
* Bibliotek [Aspose.Slides](../../)