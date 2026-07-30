---
title: FillPie()
second_title: Riferimento API di Aspose.Slides per C++
description: Riempie la torta specificata usando il pennello specificato sulla superficie rappresentata dall'oggetto corrente.
type: docs
weight: 274
url: /it/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) metodo


Riempie la torta specificata usando il pennello specificato sulla superficie rappresentata dall'oggetto corrente.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un pennello da usare per riempire la torta |
| x | int | La coordinata X dell'angolo in alto a sinistra del rettangolo che definisce l'ellisse |
| y | int | La coordinata Y dell'angolo in alto a sinistra del rettangolo che definisce l'ellisse |
| width | int | La larghezza del rettangolo che definisce l'ellisse |
| height | int | L'altezza del rettangolo che definisce l'ellisse |
| startAngle | int | Angolo in gradi misurato in senso orario dall'asse X al punto di partenza della torta |
| sweepAngle | int | Angolo in gradi misurato in senso orario dal **startAngle** al punto finale della torta |


## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) metodo


Riempie la torta specificata usando il pennello specificato sulla superficie rappresentata dall'oggetto corrente.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un pennello da usare per riempire la torta |
| x | **float** | La coordinata X dell'angolo in alto a sinistra del rettangolo che definisce l'ellisse |
| y | **float** | La coordinata Y dell'angolo in alto a sinistra del rettangolo che definisce l'ellisse |
| width | **float** | La larghezza del rettangolo che definisce l'ellisse |
| height | **float** | L'altezza del rettangolo che definisce l'ellisse |
| startAngle | **float** | Angolo in gradi misurato in senso orario dall'asse X al punto di partenza della torta |
| sweepAngle | **float** | Angolo in gradi misurato in senso orario dal **startAngle** al punto finale della torta |


## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) metodo


Riempie la torta specificata usando il pennello specificato sulla superficie rappresentata dall'oggetto corrente.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un pennello da usare per riempire la torta |
| rect | [Rectangle](../../rectangle/) | Il rettangolo che definisce l'ellisse |
| startAngle | **float** | Angolo in gradi misurato in senso orario dall'asse X al punto di partenza della torta |
| sweepAngle | **float** | Angolo in gradi misurato in senso orario dal **startAngle** al punto finale della torta |


## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Brush](../../brush/)
* Classe [Graphics](../)
* Classe [Rectangle](../../rectangle/)
* Spazio dei nomi [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)