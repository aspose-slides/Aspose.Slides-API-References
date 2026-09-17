---
title: ParagraphFormat class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/paragraphformat/
---
## ParagraphFormat classe

Cette classe contient les propriétés de mise en forme des paragraphes. Contrairement à [`IParagraphFormatEffectiveData`](/slides/python-net/fr/aspose.slides/iparagraphformateffectivedata), toutes les propriétés de cette classe sont modifiables.

**Héritage:**[`ParagraphFormat`](/slides/python-net/fr/aspose.slides/paragraphformat) → [`PVIObject`](/slides/python-net/fr/aspose.slides/pviobject)

Le type ParagraphFormat expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides/paragraphformat/__init__/#) | Initialise une nouvelle instance de la classe [`ParagraphFormat`](/slides/python-net/fr/aspose.slides/paragraphformat). |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`alignment`](/slides/python-net/fr/aspose.slides/paragraphformat/alignment/) | Retourne ou définit l'alignement du texte dans un paragraphe sans héritage.<br/>            Lecture/écriture [`TextAlignment`](/slides/python-net/fr/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/fr/aspose.slides/paragraphformat/space_within/) | Retourne ou définit la quantité d'espace entre les lignes de base dans un paragraphe. Une valeur positive signifie pourcentage, une valeur négative - taille en points. Aucun héritage appliqué.<br/>            Lecture/écriture **float**. |
| [`space_before`](/slides/python-net/fr/aspose.slides/paragraphformat/space_before/) | Retourne ou définit la quantité d'espace avant la première ligne dans un paragraphe sans héritage.<br/>            Une valeur positive indique le pourcentage de la taille de la police que doit occuper l'espace blanc.<br/>            Une valeur négative indique la taille de l'espace blanc en points.<br/>            Lecture/écriture **float**. |
| [`space_after`](/slides/python-net/fr/aspose.slides/paragraphformat/space_after/) | Retourne ou définit la quantité d'espace après la dernière ligne dans un paragraphe sans héritage.<br/>            Une valeur positive indique le pourcentage de la taille de la police que doit occuper l'espace blanc.<br/>            Une valeur négative indique la taille de l'espace blanc en points.<br/>            Lecture/écriture **float**. |
| [`east_asian_line_break`](/slides/python-net/fr/aspose.slides/paragraphformat/east_asian_line_break/) | Détermine si le saut de ligne est-asiatique est utilisé dans un paragraphe. Aucun héritage appliqué.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/fr/aspose.slides/paragraphformat/right_to_left/) | Détermine si l'écriture de droite à gauche est utilisée dans un paragraphe. Aucun héritage appliqué.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/fr/aspose.slides/paragraphformat/latin_line_break/) | Détermine si le saut de ligne latin est utilisé dans un paragraphe. Aucun héritage appliqué.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/fr/aspose.slides/paragraphformat/hanging_punctuation/) | Détermine si la ponctuation suspendue est utilisée dans un paragraphe. Aucun héritage appliqué.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/fr/aspose.slides/paragraphformat/margin_left/) | Retourne ou définit la marge gauche dans un paragraphe sans héritage.<br/>            Lecture/écriture **float**. |
| [`margin_right`](/slides/python-net/fr/aspose.slides/paragraphformat/margin_right/) | Retourne ou définit la marge droite dans un paragraphe sans héritage.<br/>            Lecture/écriture **float**. |
| [`indent`](/slides/python-net/fr/aspose.slides/paragraphformat/indent/) | Retourne ou définit le retrait de première ligne / retrait suspendu du paragraphe sans héritage. Le retrait suspendu peut être défini avec des valeurs négatives.<br/>            Lecture/écriture **float**. |
| [`default_tab_size`](/slides/python-net/fr/aspose.slides/paragraphformat/default_tab_size/) | Retourne ou définit la taille de tabulation par défaut sans héritage.<br/>            Lecture/écriture **float**. |
| [`tabs`](/slides/python-net/fr/aspose.slides/paragraphformat/tabs/) | Retourne les tabulations d'un paragraphe. Aucun héritage appliqué.<br/>            Lecture seule [`ITabCollection`](/slides/python-net/fr/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/fr/aspose.slides/paragraphformat/font_alignment/) | Retourne ou définit l'alignement de police dans un paragraphe sans héritage.<br/>            Lecture/écriture [`FontAlignment`](/slides/python-net/fr/aspose.slides/fontalignment). |
| [`slide`](/slides/python-net/fr/aspose.slides/paragraphformat/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides/paragraphformat/presentation/) |  |
| [`bullet`](/slides/python-net/fr/aspose.slides/paragraphformat/bullet/) |  |
| [`depth`](/slides/python-net/fr/aspose.slides/paragraphformat/depth/) |  |
| [`default_portion_format`](/slides/python-net/fr/aspose.slides/paragraphformat/default_portion_format/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/fr/aspose.slides/paragraphformat/get_effective/#) | Obtient les données effectives de mise en forme du paragraphe avec l'héritage appliqué. |


### Remarques

Cette classe est utilisée pour retourner et manipuler les propriétés de mise en forme des paragraphes définies pour un paragraphe particulier. Cela signifie qu'aucun héritage n'est appliqué lors de la récupération des valeurs, de sorte que dans la plupart des cas vous obtiendrez des valeurs signifiant « indéfini ».

Afin d'obtenir les valeurs effectives des paramètres de mise en forme, y compris ceux hérités, vous devez utiliser la méthode [`ParagraphFormat.get_effective`](/slides/python-net/fr/aspose.slides/paragraphformat/get_effective) qui retourne une instance [`IParagraphFormatEffectiveData`](/slides/python-net/fr/aspose.slides/iparagraphformateffectivedata).


### Voir aussi
* classe [`IParagraphFormatEffectiveData`](/slides/python-net/fr/aspose.slides/iparagraphformateffectivedata)
* classe [`ParagraphFormat`](/slides/python-net/fr/aspose.slides/paragraphformat)
* classe [`PVIObject`](/slides/python-net/fr/aspose.slides/pviobject)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)