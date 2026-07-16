---
title: Pen()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit un nouvel objet Pen représentant la couleur spécifiée.
type: docs
weight: 1
url: /fr/system.drawing/pen/pen/
---
## Pen::Pen(const Color\&) constructor

Construit un nouvel objet [Pen](../) représentant la couleur spécifiée.

```cpp
System::Drawing::Pen::Pen(const Color &color)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| color | const [Color](../../color/)\& | La couleur du stylo représentée par l'objet en cours de construction |

## Pen::Pen(const Color\&, float) constructor

Construit un nouvel objet [Pen](../) représentant la couleur et la largeur spécifiées.

```cpp
System::Drawing::Pen::Pen(const Color &color, float width)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| color | const [Color](../../color/)\& | La couleur du stylo représentée par l'objet en cours de construction |
| width | **float** | La largeur du stylo représentée par l'objet en cours de construction |

## Pen::Pen(const SharedPtr\<Brush\>\&) constructor

Construit un nouvel objet [Pen](../) et l'initialise avec l'objet [Brush](../../brush/) spécifié.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | L'objet [Brush](../../brush/) qui spécifie les propriétés de remplissage du stylo représenté par l'objet en cours de construction |

## Pen::Pen(const SharedPtr\<Brush\>\&, float) constructor

Construit un nouvel objet [Pen](../) et l'initialise avec l'objet [Brush](../../brush/) spécifié.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush, float width)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | L'objet [Brush](../../brush/) qui spécifie les propriétés de remplissage du stylo représenté par l'objet en cours de construction |
| width | **float** | La largeur du stylo représentée par l'objet en cours de construction |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Color](../../color/)
* Classe [Pen](../)
* Classe [Brush](../../brush/)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)