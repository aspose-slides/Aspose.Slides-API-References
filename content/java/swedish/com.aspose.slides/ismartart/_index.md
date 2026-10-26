---
title: ISmartArt
second_title: Aspose.Slides för Java API-referens
description: Representerar ett SmartArt-diagram.
type: docs
url: /sv/com.aspose.slides/ismartart/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

Representerar ett SmartArt-diagram.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Returnerar samlingar av alla noder i SmartArt-objektet. |
| [getNodes()](#getNodes--) | Returnerar samlingar av rotnoder i SmartArt-objektet. |
| [getLayout()](#getLayout--) | Returnera eller ställ in layout för SmartArt-objektet. |
| [setLayout(int value)](#setLayout-int-) | Returnera eller ställ in layout för SmartArt-objektet. |
| [getQuickStyle()](#getQuickStyle--) | Returnera eller ställ in snabbstil för SmartArt-objektet. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Returnera eller ställ in snabbstil för SmartArt-objektet. |
| [getColorStyle()](#getColorStyle--) | Returnera eller ställ in färgstilen för SmartArt-objektet. |
| [setColorStyle(int value)](#setColorStyle-int-) | Returnera eller ställ in färgstilen för SmartArt-objektet. |
| [isReversed()](#isReversed--) | Returnera eller ställ in diagrammets tillstånd med avseende på (vänster-till-höger) LTR eller (höger-till-vänster) RTL, om diagrammet stöder omvändning. |
| [setReversed(boolean value)](#setReversed-boolean-) | Returnera eller ställ in diagrammets tillstånd med avseende på (vänster-till-höger) LTR eller (höger-till-vänster) RTL, om diagrammet stöder omvändning. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

Returnerar samlingar av alla noder i SmartArt-objektet. Endast läsning [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Returnerar:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

Returnerar samlingar av rotnoder i SmartArt-objektet. Endast läsning [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Returnerar:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

Returnera eller ställ in layout för SmartArt-objektet. Läs-skriv [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Returnerar:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

Returnera eller ställ in layout för SmartArt-objektet. Läs-skriv [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

Returnera eller ställ in snabbstil för SmartArt-objektet. Läs-skriv [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Returnerar:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```

Returnera eller ställ in snabbstil för SmartArt-objektet. Läs-skriv [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

Returnera eller ställ in färgstilen för SmartArt-objektet. Läs-skriv [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Returnerar:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

Returnera eller ställ in färgstilen för SmartArt-objektet. Läs-skriv [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

Returnera eller ställ in diagrammets tillstånd med avseende på (vänster-till-höger) LTR eller (höger-till-vänster) RTL, om diagrammet stöder omvändning. Läs-skriv boolean.

**Returnerar:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

Returnera eller ställ in diagrammets tillstånd med avseende på (vänster-till-höger) LTR eller (höger-till-vänster) RTL, om diagrammet stöder omvändning. Läs-skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |