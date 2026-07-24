---
title: Point()
second_title: Aspose.Slides für C++ API Referenz
description: Konstruiert ein neues Point-Objekt und initialisiert seine X- und Y-Koordinatenwerte mit 0.
type: docs
weight: 1
url: /de/system.drawing/point/point/
---
## Point::Point() Konstruktor


Konstruiert ein neues [Point](../)-Objekt und initialisiert seine X- und Y-Koordinatenwerte mit 0.

```cpp
System::Drawing::Point::Point()
```

## Point::Point(int, int) Konstruktor


Konstruiert ein neues [Point](../)-Objekt und initialisiert es mit den angegebenen Werten.

```cpp
System::Drawing::Point::Point(int x, int y)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Der Wert der X-Koordinate |
| y | int | Der Wert der Y-Koordinate |

## Point::Point(const Size\&) Konstruktor


Konstruiert ein neues [Point](../)-Objekt und initialisiert seine X- und Y-Koordinatenwerte mit den Breiten- und Höhenwerten des angegebenen [SizeF](../../sizef/)-Objekts entsprechend.

```cpp
System::Drawing::Point::Point(const Size &size)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | const [Size](../../size/)\& | Ein [SizeF](../../sizef/)-Objekt, dessen Breiten- und Höhenwerte verwendet werden, um die X- und Y-Koordinatenwerte des erstellten [Point](../)-Objekts zu initialisieren |

## Point::Point(int) Konstruktor


Konstruiert ein neues [Point](../)-Objekt und initialisiert seinen X-Koordinatenwert mit einem Wert, der aus den oberen 16 Bits der angegebenen 32-Bit-Ganzzahl gebildet wird, und seinen Y-Koordinatenwert mit einem Wert, der aus den unteren 16 Bits der angegebenen 32-Bit-Ganzzahl gebildet wird.

```cpp
System::Drawing::Point::Point(int dw)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dw | int | Der 32-Bit-Ganzzahlwert, dessen obere 16 Bits den X-Koordinatenwert und dessen untere 16 Bits den Y-Koordinatenwert des zu erstellenden Objekts festlegen |

## Siehe auch

* Klasse [Point](../)
* Klasse [Size](../../size/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)