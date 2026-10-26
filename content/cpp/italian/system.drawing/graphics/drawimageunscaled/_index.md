---
title: DrawImageUnscaled()
second_title: Riferimento API di Aspose.Slides per C++
description: Disegna l'immagine specificata usando la sua dimensione fisica originale nella posizione specificata.
type: docs
weight: 443
url: /it/system.drawing/graphics/drawimageunscaled/
---
## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int) metodo


Disegna l'immagine specificata usando la sua dimensione fisica originale nella posizione specificata.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| x | int | La coordinata X dell'angolo in alto a sinistra dell'immagine disegnata |
| y | int | La coordinata Y dell'angolo in alto a sinistra dell'immagine disegnata |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int, int, int) metodo


Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y, int width, int height)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| x | int | La coordinata X dell'angolo in alto a sinistra dell'immagine disegnata |
| y | int | La coordinata Y dell'angolo in alto a sinistra dell'immagine disegnata |
| width | int | Non usato |
| height | int | Non usato |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Rectangle\&) metodo


Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Rectangle &rect)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| rect | const [Rectangle](../../rectangle/)\& | Il rettangolo che specifica l'angolo in alto a sinistra dell'immagine disegnata. Le proprietà X e Y del rettangolo specificano l'angolo in alto a sinistra. I valori di larghezza e altezza sono ignorati. |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Point\&) metodo


Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Point &point)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'immagine da disegnare |
| point | const [Point](../../point/)\& | La struttura [Point](../../point/) che specifica l'angolo in alto a sinistra dell'immagine disegnata. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Image](../../image/)
* Classe [Graphics](../)
* Classe [Rectangle](../../rectangle/)
* Classe [Point](../../point/)
* Namespace [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)