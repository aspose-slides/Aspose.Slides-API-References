---
title: FontsManager
second_title: Referencia de API de Aspose.Sildes para .NET
description: Gestiona fuentes en toda la presentación.
type: docs
weight: 4960
url: /es/aspose.slides/fontsmanager/
---
## FontsManager clase

Gestiona fuentes en toda la presentación.

```csharp
public class FontsManager : IFontsManager
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [FontFallBackRulesCollection](../../aspose.slides/fontsmanager/fontfallbackrulescollection) { get; set; } | Representa la colección de reglas FontFallBack de un usuario para la gestión de colecciones de fuentes para sustituciones adecuadas mediante la funcionalidad de reserva. Lectura/escritura [`IFontFallBackRulesCollection`](../ifontfallbackrulescollection). |
| [FontSubstRuleList](../../aspose.slides/fontsmanager/fontsubstrulelist) { get; set; } | Sustituciones de fuentes a usar al renderizar. Lectura/escritura [`IFontSubstRuleCollection`](../ifontsubstrulecollection). |
| [PreferRegisteredFontsOverEmbedded](../../aspose.slides/fontsmanager/preferregisteredfontsoverembedded) { get; set; } | Especifica si las fuentes registradas deben tener preferencia sobre las fuentes incrustadas con el mismo nombre y estilo de fuente. Cuando está habilitado, las fuentes incrustadas coincidentes se reemplazan temporalmente por las fuentes registradas correspondientes durante la exportación. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddEmbeddedFont](../../aspose.slides/fontsmanager/addembeddedfont#addembeddedfont_1)(byte[], EmbedFontCharacters) | Añade la fuente incrustada. Tenga en cuenta al copiar cualquier fuente que la mayoría de las fuentes están protegidas por derechos de autor. Primero localice la licencia de una fuente y verifique que pueda transferirse libremente a otra máquina. Se puede lanzar una ArgumentException si los datos de la fuente son nulos o esta fuente ya está incrustada. |
| [AddEmbeddedFont](../../aspose.slides/fontsmanager/addembeddedfont#addembeddedfont)(IFontData, EmbedFontCharacters) | Añade la fuente incrustada. Tenga en cuenta al copiar cualquier fuente que la mayoría de las fuentes están protegidas por derechos de autor. Primero localice la licencia de una fuente y verifique que pueda transferirse libremente a otra máquina. Se puede lanzar una ArgumentException si los datos de la fuente son nulos o esta fuente ya está incrustada. |
| [GetEmbeddedFonts](../../aspose.slides/fontsmanager/getembeddedfonts)() | Devuelve las fuentes incrustadas en la presentación. |
| [GetFontBytes](../../aspose.slides/fontsmanager/getfontbytes)(IFontData, FontStyleType) | Recupera la matriz de bytes que representa los datos de la fuente para un estilo de fuente y datos de fuente especificados. |
| [GetFontEmbeddingLevel](../../aspose.slides/fontsmanager/getfontembeddinglevel)(byte[], string) | Determina el nivel de incrustación de una fuente a partir de la matriz de bytes y el nombre de la fuente proporcionados. |
| [GetFonts](../../aspose.slides/fontsmanager/getfonts)() | Devuelve las fuentes usadas en la presentación. |
| [GetSubstitutions](../../aspose.slides/fontsmanager/getsubstitutions#getsubstitutions)() | Obtiene la información sobre las fuentes que se reemplazarán en la renderización de la presentación. |
| [GetSubstitutions](../../aspose.slides/fontsmanager/getsubstitutions#getsubstitutions_1)(int[]) | Obtiene la información sobre las fuentes que se reemplazarán durante la renderización de las diapositivas especificadas. |
| [RemoveEmbeddedFont](../../aspose.slides/fontsmanager/removeembeddedfont)(IFontData) | Elimina la fuente incrustada. |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont#replacefont_1)(IFontSubstRule) | Reemplaza la fuente en la presentación usando la información proporcionada en [`FontSubstRule`](../fontsubstrule). |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont#replacefont_2)(IFontSubstRuleCollection) | Reemplaza la fuente en la presentación usando la información proporcionada en la colección de [`FontSubstRule`](../fontsubstrule). |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont#replacefont)(IFontData, IFontData) | Reemplaza la fuente en la presentación. |

### Ejemplos

El siguiente ejemplo muestra cómo añadir fuentes incrustadas a una presentación de PowerPoint.

```csharp
[C#]
// Cargar presentación
using (Presentation presentation = new Presentation("Fonts.pptx"))
{
	// Cargar fuente de origen que será reemplazada
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
	// Guardar la presentación
	presentation.Save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
}
```

### Ver también

* interfaz [IFontsManager](../ifontsmanager)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->