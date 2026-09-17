---
title: IFontsManager class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ifontsmanager/
---
## IFontsManager classe

Gère les polices dans la présentation.

Le type IFontsManager expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/fr/aspose.slides/ifontsmanager/font_subst_rule_list/) | Substitutions de polices à utiliser lors du rendu<br/>            Lecture/écriture [`IFontSubstRuleCollection`](/slides/python-net/fr/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/fr/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Représente la collection d'un utilisateur des règles FontFallBack pour gérer des collections de polices afin d'assurer des substitutions appropriées grâce à la fonctionnalité de secours<br/>            Lecture/écriture [`IFontFallBackRulesCollection`](/slides/python-net/fr/aspose.slides/ifontfallbackrulescollection). |

## Méthodes

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/fr/aspose.slides/ifontsmanager/get_substitutions/#) | Obtient les informations sur les polices qui seront remplacées lors du rendu de la présentation. |
| [`get_substitutions(self, slides)`](/slides/python-net/fr/aspose.slides/ifontsmanager/get_substitutions/#listint) | Obtient les informations sur les polices qui seront remplacées lors du rendu des diapositives spécifiées. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/fr/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Ajoute la police intégrée.<br/>            Gardez à l'esprit que la plupart des polices sont protégées par des droits d'auteur lors de la copie. Localisez d'abord la licence d'une police à l'avance et vérifiez qu'elle peut être librement transférée vers une autre machine. Une ArgumentException peut être levée si les données de la police sont nulles ou si cette police est déjà intégrée |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/fr/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Ajoute la police intégrée<br/>            Gardez à l'esprit que la plupart des polices sont protégées par des droits d'auteur lors de l'ajout. Localisez d'abord la licence d'une police à l'avance et vérifiez qu'elle peut être librement transférée vers une autre machine. Une ArgumentException peut être levée si les données de la police sont nulles ou si cette police est déjà intégrée |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/fr/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Remplace la police dans la présentation |
| [`replace_font(self, subst_rule)`](/slides/python-net/fr/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Remplace la police dans la présentation en utilisant les informations fournies dans [`IFontSubstRule`](/slides/python-net/fr/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/fr/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Remplace la police dans la présentation en utilisant les informations fournies dans la collection de [`IFontSubstRule`](/slides/python-net/fr/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/fr/aspose.slides/ifontsmanager/get_fonts/#) | Renvoie les polices utilisées dans la présentation |
| [`get_embedded_fonts(self)`](/slides/python-net/fr/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Renvoie les polices intégrées dans la présentation |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/fr/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Supprime la police intégrée |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/fr/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Récupère le tableau d'octets représentant les données de la police pour un style de police spécifié et les données de la police. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/fr/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Détermine le niveau d'intégration d'une police à partir du tableau d'octets fourni et du nom de la police. |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)