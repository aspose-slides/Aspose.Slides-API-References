---
title: BeginContainer()
second_title: Riferimento API di Aspose.Slides per C++
description: Salva un contenitore con lo stato attuale di questo oggetto, apre e utilizza un nuovo contenitore e restituisce il contenitore salvato.
type: docs
weight: 976
url: /it/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() metodo


Salva un contenitore con lo stato attuale di questo oggetto, apre e utilizza un nuovo contenitore e restituisce il contenitore salvato.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) metodo


Salva un contenitore con lo stato attuale di questo oggetto, apre e utilizza un nuovo contenitore e restituisce il contenitore salvato.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | Il rettangolo che specifica una trasformazione di scala del nuovo contenitore. Usato insieme a **srcrect** |
| srcrect | [Rectangle](../../rectangle/) | Il rettangolo che specifica una trasformazione di scala del nuovo contenitore. Usato insieme a **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | Il valore che specifica l'unità di misura del nuovo contenitore |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) metodo


Salva un contenitore con lo stato attuale di questo oggetto, apre e utilizza un nuovo contenitore e restituisce il contenitore salvato.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | Il rettangolo che specifica una trasformazione di scala del nuovo contenitore. Usato insieme a **srcrect** |
| srcrect | [RectangleF](../../rectanglef/) | Il rettangolo che specifica una trasformazione di scala del nuovo contenitore. Usato insieme a **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | Il valore che specifica l'unità di misura del nuovo contenitore |

## Vedi anche

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Classe [Graphics](../)
* Classe [Rectangle](../../rectangle/)
* Classe [RectangleF](../../rectanglef/)
* namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)