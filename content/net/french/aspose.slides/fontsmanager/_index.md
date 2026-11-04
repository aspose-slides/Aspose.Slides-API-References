---
title: FontsManager
second_title: Référence API Aspose.Sildes pour .NET
description: Gère les polices dans la présentation.
type: docs
weight: 4960
url: /fr/aspose.slides/fontsmanager/
---
## FontsManager classe

Gère les polices dans la présentation.

```csharp
public class FontsManager : IFontsManager
```

## Propriétés

| Nom | Description |
| --- | --- |
| [FontFallBackRulesCollection](../../aspose.slides/fontsmanager/fontfallbackrulescollection) { get; set; } | Représente la collection d'un utilisateur de règles FontFallBack pour la gestion de collections de polices afin d'assurer des substitutions appropriées grâce à la fonctionnalité de repli. Lecture/écriture [`IFontFallBackRulesCollection`](../ifontfallbackrulescollection). |
| [FontSubstRuleList](../../aspose.slides/fontsmanager/fontsubstrulelist) { get; set; } | Substitutions de polices à utiliser lors du rendu. Lecture/écriture [`IFontSubstRuleCollection`](../ifontsubstrulecollection). |
| [PreferRegisteredFontsOverEmbedded](../../aspose.slides/fontsmanager/preferregisteredfontsoverembedded) { get; set; } | Spécifie si les polices enregistrées doivent être privilégiées par rapport aux polices incorporées portant le même nom et style. Lorsqu'elle est activée, les polices incorporées correspondantes sont temporairement remplacées par les polices enregistrées correspondantes lors de l'exportation. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddEmbeddedFont](../../aspose.slides/fontsmanager/addembeddedfont#addembeddedfont_1)(byte[], EmbedFontCharacters) | Ajoute la police incorporée. Gardez à l'esprit que la plupart des polices sont protégées par le droit d'auteur lors de la copie. Localisez d'abord la licence d'une police et vérifiez qu'elle peut être transférée librement vers une autre machine. Une ArgumentException peut être levée si les données de la police sont null ou si cette police est déjà incorporée |
| [AddEmbeddedFont](../../aspose.slides/fontsmanager/addembeddedfont#addembeddedfont)(IFontData, EmbedFontCharacters) | Ajoute la police incorporée. Gardez à l'esprit que la plupart des polices sont protégées par le droit d'auteur lors de la copie. Localisez d'abord la licence d'une police et vérifiez qu'elle peut être transférée librement vers une autre machine. Une ArgumentException peut être levée si les données de la police sont null ou si cette police est déjà incorporée |
| [GetEmbeddedFonts](../../aspose.slides/fontsmanager/getembeddedfonts)() | Renvoie les polices incorporées dans la présentation |
| [GetFontBytes](../../aspose.slides/fontsmanager/getfontbytes)(IFontData, FontStyleType) | Récupère le tableau d'octets représentant les données de police pour un style de police et des données de police spécifiés. |
| [GetFontEmbeddingLevel](../../aspose.slides/fontsmanager/getfontembeddinglevel)(byte[], string) | Détermine le niveau d'incorporation d'une police à partir du tableau d'octets et du nom de police fournis. |
| [GetFonts](../../aspose.slides/fontsmanager/getfonts)() | Renvoie les polices utilisées dans la présentation |
| [GetSubstitutions](../../aspose.slides/fontsmanager/getsubstitutions#getsubstitutions)() | Obtient les informations sur les polices qui seront remplacées lors du rendu de la présentation. |
| [GetSubstitutions](../../aspose.slides/fontsmanager/getsubstitutions#getsubstitutions_1)(int[]) | Obtient les informations sur les polices qui seront remplacées lors du rendu des diapositives spécifiées. |
| [RemoveEmbeddedFont](../../aspose.slides/fontsmanager/removeembeddedfont)(IFontData) | Supprime la police incorporée |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont#replacefont_1)(IFontSubstRule) | Remplace la police dans la présentation à l'aide des informations fournies dans [`FontSubstRule`](../fontsubstrule) |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont#replacefont_2)(IFontSubstRuleCollection) | Remplace la police dans la présentation à l'aide des informations fournies dans la collection de [`FontSubstRule`](../fontsubstrule) |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont#replacefont)(IFontData, IFontData) | Remplace la police dans la présentation |

### Exemples

L'exemple suivant montre comment ajouter des polices incorporées à une présentation PowerPoint.

```csharp
[C#]
// Charger la présentation
using (Presentation presentation = new Presentation("Fonts.pptx"))
{
	// Charger la police source à remplacer
	IFontData sourceFont = new FontData("Arial");
	IFontData[] allFonts = presentation.FontsManager.GetFonts();
	IFontData[] embeddedFonts = presentation.FontsManager.GetEmbeddedFonts();
	foreach (IFontData font in allFonts)
	{
		if (!embeddedFonts.Contains(font))
		{
			presentation.FontsManager.AddEmbeddedFont(font, EmbedFontCharacters.All);
		}
	}
	// Enregistrer la présentation
	presentation.Save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
}
```

### Voir aussi

* interface [IFontsManager](../ifontsmanager)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->