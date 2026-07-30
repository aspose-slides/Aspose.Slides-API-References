---
title: CustomLineCap()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza della classe CustomLineCap che rappresenta un'estremità di linea definita dall'utente con le proprietà specificate.
type: docs
weight: 1
url: /it/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) costruttore

Crea una nuova istanza della classe [CustomLineCap](../) che rappresenta un'estremità di linea definita dall'utente con le proprietà specificate.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Specifica un riempimento per l'estremità personalizzata |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Specifica un contorno dell'estremità personalizzata |
| baseCap | [LineCap](../../linecap/) | L'estremità di linea di base da cui è creata l'estremità personalizzata |
| baseInset | **float** | Specifica la distanza tra la linea e l'estremità |

## Vedi anche

* Enum [LineCap](../../linecap/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [GraphicsPath](../../graphicspath/)
* Classe [CustomLineCap](../)
* Spazio dei nomi [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)