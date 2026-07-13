---
title: SizeF
second_title: Aspose.Slides pro Android pomocí reference API Java
description: Třída pro popis šířky a výšky v některé libovolné jednotce s hodnotami s plovoucí desetinnou čárkou.
type: docs
url: /cs/com.aspose.slides.android/sizef/
---
**Dědičnost:**
java.lang.Object
```
public class SizeF
```

Třída pro popis šířky a výšky v některé libovolné jednotce s hodnotami s plovoucí desetinnou čárkou.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | Vytvořte novou instanci SizeF. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getWidth()](#getWidth--) | Získá šířku velikosti. |
| [getHeight()](#getHeight--) | Získá výšku velikosti. |
| [equals(Object obj)](#equals-java.lang.Object-) | Zkontroluje, zda je tato velikost rovna jiné velikosti. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Vrátí velikost jako řetězec ve formátu  "WxH"  |
### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Vytvořte novou instanci SizeF.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| width | float | Šířka velikosti |
| height | float | Výška velikosti |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Získá šířku velikosti.

**Návratová hodnota:**
float - šířka
### getHeight() {#getHeight--}
```
public float getHeight()
```


Získá výšku velikosti.

**Návratová hodnota:**
float - výška
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Zkontroluje, zda je tato velikost rovna jiné velikosti.

Dvě velikosti jsou stejné, pokud a jen pokud jsou jejich šířky i výšky identické.

Pro tento účel jsou hodnoty šířky/výšky typu float považovány za stejné, pokud a jen pokud metoda Float#floatToIntBits(float).floatToIntBits(float) vrátí stejnou hodnotu typu int při aplikaci na každou z nich.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Návratová hodnota:**
boolean - true pokud byly objekty stejné, false jinak
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Návratová hodnota:**
int
### toString() {#toString--}
```
public String toString()
```


Vrátí velikost jako řetězec ve formátu  "WxH" 

**Návratová hodnota:**
java.lang.String - řetězcová reprezentace velikosti