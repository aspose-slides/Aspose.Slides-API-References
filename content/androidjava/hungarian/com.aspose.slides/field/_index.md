---
title: Field
second_title: Aspose.Slides Androidra Java API hivatkozás segítségével
description: Mezőt reprezentál.
type: docs
url: /hu/com.aspose.slides/field/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.IField](../../com.aspose.slides/ifield)
```
public final class Field extends DomObject<Portion> implements IField
```

Mezőt reprezentál.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getType()](#getType--) | Returns or sets field's type. |
| [setType(IFieldType value)](#setType-com.aspose.slides.IFieldType-) | Returns or sets field's type. |
| [getSlide()](#getSlide--) | Returns the parent slide of a paragraph. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a paragraph. |
### getType() {#getType--}
```
public final IFieldType getType()
```

Visszaadja vagy beállítja a mező típusát. Olvasás/írás [IFieldType](../../com.aspose.slides/ifieldtype).

**Visszatér:**
[IFieldType](../../com.aspose.slides/ifieldtype)
### setType(IFieldType value) {#setType-com.aspose.slides.IFieldType-}
```
public final void setType(IFieldType value)
```

Visszaadja vagy beállítja a mező típusát. Olvasás/írás [IFieldType](../../com.aspose.slides/ifieldtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja a bekezdés szülő diáját. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a bekezdés szülő prezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)