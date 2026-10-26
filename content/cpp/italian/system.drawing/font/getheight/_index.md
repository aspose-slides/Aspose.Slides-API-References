---
title: GetHeight()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce l'interlinea del carattere rappresentato dall'oggetto corrente, nell'unità corrente di un oggetto Graphics specificato.
type: docs
weight: 14
url: /it/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) metodo

Restituisce l'interlinea del carattere rappresentato dall'oggetto corrente, nell'unità corrente di un oggetto [Graphics](../../graphics/) specificato.

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Un oggetto [Graphics](../../graphics/) che specifica le unità di misura |

## Font::GetHeight(float) metodo

Restituisce l'altezza del carattere rappresentato dall'oggetto corrente quando viene disegnato su un dispositivo di visualizzazione con la risoluzione verticale specificata.

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dpi | **float** | La risoluzione verticale del dispositivo di visualizzazione |

### Valore di ritorno

L'altezza del carattere in pixel

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Graphics](../../graphics/)
* Classe [Font](../)
* Spazio dei nomi [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)