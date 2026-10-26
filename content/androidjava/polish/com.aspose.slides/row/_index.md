---
title: Row
second_title: Aspose.Slides dla Androida za pośrednictwem odniesienia API Java
description: Reprezentuje wiersz w tabeli.
type: docs
url: /pl/com.aspose.slides/row/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

Reprezentuje wiersz w tabeli.
## Metody

| Metoda | Opis |
| --- | --- |
| [getHeight()](#getHeight--) | Zwraca wysokość wiersza. |
| [getMinimalHeight()](#getMinimalHeight--) | Zwraca lub ustawia minimalną możliwą wysokość wiersza. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Zwraca lub ustawia minimalną możliwą wysokość wiersza. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Ustawia zdefiniowane właściwości formatu części dla wszystkich części komórek wiersza. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Ustawia zdefiniowane właściwości formatu akapitu dla wszystkich akapitów komórek wiersza. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Ustawia zdefiniowane właściwości formatu ramki tekstowej dla wszystkich ramek tekstowych komórek wiersza. |
| [getRowFormat()](#getRowFormat--) | Zwraca obiekt RowFormat, który zawiera właściwości formatowania tego wiersza. |

### getHeight() {#getHeight--}
```
public final double getHeight()
```

Zwraca wysokość wiersza. Tylko do odczytu double.

**Zwraca:**
double

### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Zwraca lub ustawia minimalną możliwą wysokość wiersza. Odczyt/zapis double.

**Zwraca:**
double

### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```

Zwraca lub ustawia minimalną możliwą wysokość wiersza. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Ustawia zdefiniowane właściwości formatu części dla wszystkich części komórek wiersza.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | obiekt IPortionFormat z ustawionymi niezbędnymi właściwościami. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Ustawia zdefiniowane właściwości formatu akapitu dla wszystkich akapitów komórek wiersza.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | obiekt IParagraphFormat z ustawionymi niezbędnymi właściwościami. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Ustawia zdefiniowane właściwości formatu ramki tekstowej dla wszystkich ramek tekstowych komórek wiersza.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | obiekt ITextFrameFormat z ustawionymi niezbędnymi właściwościami. |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```

Zwraca obiekt RowFormat, który zawiera właściwości formatowania tego wiersza. Tylko do odczytu [IRowFormat](../../com.aspose.slides/irowformat).

**Zwraca:**
[IRowFormat](../../com.aspose.slides/irowformat)