---
title: FontsManager
second_title: Aspose.Slides para Android via Referência da API Java
description: Gerencia fontes em toda a apresentação.
type: docs
url: /pt/com.aspose.slides/fontsmanager/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

Gerencia fontes em toda a apresentação.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Carregar apresentação
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Carregar fonte de origem a ser substituída
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
>      // Salvar a apresentação
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Métodos

| Método | Descrição |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Substituições de fonte a serem usadas ao renderizar. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Substituições de fonte a serem usadas ao renderizar. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Representa a coleção de regras FontFallBack de um usuário para gerenciamento de coleções de fontes para substituições adequadas por funcionalidade de fallback Leitura/gravação [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Representa a coleção de regras FontFallBack de um usuário para gerenciamento de coleções de fontes para substituições adequadas por funcionalidade de fallback Leitura/gravação [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Retorna as fontes usadas na apresentação |
| [getSubstitutions()](#getSubstitutions--) | Obtém as informações sobre fontes que serão substituídas na renderização da apresentação. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Obtém as informações sobre fontes que serão substituídas durante a renderização dos slides especificados. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Retorna as fontes incorporadas na apresentação |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Remove a fonte incorporada |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Adiciona a fonte incorporada |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Adiciona a fonte incorporada |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Substitui a fonte na apresentação |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Substitui a fonte na apresentação usando as informações fornecidas em [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Substitui a fonte na apresentação usando as informações fornecidas na coleção de [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Recupera o array de bytes que representa os dados da fonte para um estilo de fonte e dados de fonte especificados. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Determina o nível de incorporação de uma fonte a partir do array de bytes e do nome da fonte fornecidos. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

Substituições de fonte a serem usadas ao renderizar. Leitura/gravação [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Retorna:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Substituições de fonte a serem usadas ao renderizar. Leitura/gravação [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Representa a coleção de regras FontFallBack de um usuário para gerenciamento de coleções de fontes para substituições adequadas por funcionalidade de fallback Leitura/gravação [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Obtendo a coleção de regras vazia ou pré-inicializada do FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // adicionando regras à coleção
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ou 
>      // inicialização de nova instância da coleção de regras
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // adicionando regras à coleção
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // e substituindo a coleção existente pela nova no FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Representa a coleção de regras FontFallBack de um usuário para gerenciamento de coleções de fontes para substituições adequadas por funcionalidade de fallback Leitura/gravação [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Obtendo a coleção de regras vazia ou pré-inicializada do FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // adicionando regras à coleção
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ou 
>      // inicialização de nova instância da coleção de regras
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // adicionando regras à coleção
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // e substituindo a coleção existente pela nova no FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public final IFontData[] getFonts()
```

Retorna as fontes usadas na apresentação

**Retorna:**
com.aspose.slides.IFontData[] - Um array de fontes
### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Obtém as informações sobre fontes que serão substituídas na renderização da apresentação.

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


**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Coleção de todas as substituições de fontes [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Obtém as informações sobre fontes que serão substituídas durante a renderização dos slides especificados.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| slides | int[] | Um array de índices de slides para os quais recuperar informações de substituição de fonte, começando a partir de 1. |

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Uma coleção de todas as substituições de fontes ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) para os slides especificados.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

Retorna as fontes incorporadas na apresentação

**Retorna:**
com.aspose.slides.IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

Remove a fonte incorporada

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Adiciona a fonte incorporada

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Adiciona a fonte incorporada

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

Substitui a fonte na apresentação

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Fonte de origem |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Fonte de destino |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

Substitui a fonte na apresentação usando as informações fornecidas em [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Informações de substituição de fonte |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

Substitui a fonte na apresentação usando as informações fornecidas na coleção de [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Coleção de regras de substituição de fonte |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Recupera o array de bytes que representa os dados da fonte para um estilo de fonte e dados de fonte especificados.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Recuperar todas as fontes usadas na apresentação
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Obter o array de bytes que representa o estilo regular da primeira fonte na apresentação
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | O objeto de dados da fonte que contém as informações sobre a fonte [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | O estilo da fonte para o qual os dados devem ser recuperados [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Retorna:**
byte[] - Um array de bytes contendo os dados da fonte para o estilo de fonte especificado. Se os dados da fonte ou o estilo não forem encontrados, retorna null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Determina o nível de incorporação de uma fonte a partir do array de bytes e do nome da fonte fornecidos.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Recuperar todas as fontes usadas na apresentação
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Obter o array de bytes que representa o estilo regular da primeira fonte na apresentação
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // Determinar o nível de incorporação da fonte
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontBytes | byte[] | O array de bytes contendo os dados da fonte. |
| fontName | java.lang.String | O nome da fonte. |

**Retorna:**
int - O nível de incorporação da fonte especificada.