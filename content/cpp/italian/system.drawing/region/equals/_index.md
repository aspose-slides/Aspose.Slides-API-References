---
title: Equals()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se la regione specificata è identica alla regione rappresentata dall'oggetto corrente sulla superficie di disegno specificata.
type: docs
weight: 157
url: /it/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) metodo


Determina se la regione specificata è identica alla regione rappresentata dall'oggetto corrente sulla superficie di disegno specificata.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | La regione da confrontare con questa regione |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Una superficie di disegno |

### Valore restituito

True se l'interno della regione specificata è identico all'interno della regione rappresentata dall'oggetto corrente quando viene applicata la trasformazione associata al parametro **g**; altrimenti - false

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Region](../)
* Classe [Graphics](../../graphics/)
* Namespace [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)