---
title: FontsManager class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/fontsmanager/
---
## FontsManager classe

Gère les polices de la présentation.

Le type FontsManager expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/fr/aspose.slides/fontsmanager/font_subst_rule_list/) | Substitutions de police à utiliser lors du rendu.<br/>            Lecture/écriture [`IFontSubstRuleCollection`](/slides/python-net/fr/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/fr/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Représente la collection d'un utilisateur de règles FontFallBack pour la gestion de collections de polices afin d'effectuer les substitutions appropriées grâce à la fonctionnalité de secours.<br/>            Lecture/écriture [`IFontFallBackRulesCollection`](/slides/python-net/fr/aspose.slides/ifontfallbackrulescollection). |

## Méthodes

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/fr/aspose.slides/fontsmanager/get_substitutions/#) | Obtient les informations sur les polices qui seront remplacées lors du rendu de la présentation. |
| [`get_substitutions(self, slides)`](/slides/python-net/fr/aspose.slides/fontsmanager/get_substitutions/#listint) | Obtient les informations sur les polices qui seront remplacées lors du rendu des diapositives spécifiées. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/fr/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Ajoute la police incorporée<br/>            Gardez à l'esprit que lors de la copie de toute police, la plupart sont protégées par des droits d'auteur. Localisez d'abord la licence d'<br/>            une police au préalable et vérifiez qu'elle peut être librement transférée à une autre machine. Une ArgumentException peut être levée si les données de police sont None ou si cette police est déjà incorporée |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/fr/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Ajoute la police incorporée<br/>            Gardez à l'esprit que lors de la copie de toute police, la plupart sont protégées par des droits d'auteur. Localisez d'abord la licence d'<br/>            une police au préalable et vérifiez qu'elle peut être librement transférée à une autre machine. Une ArgumentException peut être levée si les données de police sont None ou si cette police est déjà incorporée |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/fr/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Remplace la police dans la présentation |
| [`replace_font(self, subst_rule)`](/slides/python-net/fr/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Remplace la police dans la présentation en utilisant les informations fournies dans [`FontSubstRule`](/slides/python-net/fr/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/fr/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Remplace la police dans la présentation en utilisant les informations fournies dans la collection de [`FontSubstRule`](/slides/python-net/fr/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/fr/aspose.slides/fontsmanager/get_fonts/#) | Renvoie les polices utilisées dans la présentation |
| [`get_embedded_fonts(self)`](/slides/python-net/fr/aspose.slides/fontsmanager/get_embedded_fonts/#) | Renvoie les polices incorporées dans la présentation |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/fr/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Supprime la police incorporée |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/fr/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Récupère le tableau d'octets représentant les données de police pour un style de police spécifié et les données de police. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/fr/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Détermine le niveau d'incorporation d'une police à partir du tableau d'octets fourni et du nom de la police. |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)