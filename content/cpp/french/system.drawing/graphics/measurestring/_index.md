---
title: MeasureString()
second_title: Référence de l'API Aspose.Slides pour C++
description: Retourne la taille de la chaîne spécifiée lorsqu'elle est dessinée avec la police spécifiée dans le format spécifié.
type: docs
weight: 521
url: /fr/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const&, System::SharedPtr\<Font\> const&, PointF const&, System::SharedPtr\<StringFormat\> const&) const method

Retourne la taille de la chaîne spécifiée lorsqu’elle est dessinée avec la police spécifiée dans le format spécifié.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) const& | La chaîne dont il faut calculer la taille |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const& | La police utilisée pour dessiner la chaîne |
| origin | [PointF](../../pointf/) const& | Spécifie l’emplacement du coin supérieur gauche de la chaîne |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const& | Spécifie le format de la chaîne |

### Return Value

Un objet [SizeF](../../sizef/) qui représente la taille de la chaîne dans les unités de mesure spécifiées par la propriété PageUnit de l’objet Grapphics actuel.

## Graphics::MeasureString(String const&, System::SharedPtr\<Font\> const&, int, System::SharedPtr\<StringFormat\> const&) const method

Retourne la taille de la chaîne spécifiée lorsqu’elle est dessinée avec la police spécifiée dans le format spécifié.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) const& | La chaîne dont il faut calculer la taille |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const& | La police utilisée pour dessiner la chaîne |
| width | int | La largeur maximale de la chaîne |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const& | Spécifie le format de la chaîne |

### Return Value

Un objet [SizeF](../../sizef/) qui représente la taille de la chaîne dans les unités de mesure spécifiées par la propriété PageUnit de l’objet Grapphics actuel.

## Graphics::MeasureString(String const&, System::SharedPtr\<Font\> const&, SizeF const&, System::SharedPtr\<StringFormat\> const&, int&, int&) const method

NON IMPLEMENTÉ.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```

## Graphics::MeasureString(String const&, System::SharedPtr\<Font\> const&, SizeF const&, System::SharedPtr\<StringFormat\> const&) const method

Retourne la taille de la chaîne spécifiée lorsqu’elle est dessinée avec la police spécifiée dans le format spécifié.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) const& | La chaîne dont il faut calculer la taille |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const& | La police utilisée pour dessiner la chaîne |
| layoutArea | [SizeF](../../sizef/) const& | La zone de mise en page maximale de la chaîne |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const& | Spécifie le format de la chaîne |

### Return Value

Un objet [SizeF](../../sizef/) qui représente la taille de la chaîne dans les unités de mesure spécifiées par la propriété PageUnit de l’objet Grapphics actuel.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SizeF](../../sizef/)
* Class [String](../../../system/string/)
* Class [Font](../../font/)
* Class [PointF](../../pointf/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)