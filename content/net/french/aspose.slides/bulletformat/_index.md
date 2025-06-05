---
title: BulletFormat
second_title: Référence API d'Aspose.Sildes pour .NET
description: Représente les propriétés de formatage de puces de paragraphes.
type: docs
weight: 990
url: /fr/aspose.slides/bulletformat/
---

## Classe BulletFormat

Représente les propriétés de formatage de puces de paragraphes.

```csharp
public sealed class BulletFormat : PVIObject, IBulletFormat
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface IPresentationComponent de base. Lecture seule [`IPresentationComponent`](../ipresentationcomponent). |
| [Char](../../aspose.slides/bulletformat/char) { get; set; } | Renvoie ou définit le caractère de puce d'un paragraphe sans héritage. Lecture/écriture Char. |
| [Color](../../aspose.slides/bulletformat/color) { get; } | Renvoie le format de couleur d'une puce d'un paragraphe sans héritage. Lecture seule [`IColorFormat`](../icolorformat). |
| [Font](../../aspose.slides/bulletformat/font) { get; set; } | Renvoie ou définit la police de la puce d'un paragraphe sans héritage. Lecture/écriture [`IFontData`](../ifontdata). |
| [Height](../../aspose.slides/bulletformat/height) { get; set; } | Renvoie ou définit la hauteur de la puce d'un paragraphe sans héritage. La valeur float.NaN détermine que la puce hérite de la hauteur de la première portion du paragraphe. Lecture/écriture Single. |
| [IsBulletHardColor](../../aspose.slides/bulletformat/isbullethardcolor) { get; set; } | Détermine si la puce a sa propre couleur ou l'hérite de la première portion du paragraphe. **NullableBool.True** si la puce a sa propre couleur et **NullableBool.False** si la puce hérite de la couleur de la première portion du paragraphe. Lecture/écriture [`NullableBool`](../nullablebool). |
| [IsBulletHardFont](../../aspose.slides/bulletformat/isbullethardfont) { get; set; } | Détermine si la puce a sa propre police ou l'hérite de la première portion du paragraphe. **NullableBool.True** si la puce a sa propre police et **NullableBool.False** si la puce hérite de la police de la première portion du paragraphe. Lecture/écriture [`NullableBool`](../nullablebool). |
| [NumberedBulletStartWith](../../aspose.slides/bulletformat/numberedbulletstartwith) { get; set; } | Renvoie ou définit le premier numéro utilisé pour un groupe de puces numérotées sans héritage. Lecture/écriture Int16. |
| [NumberedBulletStyle](../../aspose.slides/bulletformat/numberedbulletstyle) { get; set; } | Renvoie ou définit le style d'une puce numérotée sans héritage. Lecture/écriture [`NumberedBulletStyle`](../numberedbulletstyle). |
| [Picture](../../aspose.slides/bulletformat/picture) { get; } | Renvoie l'image utilisée comme puce dans un paragraphe sans héritage. Lecture seule [`ISlidesPicture`](../islidespicture). |
| [Type](../../aspose.slides/bulletformat/type) { get; set; } | Renvoie ou définit le type de puce d'un paragraphe sans héritage. Lecture/écriture [`BulletType`](../bullettype). |

## Méthodes

| Nom | Description |
| --- | --- |
| [ApplyDefaultParagraphIndentsShifts](../../aspose.slides/bulletformat/applydefaultparagraphindentsshifts)() | Définit des décalages non nuls par défaut pour l'indentation effective des paragraphes et le MargentGauche lorsque les puces sont activées (comme PowerPoint le fait si la numérotation/pucelage de paragraphes est activée). Si les puces sont désactivées, réinitialise simplement l'indentation et le MargentGauche du paragraphe (comme PowerPoint le fait si la numérotation/pucelage de paragraphes est désactivée). Les décalages d'indentation sont appliqués par rapport au contexte de puces actuel - IBulletFormat.Type, .NumberedBulletStyle et FontHeight de la première portion. Les décalages d'indentation non nuls sont appliqués à l'indentation effective et au MargentGauche du paragraphe actuel (rendant les valeurs résultantes locales). |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compare avec l'objet spécifié. |
| [GetEffective](../../aspose.slides/bulletformat/geteffective)() | Obtient les données de formatage de puces effectives avec l'héritage appliqué. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Renvoie le code de hachage. |

### Voir aussi

* classe [PVIObject](../pviobject)
* interface [IBulletFormat](../ibulletformat)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)