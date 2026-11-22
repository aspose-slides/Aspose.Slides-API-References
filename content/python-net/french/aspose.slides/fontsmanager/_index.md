---
title: FontsManager class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/fontsmanager/
---
## FontsManager classe

Gère les polices sur l’ensemble de la présentation.

Le type FontsManager expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/fr/aspose.slides/fontsmanager/font_subst_rule_list/) | Substitutions de polices à utiliser lors du rendu.<br/>            Lire/écrire [`IFontSubstRuleCollection`](/slides/python-net/fr/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/fr/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Représente la collection d’un utilisateur de règles FontFallBack pour gérer les collections de polices afin d’assurer les substitutions appropriées via la fonctionnalité de secours.<br/>            Lire/écrire [`IFontFallBackRulesCollection`](/slides/python-net/fr/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/fr/aspose.slides/fontsmanager/prefer_registered_fonts_over_embedded/) | Spécifie si les polices enregistrées doivent être privilégiées par rapport aux polices intégrées portant le même nom et le même style.<br/>            Lorsqu’elle est activée, les polices intégrées correspondantes sont temporairement remplacées par les polices enregistrées correspondantes lors de l’exportation. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/fr/aspose.slides/fontsmanager/get_substitutions/#) | Obtient les informations sur les polices qui seront remplacées lors du rendu de la présentation. |
| [`get_substitutions(self, slides)`](/slides/python-net/fr/aspose.slides/fontsmanager/get_substitutions/#listint) | Obtient les informations sur les polices qui seront remplacées lors du rendu des diapositives spécifiées. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/fr/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Ajoute la police intégrée<br/>            Gardez à l\'esprit, lors de la copie de toute police, que la plupart des polices sont protégées par le droit d\'auteur. Commencez par localiser la licence d\'une police à l\'avance et vérifiez qu\'elle peut être librement transférée vers une autre machine. Une ArgumentException peut être levée si les données de la police sont null ou si cette police est déjà intégrée |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/fr/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Ajoute la police intégrée<br/>            Gardez à l\'esprit, lors de la copie de toute police, que la plupart des polices sont protégées par le droit d\'auteur. Commencez par localiser la licence d\'une police à l\'avance et vérifiez qu\'elle peut être librement transférée vers une autre machine. Une ArgumentException peut être levée si les données de la police sont null ou si cette police est déjà intégrée |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/fr/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Remplace la police dans la présentation |
| [`replace_font(self, subst_rule)`](/slides/python-net/fr/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Remplace la police dans la présentation en utilisant les informations fournies dans [`FontSubstRule`](/slides/python-net/fr/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/fr/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Remplace la police dans la présentation en utilisant les informations fournies dans la collection de [`FontSubstRule`](/slides/python-net/fr/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/fr/aspose.slides/fontsmanager/get_fonts/#) | Renvoie les polices utilisées dans la présentation |
| [`get_embedded_fonts(self)`](/slides/python-net/fr/aspose.slides/fontsmanager/get_embedded_fonts/#) | Renvoie les polices intégrées dans la présentation |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/fr/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Supprime la police intégrée |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/fr/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Récupère le tableau d’octets représentant les données de police pour un style de police et des données de police spécifiés. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/fr/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Détermine le niveau d’intégration d’une police à partir du tableau d’octets et du nom de police fournis. |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)