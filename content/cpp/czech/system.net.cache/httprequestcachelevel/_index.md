---
title: HttpRequestCacheLevel
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Výčet popisuje nastavení mezipaměti pro HTTP.
type: docs
weight: 40
url: /cs/system.net.cache/httprequestcachelevel/
---
## HttpRequestCacheLevel výčet

Výčet popisuje nastavení mezipaměti pro HTTP.

```cpp
enum class HttpRequestCacheLevel
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Default | 0 | Vyhoví požadavku na zdroj buď použitím uložené kopie zdroje, nebo odesláním požadavku na zdroj na server. |
| BypassCache | 1 | Vyhoví požadavku použitím serveru. |
| CacheOnly | 2 | Vždy používá mezipaměť klienta k získání zdroje. |
| CacheIfAvailable | 3 | Vyhoví požadavku na zdroj z mezipaměti, pokud je zdroj dostupný, jinak odešle požadavek na server. |
| Revalidate | 4 | Použije lokální kopii zdroje, pokud je časové razítko klienta stejné jako časové razítko zdroje na serveru. V opačném případě je zdroj stažen ze serveru. |
| Reload | 5 | Zdroj je vždy stažen ze serveru. |
| NoCacheNoStore | 6 | Nikdy nevyhoví požadavku použitím zdrojů z mezipaměti a neukládá zdroje do mezipaměti. |
| CacheOrNextCacheOnly | 7 | Vyhoví požadavku na zdroj buď z mezipaměti lokálního počítače, nebo ze vzdálené mezipaměti v LAN. |
| Refresh | 8 | Vyhoví požadavku použitím serveru nebo mezipaměti jinou než lokální mezipaměť. |

## Viz také

* Jmenný prostor [System::Net::Cache](../)
* Knihovna [Aspose.Slides](../../)