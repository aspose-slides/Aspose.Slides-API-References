---
title: Field
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta un campo.
type: docs
url: /it/com.aspose.slides/field/
---
**Ereditarietà:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IField](../../com.aspose.slides/ifield)
```
public final class Field extends DomObject<Portion> implements IField
```

Rappresenta un campo.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Restituisce o imposta il tipo del campo. |
| [setType(IFieldType value)](#setType-com.aspose.slides.IFieldType-) | Restituisce o imposta il tipo del campo. |
| [getSlide()](#getSlide--) | Restituisce la diapositiva padre di un paragrafo. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione padre di un paragrafo. |
### getType() {#getType--}
```
public final IFieldType getType()
```

Restituisce o imposta il tipo del campo. Lettura/Scrittura [IFieldType](../../com.aspose.slides/ifieldtype).

**Restituisce:**
[IFieldType](../../com.aspose.slides/ifieldtype)
### setType(IFieldType value) {#setType-com.aspose.slides.IFieldType-}
```
public final void setType(IFieldType value)
```

Restituisce o imposta il tipo del campo. Lettura/Scrittura [IFieldType](../../com.aspose.slides/ifieldtype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Restituisce la diapositiva padre di un paragrafo. Sola lettura [BaseSlide](../../com.aspose.slides/baseslide).

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Restituisce la presentazione padre di un paragrafo. Sola lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)