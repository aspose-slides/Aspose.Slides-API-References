---
title: RequestCacheLevel
second_title: Aspose.Slides pro C++ API Reference
description: Výčet popisuje nastavení mezipaměti použitelné pro libovolný WebRequest.
type: docs
weight: 27
url: /cs/system.net.cache/requestcachelevel/
---
## RequestCacheLevel enum

The enum describes cache settings applicable for any [WebRequest](../../system.net/webrequest/).

```cpp
enum class RequestCacheLevel
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Default | 0 | Vyhoví požadavku na zdroj buď použitím uložené kopie zdroje, nebo odesláním požadavku na zdroj na server. |
| BypassCache | 1 | Vyhoví požadavku použitím serveru. Žádné položky nejsou načteny z mezipaměti. |
| CacheOnly | 2 | Vyhoví požadavku na zdroj pouze z mezipaměti. Bude vyvolána výjimka WebException, pokud zdroj není v mezipaměti klienta. |
| CacheIfAvailable | 3 | Vyhoví požadavku na zdroj z mezipaměti, pokud je zdroj dostupný, jinak odešle požadavek na server. |
| Revalidate | 4 | Použije lokální kopii zdroje, pokud je časové razítko klienta stejné jako časové razítko zdroje na serveru. Jinak je zdroj stažen ze serveru. |
| Reload | 5 | Zdroj je vždy stažen ze serveru. |
| NoCacheNoStore | 6 | Nikdy nevyhoví požadavku použitím zdrojů z mezipaměti a neukládá zdroje do mezipaměti. |

## Viz také

* Jmenný prostor [System::Net::Cache](../)
* Knihovna [Aspose.Slides](../../)