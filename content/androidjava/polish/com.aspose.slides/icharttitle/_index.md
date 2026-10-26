---
title: IChartTitle
second_title: Aspose.Slides dla Androida poprzez interfejs API Java
description: Reprezentuje właściwości tytułu wykresu.
type: docs
url: /pl/com.aspose.slides/icharttitle/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

Reprezentuje właściwości tytułu wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getOverlay()](#getOverlay--) | Określa, czy inne elementy wykresu mogą nakładać się na tytuł. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Określa, czy inne elementy wykresu mogą nakładać się na tytuł. |
| [getFormat()](#getFormat--) | Zwraca style wypełnienia, linii i efektów tytułu. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Określa, czy inne elementy wykresu mogą nakładać się na tytuł. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Określa, czy inne elementy wykresu mogą nakładać się na tytuł. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Zwraca style wypełnienia, linii i efektów tytułu. Tylko do odczytu [IFormat](../../com.aspose.slides/iformat).

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)