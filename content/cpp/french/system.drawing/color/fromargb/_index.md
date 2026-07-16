---
title: FromArgb()
second_title: Référence API Aspose.Slides pour C++
description: Construit une instance de la classe Color qui représente la couleur spécifiée.
type: docs
weight: 235
url: /fr/system.drawing/color/fromargb/
---
## Color::FromArgb(int) méthode

Construit une instance de la classe [Color](../) qui représente la couleur spécifiée.

```cpp
static Color System::Drawing::Color::FromArgb(int argb)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| argb | int | Une valeur ARGB de 32 bits de la couleur à représenter par l'objet en cours de construction |

### Valeur de retour

Un objet qui représente la couleur spécifiée.

## Color::FromArgb(int, int, int, int) méthode

Construit une instance de la classe [Color](../) qui représente la couleur spécifiée.

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, int red, int green, int blue)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| alpha | int | Une valeur du composant alpha de la couleur |
| red | int | Une valeur du composant rouge de la couleur |
| green | int | Une valeur du composant vert de la couleur |
| blue | int | Une valeur du composant bleu de la couleur |

### Valeur de retour

Un objet qui représente la couleur spécifiée.

## Color::FromArgb(int, int, int) méthode

Construit une instance de la classe [Color](../) qui représente la couleur spécifiée avec le composant alpha réglé à 0xFF.

```cpp
static Color System::Drawing::Color::FromArgb(int red, int green, int blue)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| red | int | Une valeur du composant rouge de la couleur |
| green | int | Une valeur du composant vert de la couleur |
| blue | int | Une valeur du composant bleu de la couleur |

### Valeur de retour

Un objet qui représente la couleur spécifiée.

## Color::FromArgb(int, Color) méthode

Construit une instance de la classe [Color](../) qui représente la couleur spécifiée.

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, Color base_color)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| alpha | int | Une valeur du composant alpha de la couleur |
| base_color | [Color](../) | Une instance de l'objet [Color](../) qui représente les composants rouge, vert et bleu de la couleur à représenter par l'objet en cours de création |

### Valeur de retour

Un objet qui représente la couleur spécifiée.

## Voir aussi

* Classe [Color](../)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)