---
title: IChartTitle
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Představuje vlastnosti titulku grafu.
type: docs
url: /cs/com.aspose.slides/icharttitle/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

Představuje vlastnosti titulku grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getOverlay()](#getOverlay--) | Určuje, zda mají být ostatní prvky grafu povoleny překrývat titul. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Určuje, zda mají být ostatní prvky grafu povoleny překrývat titul. |
| [getFormat()](#getFormat--) | Vrací styly výplně, čáry a efektu titulku. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Určuje, zda mají být ostatní prvky grafu povoleny překrývat titul. Čtení/Zápis boolean.

**Vrací:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Určuje, zda mají být ostatní prvky grafu povoleny překrývat titul. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Vrací styly výplně, čáry a efektu titulku. Pouze pro čtení [IFormat](../../com.aspose.slides/iformat).

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)