---
title: IFontsManager
second_title: Aspose.Slides para Java Referência da API
description: Gerencia fontes em toda a apresentação.
type: docs
url: /pt/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Gerencia fontes em toda a apresentação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Substituições de fonte a serem usadas ao renderizar Leitura/gravação [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Substituições de fonte a serem usadas ao renderizar Leitura/gravação [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Representa a coleção de regras FontFallBack de um usuário para gerenciamento de coleções de fontes para substituições adequadas pela funcionalidade de fallback Leitura/gravação [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Representa a coleção de regras FontFallBack de um usuário para gerenciamento de coleções de fontes para substituições adequadas pela funcionalidade de fallback Leitura/gravação [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Retorna as fontes usadas na apresentação |
| [getSubstitutions()](#getSubstitutions--) | Obtém as informações sobre fontes que serão substituídas na renderização da apresentação. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Obtém as informações sobre fontes que serão substituídas durante a renderização dos slides especificados. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Retorna as fontes incorporadas na apresentação |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Remove a fonte incorporada |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Adiciona a fonte incorporada. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Adiciona a fonte incorporada |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Substitui fonte na apresentação |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Substitui fonte na apresentação usando informações fornecidas em [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Substitui fonte na apresentação usando informações fornecidas na coleção de [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Recupera o array de bytes que representa os dados da fonte para um estilo de fonte e dados de fonte especificados. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Determina o nível de incorporação de uma fonte a partir do array de bytes e do nome da fonte fornecidos. |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | Especifica se fontes registradas devem ter prioridade sobre fontes incorporadas com o mesmo nome e estilo. |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | Especifica se fontes registradas devem ter prioridade sobre fontes incorporadas com o mesmo nome e estilo. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

Substituições de fonte a serem usadas ao renderizar Leitura/gravação [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Retorna:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Substituições de fonte a serem usadas ao renderizar Leitura/gravação [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Representa a coleção de regras FontFallBack de um usuário para gerenciamento de coleções de fontes para substituições adequadas pela funcionalidade de fallback Leitura/gravação [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Obtendo a coleção vazia ou pré-inicializada de regras do FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // Adicionando regras à coleção
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ou
>      // inicialização de nova instância da coleção de regras
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // Adicionando regras à coleção
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // e substituição da coleção existente pela nova no FontsManager 
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
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Representa a coleção de regras FontFallBack de um usuário para gerenciamento de coleções de fontes para substituições adequadas pela funcionalidade de fallback Leitura/gravação [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Obtendo a coleção vazia ou pré-inicializada de regras do FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // Adicionando regras à coleção
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ou
>      // inicialização de nova instância da coleção de regras
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // Adicionando regras à coleção
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
public abstract IFontData[] getFonts()
```

Retorna as fontes usadas na apresentação

**Retorna:**
com.aspose.slides.IFontData[] - Um array de fontes
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Coleção de todas as substituições de fonte [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
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
| slides | int[] | Um array de índices de slides para os quais recuperar informações de substituição de fonte, começando em 1. |

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Uma coleção de todas as substituições de fonte ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) para os slides especificados.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

Retorna as fontes incorporadas na apresentação

**Retorna:**
com.aspose.slides.IFontData[] - Fontes incorporadas IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

Remove a fonte incorporada

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Objeto de dados da fonte [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Adiciona a fonte incorporada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Objeto de dados da fonte [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Regra de fonte incorporada [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Mantenha em mente ao copiar quaisquer fontes que a maioria das fontes é protegida por direitos autorais. Primeiro localize a licença de uma fonte e verifique se ela pode ser transferida livremente para outra máquina. |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Adiciona a fonte incorporada

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontData | byte[] | Dados da fonte  byte[]  |
| embedFontRule | int | Regra de fonte incorporada [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Mantenha em mente ao adicionar quaisquer fontes que a maioria das fontes é protegida por direitos autorais. Primeiro localize a licença de uma fonte e verifique se ela pode ser transferida livremente para outra máquina. |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

Substitui fonte na apresentação

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Fonte de origem |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Fonte de destino |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

Substitui fonte na apresentação usando informações fornecidas em [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Informações de substituição de fonte |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Substitui fonte na apresentação usando informações fornecidas na coleção de [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Coleção de informações de substituição de fonte |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
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
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | O objeto de dados da fonte contendo as informações sobre a fonte [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | O estilo da fonte para o qual os dados devem ser recuperados [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Retorna:**
byte[] - Um array de bytes contendo os dados da fonte para o estilo especificado. Se os dados da fonte ou o estilo não forem encontrados, retorna nulo.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Determina o nível de incorporação de uma fonte a partir do array de bytes e do nome da fonte fornecidos.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Recuperar todas as fontes usadas na apresentação
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Obter o array de bytes que representa o estilo regular da primeira fonte na apresentação
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
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
### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public abstract boolean getPreferRegisteredFontsOverEmbedded()
```

Especifica se fontes registradas devem ter prioridade sobre fontes incorporadas com o mesmo nome e estilo. Quando habilitado, fontes incorporadas correspondentes são temporariamente substituídas por fontes registradas correspondentes durante a exportação.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      pres.getFontsManager().setPreferRegisteredFontsOverEmbedded(true);
>      pres.save("Presentation-out.pdf", SaveFormat.Pdf);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

O padrão é **false** .

**Retorna:**
boolean
### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public abstract void setPreferRegisteredFontsOverEmbedded(boolean value)
```

Especifica se fontes registradas devem ter prioridade sobre fontes incorporadas com o mesmo nome e estilo. Quando habilitado, fontes incorporadas correspondentes são temporariamente substituídas por fontes registradas correspondentes durante a exportação.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      pres.getFontsManager().setPreferRegisteredFontsOverEmbedded(true);
>      pres.save("Presentation-out.pdf", SaveFormat.Pdf);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

O padrão é **false** .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |