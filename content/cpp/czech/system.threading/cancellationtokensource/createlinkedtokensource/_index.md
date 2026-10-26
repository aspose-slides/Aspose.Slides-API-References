---
title: CreateLinkedTokenSource()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří propojený zdroj tokenu, který se zruší, když se zruší kterýkoli z poskytnutých tokenů.
type: docs
weight: 66
url: /cs/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken\&, const CancellationToken\&) metoda

Vytvoří propojený zdroj tokenu, který se zruší, když se zruší kterýkoli z poskytnutých tokenů.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | První token pro zrušení, který se má sledovat. |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | Druhý token pro zrušení, který se má sledovat. |

### Návratová hodnota

Nový zdroj tokenu, který se zruší, když se zruší kterýkoli vstupní token.

## Poznámky

Vrácený zdroj se okamžitě zruší, pokud je kterýkoli vstupní token již zrušen.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [CancellationTokenSource](../)
* Třída [CancellationToken](../../cancellationtoken/)
* Jmenný prostor [System::Threading](../../)
* Knihovna [Aspose.Slides](../../../)