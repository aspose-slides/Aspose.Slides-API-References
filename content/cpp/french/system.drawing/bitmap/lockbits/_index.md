---
title: LockBits()
second_title: Référence de l'API Aspose.Slides pour C++
description: Verrouille un Bitmap dans la mémoire système.
type: docs
weight: 118
url: /fr/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) méthode

Verrouille un [Bitmap](../) dans la mémoire système.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Un rectangle qui spécifie la région de l'image à verrouiller |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Spécifie le niveau d'accès au bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Le format de données de ce bitmap |

### Valeur de retour

Un pointeur partagé vers un objet BitmapData qui contient des informations sur l'opération de verrouillage effectuée

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) méthode

Verrouille un [Bitmap](../) dans la mémoire système.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Un rectangle qui spécifie la région de l'image à verrouiller |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Spécifie le niveau d'accès au bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Le format de données de ce bitmap |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | Contient des informations sur l'opération de verrouillage |

### Valeur de retour

Un pointeur partagé vers un objet BitmapData qui contient des informations sur l'opération de verrouillage effectuée

## Voir aussi

* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Classe [Rectangle](../../rectangle/)
* Classe [Bitmap](../)
* Espace de noms [System::Drawing](../../)
* Library [Aspose.Slides](../../../)