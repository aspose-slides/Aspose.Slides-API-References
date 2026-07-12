---
title: FontsManager
second_title: Aspose.Slides para Android vía referencia de API Java
description: Gestiona fuentes en toda la presentación.
type: docs
url: /es/com.aspose.slides/fontsmanager/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

Gestiona fuentes en toda la presentación.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Cargar presentación
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Cargar la fuente a reemplazar
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // Guardar la presentación
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Métodos

| Método | Descripción |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Sustituciones de fuentes a usar durante la renderización. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Sustituciones de fuentes a usar durante la renderización. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Representa la colección de reglas FontFallBack de un usuario para gestionar colecciones de fuentes para sustituciones correctas mediante la funcionalidad de reserva. Lectura/escritura [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Representa la colección de reglas FontFallBack de un usuario para gestionar colecciones de fuentes para sustituciones correctas mediante la funcionalidad de reserva. Lectura/escritura [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Devuelve las fuentes usadas en la presentación. |
| [getSubstitutions()](#getSubstitutions--) | Obtiene la información sobre las fuentes que serán reemplazadas en la renderización de la presentación. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Obtiene la información sobre las fuentes que serán reemplazadas durante la renderización de las diapositivas especificadas. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Devuelve las fuentes incrustadas en la presentación. |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Elimina la fuente incrustada. |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Agrega la fuente incrustada. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Agrega la fuente incrustada. |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Reemplaza la fuente en la presentación. |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Reemplaza la fuente en la presentación usando la información proporcionada en [FontSubstRule](../../com.aspose.slides/fontsubstrule). |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Reemplaza la fuente en la presentación usando la información proporcionada en la colección de [FontSubstRule](../../com.aspose.slides/fontsubstrule). |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Recupera el arreglo de bytes que representa los datos de la fuente para un estilo de fuente y datos de fuente especificados. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Determina el nivel de incrustación de una fuente a partir del arreglo de bytes y el nombre de la fuente proporcionados. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```


Sustituciones de fuentes a usar durante la renderización. Lectura/escritura [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Devuelve:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```


Sustituciones de fuentes a usar durante la renderización. Lectura/escritura [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```


Representa la colección de reglas FontFallBack de un usuario para gestionar colecciones de fuentes para sustituciones correctas mediante la funcionalidad de reserva. Lectura/escritura [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Obteniendo la colección de reglas vacía o preinicializada del FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // agregando reglas a la colección
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // o
>      // inicialización de una nueva instancia de la colección de reglas
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // agregando reglas a la colección
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // y reemplazando la colección existente por la nueva en FontsManager
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```


Representa la colección de reglas FontFallBack de un usuario para gestionar colecciones de fuentes para sustituciones correctas mediante la funcionalidad de reserva. Lectura/escritura [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Obteniendo la colección de reglas vacía o preinicializada del FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // agregando reglas a la colección
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // o
>      // inicialización de una nueva instancia de la colección de reglas
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // agregando reglas a la colección
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // y reemplazando la colección existente por la nueva en FontsManager
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public final IFontData[] getFonts()
```


Devuelve las fuentes usadas en la presentación

**Devuelve:**
com.aspose.slides.IFontData[] - Una matriz de fuentes
### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```


Obtiene la información sobre las fuentes que serán reemplazadas en la renderización de la presentación.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions())
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Colección de todas las sustituciones de fuentes [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```


Obtiene la información sobre las fuentes que serán reemplazadas durante la renderización de las diapositivas especificadas.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      int[] targetSlides = { 1, 2, 5 };
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions(targetSlides))
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slides | int[] | Una matriz de índices de diapositivas para los que se debe obtener la información de sustitución de fuentes, comenzando desde 1. |

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Una colección de todas las sustituciones de fuentes ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) para las diapositivas especificadas.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```


Devuelve las fuentes incrustadas en la presentación

**Devuelve:**
com.aspose.slides.IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```


Elimina la fuente incrustada

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```


Agrega la fuente incrustada

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```


Agrega la fuente incrustada

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```


Reemplaza la fuente en la presentación

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Fuente origen |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Fuente destino |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```


Reemplaza la fuente en la presentación usando la información proporcionada en [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Información de sustitución de fuente |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```


Reemplaza la fuente en la presentación usando la información proporcionada en la colección de [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Colección de reglas de sustitución de fuentes |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```


Recupera el arreglo de bytes que representa los datos de la fuente para un estilo de fuente y datos especificados.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Obtiene todas las fuentes usadas en la presentación
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Obtiene el arreglo de bytes que representa el estilo regular de la primera fuente en la presentación
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | El objeto de datos de fuente que contiene la información sobre la fuente [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | El estilo de la fuente para el cual se deben recuperar los datos [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Devuelve:**
byte[] - Un arreglo de bytes que contiene los datos de la fuente para el estilo especificado. Si los datos de la fuente o el estilo no se encuentran, devuelve null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```


Determina el nivel de incrustación de una fuente a partir del arreglo de bytes y el nombre de la fuente proporcionados.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Obtiene todas las fuentes usadas en la presentación
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Obtiene el arreglo de bytes que representa el estilo regular de la primera fuente en la presentación
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // Determina el nivel de incrustación de la fuente
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontBytes | byte[] | El arreglo de bytes que contiene los datos de la fuente. |
| fontName | java.lang.String | El nombre de la fuente. |

**Devuelve:**
int - El nivel de incrustación de la fuente especificada.