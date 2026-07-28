---
title: TryParse()
second_title: Aspose.Slides for C++ API Referenciája
description: Átalakítja a megadott karakterláncot, amely egy szám sztring ábrázolását tartalmazza, a megfelelő Decimal értékké.
type: docs
weight: 482
url: /hu/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám sztring ábrázolását tartalmazza, a megfelelő [Decimal](../) értékké.

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc |
| result | [Decimal](../)\& | Az a [Decimal](../) változóra mutató hivatkozás, ahová a konverzió eredménye kerül |

### Visszatérési érték

Igaz, ha a konverzió sikerült, egyébként - hamis

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám sztring ábrázolását tartalmazza, a megfelelő [Decimal](../) értékké a megadott formázási információk és számstílus felhasználásával.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles felsoroló értékeinek bitenkénti kombinációja, amely meghatározza a szám sztring ábrázolásának engedélyezett stílusát |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy objektumra, amely a karakterlánc formátuminformációit tartalmazza |
| result | [Decimal](../)\& | Kimeneti argumentum; tartalmazza a konverzió eredményét |

### Visszatérési érték

Igaz, ha a konverzió sikerült, egyébként - hamis

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Decimal](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)