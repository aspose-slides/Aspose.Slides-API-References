---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
description: Administra fuentes en toda la presentación.
type: docs
url: /es/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Administra fuentes en toda la presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Sustituciones de fuentes que se utilizan al renderizar Lectura/escritura [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Sustituciones de fuentes que se utilizan al renderizar Lectura/escritura [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Representa la colección del usuario de reglas FontFallBack para la gestión de colecciones de fuentes para sustituciones correctas mediante la funcionalidad de reserva Lectura/escritura [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Representa la colección del usuario de reglas FontFallBack para la gestión de colecciones de fuentes para sustituciones correctas mediante la funcionalidad de reserva Lectura/escritura [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Devuelve las fuentes usadas en la presentación |
| [getSubstitutions()](#getSubstitutions--) | Obtiene la información sobre las fuentes que se reemplazarán en el renderizado de la presentación. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Obtiene la información sobre las fuentes que se reemplazarán durante el renderizado de las diapositivas especificadas. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Devuelve las fuentes incrustadas en la presentación |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Elimina la fuente incrustada |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Añade la fuente incrustada. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Añade la fuente incrustada |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Reemplaza la fuente en la presentación |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Reemplaza la fuente en la presentación usando la información proporcionada en [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Reemplaza la fuente en la presentación usando la información proporcionada en la colección de [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Recupera la matriz de bytes que representa los datos de la fuente para un estilo de fuente y datos de fuente especificados. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Determina el nivel de incrustación de una fuente a partir de la matriz de bytes y el nombre de la fuente proporcionados. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```


Sustituciones de fuentes que se utilizan al renderizar Lectura/escritura [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Valor devuelto:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```


Sustituciones de fuentes que se utilizan al renderizar Lectura/escritura [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```


Representa la colección del usuario de reglas FontFallBack para la gestión de colecciones de fuentes para sustituciones correctas mediante la funcionalidad de reserva Lectura/escritura [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Obtención de la colección de reglas vacía o preinicializada desde FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // añadido de reglas a la colección
>      // o 
>      // inicialización de una nueva instancia de la colección de reglas
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // añadido de reglas a la colección
>      // y reemplazo de la colección existente por la nueva en FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Valor devuelto:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```


Representa la colección del usuario de reglas FontFallBack para la gestión de colecciones de fuentes para sustituciones correctas mediante la funcionalidad de reserva Lectura/escritura [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Obtención de la colección de reglas vacía o preinicializada de FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // añadiendo reglas a la colección
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // o 
>      // inicialización de una nueva instancia de la colección de reglas
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // añadiendo reglas a la colección
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // y reemplazo de la colección existente por la nueva en FontsManager 
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
public abstract IFontData[] getFonts()
```


Devuelve las fuentes usadas en la presentación

**Valor devuelto:**
com.aspose.slides.IFontData[] - Una matriz de fuentes
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```


Obtiene la información sobre las fuentes que se reemplazarán en el renderizado de la presentación.

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


**Valor devuelto:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Colección de todas las sustituciones de fuentes [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```


Obtiene la información sobre las fuentes que se reemplazarán durante el renderizado de las diapositivas especificadas.

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
| slides | int[] | Una matriz de índices de diapositivas para los que se debe recuperar la información de sustitución de fuentes, comenzando desde 1. |

**Valor devuelto:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Una colección de todas las sustituciones de fuentes ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) para las diapositivas especificadas.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```


Devuelve las fuentes incrustadas en la presentación

**Valor devuelto:**
com.aspose.slides.IFontData[] - Fuentes incrustadas IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```


Elimina la fuente incrustada

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Objeto de datos de fuente [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```


Añade la fuente incrustada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Objeto de datos de fuente [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Regla de fuente incrustada [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Tenga en cuenta que al copiar cualquier fuente, la mayoría de las fuentes están protegidas por derechos de autor. Primero localice la licencia de la fuente y verifique que pueda transferirse libremente a otra máquina. |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```


Añade la fuente incrustada

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontData | byte[] | Datos de la fuente  byte[]  |
| embedFontRule | int | Regla de fuente incrustada [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Tenga en cuenta que al añadir cualquier fuente, la mayoría de las fuentes están protegidas por derechos de autor. Primero localice la licencia de la fuente y verifique que pueda transferirse libremente a otra máquina. |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```


Reemplaza la fuente en la presentación

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Fuente de origen |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Fuente de destino |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```


Reemplaza la fuente en la presentación usando la información proporcionada en [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Información de sustitución de fuente |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```


Reemplaza la fuente en la presentación usando la información proporcionada en la colección de [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Colección de información de sustitución de fuentes |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```


Recupera la matriz de bytes que representa los datos de la fuente para un estilo de fuente y datos de fuente especificados.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Recuperar todas las fuentes usadas en la presentación
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Obtener la matriz de bytes que representa el estilo regular de la primera fuente en la presentación
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | El objeto de datos de fuente que contiene la información sobre la fuente [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | El estilo de la fuente para el que se deben recuperar los datos [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Valor devuelto:**
byte[] - Una matriz de bytes que contiene los datos de la fuente para el estilo especificado. Si no se encuentran los datos o el estilo de la fuente, se devuelve null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```


Determina el nivel de incrustación de una fuente a partir de la matriz de bytes y el nombre de la fuente proporcionados.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Recuperar todas las fuentes usadas en la presentación
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Obtener la matriz de bytes que representa el estilo regular de la primera fuente en la presentación
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Determinar el nivel de incrustación de la fuente
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontBytes | byte[] | La matriz de bytes que contiene los datos de la fuente. |
| fontName | java.lang.String | El nombre de la fuente. |

**Valor devuelto:**
int - El nivel de incrustación de la fuente especificada.