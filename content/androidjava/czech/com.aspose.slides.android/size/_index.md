---
title: Size
second_title: Aspose.Slides pro Android přes referenci Java API
description: Třída pro popis šířky a výšky v libovolné jednotce.
type: docs
url: /cs/com.aspose.slides.android/size/
---
**Dědičnost:**
java.lang.Object
```
public class Size
```

Třída pro popis šířky a výšky v libovolné jednotce.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | Vytvoří novou instanci Size. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getWidth()](#getWidth--) | Získá šířku velikosti. |
| [getHeight()](#getHeight--) | Získá výšku velikosti. |
| [equals(Object obj)](#equals-java.lang.Object-) | Zkontroluje, zda je tato velikost rovna jiné velikosti. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Vrátí velikost jako řetězec ve formátu "WxH" |
### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```

Vytvoří novou instanci Size.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| width | int | Šířka velikosti |
| height | int | Výška velikosti |
### getWidth() {#getWidth--}
```
public int getWidth()
```

Získá šířku velikosti.

**Vrací:**
int - šířka
### getHeight() {#getHeight--}
```
public int getHeight()
```

Získá výšku velikosti.

**Vrací:**
int - výška
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Zkontroluje, zda je tato velikost rovna jiné velikosti.

Dvě velikosti jsou rovny právě tehdy, když jsou jejich šířky i výšky stejné.

Objekt velikosti není nikdy roven žádnému jinému typu objektu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Vrací:**
boolean - true pokud jsou objekty rovny, false jinak
### hashCode() {#hashCode--}
```
public int hashCode()
```

**Vrací:**
int
### toString() {#toString--}
```
public String toString()
```

Vrátí velikost jako řetězec ve formátu "WxH"

**Vrací:**
java.lang.String - řetězcová reprezentace velikosti