---
title: SizeF
second_title: Aspose.Slides dla Androida – odwołanie do API Java
description: Klasa służąca do opisywania wymiarów szerokości i wysokości w dowolnej jednostce za pomocą wartości zmiennoprzecinkowych.
type: docs
url: /pl/com.aspose.slides.android/sizef/
---
**Dziedziczenie:**
java.lang.Object
```
public class SizeF
```

Klasa służąca do opisywania wymiarów szerokości i wysokości w dowolnej jednostce za pomocą wartości zmiennoprzecinkowych.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | Create a new SizeF instance. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getWidth()](#getWidth--) | Get the width of the size. |
| [getHeight()](#getHeight--) | Get the height of the size. |
| [equals(Object obj)](#equals-java.lang.Object-) | Check if this size is equal to another size. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Return the size represented as a string with the format  "WxH"  |
### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Utwórz nową instancję SizeF.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| width | float | Szerokość rozmiaru |
| height | float | Wysokość rozmiaru |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Pobiera szerokość rozmiaru.

**Zwraca:**
float - szerokość
### getHeight() {#getHeight--}
```
public float getHeight()
```


Pobiera wysokość rozmiaru.

**Zwraca:**
float - wysokość
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Sprawdza, czy ten rozmiar jest równy innemu rozmiarowi.

Dwa rozmiary są równe wtedy i tylko wtedy, gdy ich szerokości i wysokości są identyczne.

W tym celu wartości zmiennoprzecinkowe szerokości/wysokości są uznawane za takie same wtedy i tylko wtedy, gdy metoda Float\#floatToIntBits(float).floatToIntBits(float) zwraca identyczną wartość typu int po zastosowaniu do obu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Zwraca:**
boolean -  true  jeśli obiekty były równe,  false  w przeciwnym razie
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


Zwraca rozmiar jako ciąg znaków w formacie "WxH" 

**Zwraca:**
java.lang.String - tekstowa reprezentacja rozmiaru