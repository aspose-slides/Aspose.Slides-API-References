---
title: Background
second_title: Aspose.Slides dla Androida za pośrednictwem odwołania do API Java
description: Reprezentuje tło slajdu.
type: docs
url: /pl/com.aspose.slides/background/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

Reprezentuje tło slajdu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getType()](#getType--) | Zwraca typ wypełnienia tła. |
| [setType(byte value)](#setType-byte-) | Zwraca typ wypełnienia tła. |
| [getFillFormat()](#getFillFormat--) | Zwraca FillFormat dla wypełnienia BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Zwraca EffectFormat dla wypełnienia BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Zwraca ColorFormat dla wypełnienia BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Zwraca indeks wypełnienia BackgroundType.Themed w kolekcji motywów tła. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Zwraca indeks wypełnienia BackgroundType.Themed w kolekcji motywów tła. |
| [getEffective()](#getEffective--) | Pobiera efektywne dane tła z zastosowanym dziedziczeniem. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Zwraca slajd nadrzędny kształtu. |
| [getPresentation()](#getPresentation--) | Zwraca prezentację nadrzędną slajdu. |
### getType() {#getType--}
```
public final byte getType()
```

Zwraca typ wypełnienia tła. Odczyt/Zapis [BackgroundType](../../com.aspose.slides/backgroundtype).

**Zwraca:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Zwraca typ wypełnienia tła. Odczyt/Zapis [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Zwraca FillFormat dla wypełnienia BackgroundType.OwnBackground. Tylko do odczytu [IFillFormat](../../com.aspose.slides/ifillformat).

**Zwraca:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Zwraca EffectFormat dla wypełnienia BackgroundType.OwnBackground. Tylko do odczytu [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Zwraca:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

Zwraca ColorFormat dla wypełnienia BackgroundType.Themed. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

Zwraca indeks wypełnienia BackgroundType.Themed w kolekcji motywów tła. 0 oznacza brak wypełnienia. 1..999 - indeks. Odczyt/Zapis int.

**Zwraca:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

Zwraca indeks wypełnienia BackgroundType.Themed w kolekcji motywów tła. 0 oznacza brak wypełnienia. 1..999 - indeks. Odczyt/Zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```

Pobiera efektywne dane tła z zastosowanym dziedziczeniem.

--------------------

> ```
> This example demonstrates getting effective background properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IBackgroundEffectiveData effectiveBackground = pres.getSlides().get_Item(0).getBackground().getEffective();
>  	System.out.println("Background fill type: " + effectiveBackground.getFillFormat().getFillType());
>  	System.out.println("Any effects applied: " + !effectiveBackground.getEffectFormat().isNoEffects());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - jest [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Wersja. Tylko do odczytu long.

**Zwraca:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```

Zwraca slajd nadrzędny kształtu. Tylko do odczytu [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Zwraca:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```

Zwraca prezentację nadrzędną slajdu. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**
[Presentation](../../com.aspose.slides/presentation)