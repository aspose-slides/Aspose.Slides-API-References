---
title: Size
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Klasa służąca do opisywania wymiarów szerokości i wysokości w dowolnej jednostce.
type: docs
url: /pl/com.aspose.slides.android/size/
---
**Dziedziczenie:**
java.lang.Object
```
public class Size
```

Klasa służąca do opisywania wymiarów szerokości i wysokości w dowolnej jednostce.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | Utwórz nową instancję Size. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getWidth()](#getWidth--) | Pobierz szerokość rozmiaru. |
| [getHeight()](#getHeight--) | Pobierz wysokość rozmiaru. |
| [equals(Object obj)](#equals-java.lang.Object-) | Sprawdź, czy ten rozmiar jest równy innemu rozmiarowi. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Zwróć rozmiar jako łańcuch znaków w formacie "WxH" |
### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```

Utwórz nową instancję Size.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| width | int | Szerokość rozmiaru |
| height | int | Wysokość rozmiaru |
### getWidth() {#getWidth--}
```
public int getWidth()
```

Pobierz szerokość rozmiaru.

**Zwraca:**
int - szerokość
### getHeight() {#getHeight--}
```
public int getHeight()
```

Pobierz wysokość rozmiaru.

**Zwraca:**
int - wysokość
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Sprawdź, czy ten rozmiar jest równy innemu rozmiarowi.

Dwa rozmiary są równe wtedy i tylko wtedy, gdy ich szerokości i wysokości są równe.

Obiekt rozmiaru nigdy nie jest równy obiektowi innego typu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Zwraca:**
boolean - true, jeśli obiekty były równe, false w przeciwnym razie
### hashCode() {#hashCode--}
```
public int hashCode()
```

**Zwraca:**
int
### toString() {#toString--}
```
public String toString()
```

Zwróć rozmiar jako łańcuch znaków w formacie "WxH"

**Zwraca:**
java.lang.String - reprezentacja łańcucha rozmiaru