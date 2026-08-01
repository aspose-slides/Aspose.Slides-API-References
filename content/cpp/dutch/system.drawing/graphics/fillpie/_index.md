---
title: FillPie()
second_title: Aspose.Slides voor C++ API-referentie
description: Vult de opgegeven taart met de opgegeven brush op het oppervlak dat wordt vertegenwoordigd door het huidige object.
type: docs
weight: 274
url: /nl/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) methode


Vult de opgegeven taart met de opgegeven brush op het oppervlak dat wordt vertegenwoordigd door het huidige object.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Een brush om te gebruiken bij het vullen van de taart |
| x | int | De X-coördinaat van de linkerbovenhoek van de rechthoek die de ellips definieert |
| y | int | De Y-coördinaat van de linkerbovenhoek van de rechthoek die de ellips definieert |
| width | int | De breedte van de rechthoek die de ellips definieert |
| height | int | De hoogte van de rechthoek die de ellips definieert |
| startAngle | int | Hoek in graden, met de klok mee gemeten vanaf de X-as tot het startpunt van de taart |
| sweepAngle | int | Hoek in graden, met de klok mee gemeten vanaf de **startAngle** tot het eindpunt van de taart |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) methode


Vult de opgegeven taart met de opgegeven brush op het oppervlak dat wordt weergegeven door het huidige object.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Een brush om te gebruiken bij het vullen van de taart |
| x | **float** | De X-coördinaat van de linkerbovenhoek van de rechthoek die de ellips definieert |
| y | **float** | De Y-coördinaat van de linkerbovenhoek van de rechthoek die de ellips definieert |
| width | **float** | De breedte van de rechthoek die de ellips definieert |
| height | **float** | De hoogte van de rechthoek die de ellips definieert |
| startAngle | **float** | Hoek in graden, met de klok mee gemeten vanaf de X-as tot het startpunt van de taart |
| sweepAngle | **float** | Hoek in graden, met de klok mee gemeten vanaf de **startAngle** tot het eindpunt van de taart |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) methode


Vult de opgegeven taart met de opgegeven brush op het oppervlak dat wordt vertegenwoordigd door het huidige object.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Een brush om te gebruiken bij het vullen van de taart |
| rect | [Rectangle](../../rectangle/) | De rechthoek die de ellips definieert |
| startAngle | **float** | Hoek in graden, met de klok mee gemeten vanaf de X-as tot het startpunt van de taart |
| sweepAngle | **float** | Hoek in graden, met de klok mee gemeten vanaf de **startAngle** tot het eindpunt van de taart |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Brush](../../brush/)
* Klasse [Graphics](../)
* Klasse [Rectangle](../../rectangle/)
* Naamruimte [System::Drawing](../../)
* Bibliotheek [Aspose.Slides](../../../)