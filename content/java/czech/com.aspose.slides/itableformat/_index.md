---
title: ITableFormat
second_title: Aspose.Slides for Java API Reference
description: Representuje formát tabulky.
type: docs
url: /cs/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Representuje formát tabulky.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Vrací objekt vlastností výplně tabulky. |
| [getTransparency()](#getTransparency--) | Získá nebo nastaví průhlednost výplňové barvy. |
| [setTransparency(float value)](#setTransparency-float-) | Získá nebo nastaví průhlednost výplňové barvy. |
| [getEffective()](#getEffective--) | Získá účinné vlastnosti formátování tabulky s aplikovaným děděním a styly tabulek. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Vrací objekt vlastností výplně tabulky. Pouze ke čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

Získá nebo nastaví průhlednost výplňové barvy. Čtení/zápis  float .

**Vrací:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

Získá nebo nastaví průhlednost výplňové barvy. Čtení/zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```

Získá účinné vlastnosti formátování tabulky s aplikovaným děděním a styly tabulek.

**Vrací:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Jedna [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).