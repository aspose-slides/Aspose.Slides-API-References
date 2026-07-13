---
title: ITableFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje formát tabulky.
type: docs
url: /cs/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Reprezentuje formát tabulky.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Vrací objekt vlastností výplně tabulky. |
| [getTransparency()](#getTransparency--) | Získává nebo nastavuje průhlednost výplňové barvy. |
| [setTransparency(float value)](#setTransparency-float-) | Získává nebo nastavuje průhlednost výplňové barvy. |
| [getEffective()](#getEffective--) | Získává efektivní vlastnosti formátování tabulky s aplikovaným děděním a styly tabulky. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Vrací objekt vlastností výplně tabulky. Pouze pro čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Získává nebo nastavuje průhlednost výplňové barvy. Čtení/Zápis  float .

**Vrací:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Získává nebo nastavuje průhlednost výplňové barvy. Čtení/Zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


Získává efektivní vlastnosti formátování tabulky s aplikovaným děděním a styly tabulky.

**Vrací:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).