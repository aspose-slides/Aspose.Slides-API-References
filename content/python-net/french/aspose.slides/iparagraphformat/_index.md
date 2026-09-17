---
title: IParagraphFormat class
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/iparagraphformat/
---
## IParagraphFormat classe

Cette classe contient les propriétés de mise en forme de paragraphe. Contrairement à [`IParagraphFormatEffectiveData`](/slides/python-net/fr/aspose.slides/iparagraphformateffectivedata), toutes les propriétés de cette classe sont modifiables.

Le type IParagraphFormat expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`bullet`](/slides/python-net/fr/aspose.slides/iparagraphformat/bullet/) | Renvoie le format de puce du paragraphe.<br/>            Lecture seule [`IBulletFormat`](/slides/python-net/fr/aspose.slides/ibulletformat). |
| [`depth`](/slides/python-net/fr/aspose.slides/iparagraphformat/depth/) | Renvoie ou définit la profondeur du paragraphe.<br/>            La valeur 0 signifie valeur indéfinie.<br/>            Lecture/écriture **int**. |
| [`alignment`](/slides/python-net/fr/aspose.slides/iparagraphformat/alignment/) | Renvoie ou définit l'alignement du texte dans un paragraphe sans héritage.<br/>            Lecture/écriture [`TextAlignment`](/slides/python-net/fr/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/fr/aspose.slides/iparagraphformat/space_within/) | Renvoie ou définit la quantité d'espace entre les lignes de base dans un paragraphe. Une valeur positive signifie un pourcentage, négative - une taille en points. Aucun héritage appliqué.<br/>            Lecture/écriture **float**. |
| [`space_before`](/slides/python-net/fr/aspose.slides/iparagraphformat/space_before/) | Renvoie ou définit la quantité d'espace avant la première ligne dans un paragraphe sans héritage.<br/>            Une valeur positive spécifie le pourcentage de la taille de police que doit occuper l'espace blanc.<br/>            Une valeur négative spécifie la taille de l'espace blanc en points.<br/>            Lecture/écriture **float**. |
| [`space_after`](/slides/python-net/fr/aspose.slides/iparagraphformat/space_after/) | Renvoie ou définit la quantité d'espace après la dernière ligne dans un paragraphe sans héritage.<br/>            Une valeur positive spécifie le pourcentage de la taille de police que doit occuper l'espace blanc.<br/>            Une valeur négative spécifie la taille de l'espace blanc en points.<br/>            Lecture/écriture **float**. |
| [`east_asian_line_break`](/slides/python-net/fr/aspose.slides/iparagraphformat/east_asian_line_break/) | Détermine si le saut de ligne Est-asiatique est utilisé dans un paragraphe. Aucun héritage appliqué.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/fr/aspose.slides/iparagraphformat/right_to_left/) | Détermine si l'écriture de droite à gauche est utilisée dans un paragraphe. Aucun héritage appliqué.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/fr/aspose.slides/iparagraphformat/latin_line_break/) | Détermine si le saut de ligne latin est utilisé dans un paragraphe. Aucun héritage appliqué.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/fr/aspose.slides/iparagraphformat/hanging_punctuation/) | Détermine si la ponctuation en suspension est utilisée dans un paragraphe. Aucun héritage appliqué.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/fr/aspose.slides/iparagraphformat/margin_left/) | Renvoie ou définit la marge gauche dans un paragraphe sans héritage.<br/>            Lecture/écriture **float**. |
| [`margin_right`](/slides/python-net/fr/aspose.slides/iparagraphformat/margin_right/) | Renvoie ou définit la marge droite dans un paragraphe sans héritage.<br/>            Lecture/écriture **float**. |
| [`indent`](/slides/python-net/fr/aspose.slides/iparagraphformat/indent/) | Renvoie ou définit le retrait de la première ligne / retrait suspendu du paragraphe sans héritage. Le retrait suspendu peut être défini avec des valeurs négatives.<br/>            Lecture/écriture **float**. |
| [`default_tab_size`](/slides/python-net/fr/aspose.slides/iparagraphformat/default_tab_size/) | Renvoie ou définit la taille de tabulation par défaut sans héritage.<br/>            Lecture/écriture **float**. |
| [`tabs`](/slides/python-net/fr/aspose.slides/iparagraphformat/tabs/) | Renvoie les tabulations d'un paragraphe. Aucun héritage appliqué.<br/>            Lecture seule [`ITabCollection`](/slides/python-net/fr/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/fr/aspose.slides/iparagraphformat/font_alignment/) | Renvoie ou définit un alignement de police dans un paragraphe sans héritage.<br/>            Lecture/écriture [`FontAlignment`](/slides/python-net/fr/aspose.slides/fontalignment). |
| [`default_portion_format`](/slides/python-net/fr/aspose.slides/iparagraphformat/default_portion_format/) | Renvoie le format de portion par défaut d'un paragraphe. Aucun héritage appliqué.<br/>            Lecture seule [`IPortionFormat`](/slides/python-net/fr/aspose.slides/iportionformat). |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/fr/aspose.slides/iparagraphformat/get_effective/#) | Obtient les données de mise en forme de paragraphe effectives avec l'héritage appliqué. |

### Remarques

Cette classe sert à renvoyer et à manipuler les propriétés de mise en forme de paragraphe définies pour le paragraphe particulier. Cela signifie qu'aucun héritage n'est appliqué lors de la récupération des valeurs, de sorte que, dans la plupart des cas, vous obtiendrez des valeurs signifiant « indéfini ».

Afin d'obtenir les valeurs des paramètres de mise en forme effectifs, y compris ceux hérités, vous devez utiliser la méthode [`IParagraphFormat.get_effective`](/slides/python-net/fr/aspose.slides/iparagraphformat/get_effective) qui renvoie une instance [`IParagraphFormatEffectiveData`](/slides/python-net/fr/aspose.slides/iparagraphformateffectivedata).

### Voir aussi
* classe [`IParagraphFormatEffectiveData`](/slides/python-net/fr/aspose.slides/iparagraphformateffectivedata)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)