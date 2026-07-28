---
title: CreateLinkedTokenSource()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy összekapcsolt token forrást, amely megszakad, ha a megadott tokenek bármelyike megszakad.
type: docs
weight: 66
url: /hu/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken\&, const CancellationToken\&) method


Létrehoz egy összekapcsolt token forrást, amely megszakad, ha a megadott tokenek bármelyike megszakad.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | Az első figyelendő megszakítási token. |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | A második figyelendő megszakítási token. |

### Visszatérési érték

Új token forrás, amely megszakad, ha bármelyik bemeneti token megszakad.

## Megjegyzések



A visszaadott forrás azonnal megszakad, ha bármelyik bemeneti token már meg van szakítva. 

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [CancellationTokenSource](../)
* Osztály [CancellationToken](../../cancellationtoken/)
* Névtere [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)