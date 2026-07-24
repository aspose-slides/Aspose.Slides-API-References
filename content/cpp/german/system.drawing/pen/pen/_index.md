---
title: Pen()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein neues Pen-Objekt, das die angegebene Farbe darstellt.
type: docs
weight: 1
url: /de/system.drawing/pen/pen/
---
## Pen::Pen(const Color\&) Konstruktor


Erstellt ein neues [Pen](../)-Objekt, das die angegebene Farbe darstellt.

```cpp
System::Drawing::Pen::Pen(const Color &color)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| color | const [Color](../../color/)\& | Die Farbe des Stifts, die vom zu erstellenden Objekt dargestellt wird. |

## Pen::Pen(const Color\&, float) Konstruktor


Erstellt ein neues [Pen](../)-Objekt, das die angegebene Farbe und Breite darstellt.

```cpp
System::Drawing::Pen::Pen(const Color &color, float width)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| color | const [Color](../../color/)\& | Die Farbe des Stifts, die vom zu erstellenden Objekt dargestellt wird. |
| width | **float** | Die Breite des Stifts, die vom zu erstellenden Objekt dargestellt wird. |

## Pen::Pen(const SharedPtr\<Brush\>\&) Konstruktor


Erstellt ein neues [Pen](../)-Objekt und initialisiert es mit dem angegebenen [Brush](../../brush/)-Objekt.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Das [Brush](../../brush/)-Objekt, das die Füll-Eigenschaften des Stifts angibt, der durch das zu erstellende Objekt repräsentiert wird. |

## Pen::Pen(const SharedPtr\<Brush\>\&, float) Konstruktor


Erstellt ein neues [Pen](../)-Objekt und initialisiert es mit dem angegebenen [Brush](../../brush/)-Objekt.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush, float width)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Das [Brush](../../brush/)-Objekt, das die Füll-Eigenschaften des Stifts angibt, der durch das zu erstellende Objekt repräsentiert wird. |
| width | **float** | Die Breite des Stifts, die vom zu erstellenden Objekt dargestellt wird. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Color](../../color/)
* Klasse [Pen](../)
* Klasse [Brush](../../brush/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)