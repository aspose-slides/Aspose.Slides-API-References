---
title: AddPath()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge il percorso specificato al percorso rappresentato dall'oggetto corrente.
type: docs
weight: 222
url: /it/system.drawing.drawing2d/graphicspath/addpath/
---
## GraphicsPath::AddPath(const SharedPtr\<GraphicsPath\>\&, bool) metodo


Aggiunge il percorso specificato al percorso rappresentato dall'oggetto corrente.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPath(const SharedPtr<GraphicsPath> &path, bool connect)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../)\>\& | Il percorso da aggiungere |
| connect | **bool** | True specifica che l'ultima prima figura nel **path** è parte dell'ultima figura del percorso rappresentato dall'oggetto corrente; false specifica che la prima figura nel **path** e l'ultima figura del percorso rappresentato dall'oggetto corrente sono figure separate |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [GraphicsPath](../)
* Spazio dei nomi [System::Drawing::Drawing2D](../../)
* Libreria [Aspose.Slides](../../../)