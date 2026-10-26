---
title: GetHeight()
second_title: Aspose.Slides C++ API hivatkozás
description: Visszaadja a jelen objektum által képviselt betűtípus sorközét, a meghatározott Graphics objektum aktuális egységében.
type: docs
weight: 14
url: /hu/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) metódus


Visszaadja a jelen objektum által képviselt betűtípus vonalközét, a megadott [Graphics](../../graphics/) objektum aktuális egységében.

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | [Graphics](../../graphics/) objektum, amely meghatározza a mértékegységeket |

## Font::GetHeight(float) metódus


Visszaadja a jelen objektum által képviselt betűtípus magasságát, amikor a megadott függőleges felbontású megjelenítő eszközre rajzolják.

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| dpi | **float** | A megjelenítő eszköz függőleges felbontása |

### Visszatérési érték

A betűtípus magassága pixelekben

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Graphics](../../graphics/)
* Osztály [Font](../)
* Névtere [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)