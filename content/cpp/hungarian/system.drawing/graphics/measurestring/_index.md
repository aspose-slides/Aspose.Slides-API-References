---
title: MeasureString()
second_title: Aspose.Slides C++ API hivatkozás
description: Visszaadja a megadott karakterlánc méretét, amikor a megadott betűtípussal, a megadott formátumban rajzolják.
type: docs
weight: 521
url: /hu/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const metódus

Visszaadja a megadott karakterlánc méretét, amikor a megadott betűtípussal, a megadott formátumban rajzolják.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | A karakterlánc, amelynek méretét ki kell számolni |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | A karakterlánc rajzolásához használt betűtípus |
| origin | [PointF](../../pointf/) const\& | Megadja a karakterlánc bal felső sarkának helyét |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Megadja a karakterlánc formátumát |

### Visszatérési érték

Egy [SizeF](../../sizef/) objektum, amely a karakterlánc méretét reprezentálja a jelenlegi Graphics objektum PageUnit tulajdonsága által megadott mérési egységekben.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const metódus

Visszaadja a megadott karakterlánc méretét, amikor a megadott betűtípussal, a megadott formátumban rajzolják.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | A karakterlánc, amelynek méretét ki kell számolni |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | A karakterlánc rajzolásához használt betűtípus |
| width | int | A karakterlánc legnagyobb szélessége |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Megadja a karakterlánc formátumát |

### Visszatérési érték

Egy [SizeF](../../sizef/) objektum, amely a karakterlánc méretét reprezentálja a jelenlegi Graphics objektum PageUnit tulajdonsága által megadott mérési egységekben.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const metódus

NEM IMPLEMENTÁLVA.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const metódus

Visszaadja a megadott karakterlánc méretét, amikor a megadott betűtípussal, a megadott formátumban rajzolják.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | A karakterlánc, amelynek méretét ki kell számolni |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | A karakterlánc rajzolásához használt betűtípus |
| layoutArea | [SizeF](../../sizef/) const\& | A karakterlánc legnagyobb elrendezési területe |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Megadja a karakterlánc formátumát |

### Visszatérési érték

Egy [SizeF](../../sizef/) objektum, amely a karakterlánc méretét reprezentálja a jelenlegi Graphics objektum PageUnit tulajdonsága által megadott mérési egységekben.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [SizeF](../../sizef/)
* Osztály [String](../../../system/string/)
* Osztály [Font](../../font/)
* Osztály [PointF](../../pointf/)
* Osztály [StringFormat](../../stringformat/)
* Osztály [Graphics](../)
* Névtere [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)