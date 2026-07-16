---
title: DrawString()
second_title: Référence de l'API Aspose.Slides pour C++
description: Dessine la chaîne spécifiée à l'emplacement spécifié en utilisant la police et le pinceau spécifiés.
type: docs
weight: 365
url: /fr/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) méthode

Dessine la chaîne spécifiée à l'emplacement spécifié en utilisant la police et le pinceau spécifiés.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | La chaîne à dessiner |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Une police à utiliser |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un objet [Brush](../../brush/) à utiliser pour le dessin |
| topLeft | [PointF](../../pointf/) | Spécifie l'emplacement du coin supérieur gauche de la chaîne dessinée |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Spécifie le format de la chaîne |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) méthode

Dessine la chaîne spécifiée dans le rectangle indiqué en utilisant la police et le pinceau spécifiés.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | La chaîne à dessiner |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Une police à utiliser |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un objet [Brush](../../brush/) à utiliser pour le dessin |
| layoutRectangle | [RectangleF](../../rectanglef/) | Spécifie un rectangle dans lequel dessiner la chaîne |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Spécifie le format de la chaîne |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) méthode

Dessine la chaîne spécifiée à l'emplacement spécifié en utilisant la police et le pinceau spécifiés.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | La chaîne à dessiner |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Une police à utiliser |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un objet [Brush](../../brush/) à utiliser pour le dessin |
| x | **float** | La coordonnée X de l'emplacement du coin supérieur gauche de la chaîne dessinée |
| y | **float** | La coordonnée Y de l'emplacement du coin supérieur gauche de la chaîne dessinée |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Spécifie le format de la chaîne |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Font](../../font/)
* Classe [Brush](../../brush/)
* Classe [PointF](../../pointf/)
* Classe [StringFormat](../../stringformat/)
* Classe [Graphics](../)
* Classe [RectangleF](../../rectanglef/)
* Espace de noms [System::Drawing](../../)
* Library [Aspose.Slides](../../../)