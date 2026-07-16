---
title: PixelFormat
second_title: Référence API Aspose.Slides pour C++
description: Spécifie le format des données couleur d'un pixel.
type: docs
weight: 326
url: /fr/system.drawing.imaging/pixelformat/
---
## PixelFormat enum

Spécifie le format des données couleur d’un pixel.

```cpp
enum class PixelFormat
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Indexed | 65536 | Spécifie que les données du pixel contiennent des valeurs d’index de couleur, ce qui signifie qu’elles sont un index vers les couleurs de la table de couleurs système. |
| Gdi | 131072 | Spécifie que les données du pixel contiennent des couleurs GDI. |
| Alpha | 262144 | Spécifie que les données du pixel contiennent des valeurs alpha non pré-multipliées. |
| PAlpha | 524288 | Spécifie que les données du pixel contiennent des valeurs alpha pré-multipliées. |
| Extended | 1048576 | Réservé. |
| Canonical | 2097152 | Spécifie le format de pixel de 32 bits par pixel avec une profondeur de couleur de 24 bits et un canal alpha de 8 bits. |
| Undefined | 0 | Spécifie que le format de pixel est indéfini. |
| DontCare | 0 | Le format de pixel n’est pas spécifié. |
| Format1bppIndexed | n/a | Spécifie que le format de pixel est une couleur indexée de 1 bit par pixel. |
| Format4bppIndexed | n/a | Spécifie que le format de pixel est une couleur indexée de 4 bits par pixel. |
| Format8bppIndexed | n/a | Spécifie que le format de pixel est une couleur indexée de 8 bits par pixel. |
| Format16bppGrayScale | n/a | Spécifie que le format de pixel est de 16 bits par pixel. L’information couleur spécifie 65 536 nuances de gris. |
| Format16bppRgb555 | n/a | Spécifie que le format de pixel est de 16 bits par pixel avec 5 bits pour chacun des composants rouge, vert et bleu et le bit restant non utilisé. |
| Format16bppRgb565 | n/a | Spécifie que le format de pixel est de 16 bits par pixel avec 5 bits pour le rouge, 6 bits pour le vert et 5 bits pour le bleu. |
| Format16bppArgb1555 | n/a | Spécifie que le format de pixel est de 16 bits par pixel avec 5 bits pour chacun des composants rouge, vert et bleu et 1 bit pour l’alpha. |
| Format24bppRgb | n/a | Spécifie que le format de pixel est de 24 bits par pixel avec 8 bits pour chacun des composants rouge, vert et bleu. |
| Format32bppRgb | n/a | Spécifie que le format de pixel est de 32 bits par pixel avec 8 bits pour chacun des composants rouge, vert et bleu et les 8 bits restants non utilisés. |
| Format32bppArgb | n/a | Spécifie que le format de pixel est de 32 bits par pixel avec 8 bits pour chacun des composants rouge, vert et bleu et 8 bits pour l’alpha. |
| Format32bppPArgb | n/a | Spécifie que le format de pixel est de 32 bits par pixel avec 8 bits pour chacun des composants rouge, vert et bleu et 8 bits pour l’alpha. Les composants rouge, vert et bleu sont pré-multipliés selon la valeur du composant alpha. |
| Format48bppRgb | n/a | Spécifie que le format de pixel est de 48 bits par pixel avec 16 bits pour chacun des composants rouge, vert et bleu. |
| Format64bppArgb | n/a | Spécifie que le format de pixel est de 64 bits par pixel avec 16 bits pour chacun des composants rouge, vert et bleu et 16 bits pour l’alpha. |
| Format64bppPArgb | n/a | Spécifie que le format de pixel est de 64 bits par pixel avec 16 bits pour chacun des composants rouge, vert et bleu et 16 bits pour l’alpha. Les composants rouge, vert et bleu sont pré-multipliés selon la valeur du composant alpha. |
| Format32bppCMYK | n/a | Spécifie que le format de pixel est de 32 bits par pixel avec 8 bits pour chacun des composants cyan, magenta, jaune et noir. |
| Max | 16 | La valeur maximale de cet enum. |

## Voir aussi

* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.Slides](../../)