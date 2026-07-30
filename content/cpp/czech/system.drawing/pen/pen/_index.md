---
title: Pen()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří nový objekt Pen představující zadanou barvu.
type: docs
weight: 1
url: /cs/system.drawing/pen/pen/
---
## Pen::Pen(const Color\&) konstruktor

Vytvoří nový [Pen](../) objekt reprezentující zadanou barvu.

```cpp
System::Drawing::Pen::Pen(const Color &color)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| color | const [Color](../../color/)\& | Barva tužky reprezentované objektem, který je vytvářen |

## Pen::Pen(const Color\&, float) konstruktor

Vytvoří nový [Pen](../) objekt reprezentující zadanou barvu a šířku.

```cpp
System::Drawing::Pen::Pen(const Color &color, float width)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| color | const [Color](../../color/)\& | Barva tužky reprezentované objektem, který je vytvářen |
| width | **float** | Šířka tužky reprezentované objektem, který je vytvářen |

## Pen::Pen(const SharedPtr\<Brush\>\&) konstruktor

Vytvoří nový [Pen](../) objekt a inicializuje jej specifikovaným [Brush](../../brush/) objektem.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Objekt [Brush](../../brush/), který určuje výplňové vlastnosti tužky reprezentované objektem, který je vytvářen |

## Pen::Pen(const SharedPtr\<Brush\>\&, float) konstruktor

Vytvoří nový [Pen](../) objekt a inicializuje jej specifikovaným [Brush](../../brush/) objektem.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush, float width)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Objekt [Brush](../../brush/), který určuje výplňové vlastnosti tužky reprezentované objektem, který je vytvářen |
| width | **float** | Šířka tužky reprezentované objektem, který je vytvářen |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Color](../../color/)
* Class [Pen](../)
* Class [Brush](../../brush/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)