---
title: ILoadOptions
second_title: Aspose.Slides para Android via Referência de API Java
description: Permite especificar opções adicionais, como formato ou fonte padrão, ao carregar uma apresentação.
type: docs
url: /pt/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Permite especificar opções adicionais (como formato ou fonte padrão) ao carregar uma apresentação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Retorna ou define o formato de uma apresentação a ser carregada. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Retorna ou define o formato de uma apresentação a ser carregada. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Retorna ou define a fonte Regular usada caso a fonte de origem não seja encontrada. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Retorna ou define a fonte Regular usada caso a fonte de origem não seja encontrada. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Retorna ou define a fonte Symbol usada caso a fonte de origem não seja encontrada. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Retorna ou define a fonte Symbol usada caso a fonte de origem não seja encontrada. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Retorna ou define a fonte Asian usada caso a fonte de origem não seja encontrada. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Retorna ou define a fonte Asian usada caso a fonte de origem não seja encontrada. |
| [getPassword()](#getPassword--) | Obtém ou define a senha. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Obtém ou define a senha. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Esta propriedade faz sentido se o arquivo de apresentação estiver protegido por senha. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Esta propriedade faz sentido se o arquivo de apresentação estiver protegido por senha. |
| [getWarningCallback()](#getWarningCallback--) | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Representa as opções que podem ser usadas para gerenciar o comportamento de manipulação de Binary Large Objects (BLOBs), como uso de arquivos temporários ou máximo de bytes BLOBs na memória. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Representa as opções que podem ser usadas para gerenciar o comportamento de manipulação de Binary Large Objects (BLOBs), como uso de arquivos temporários ou máximo de bytes BLOBs na memória. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Especifica fontes externas a serem usadas pela apresentação. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Especifica fontes externas a serem usadas pela apresentação. |
| [getInterruptionToken()](#getInterruptionToken--) | O token para monitorar solicitações de interrupção. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | O token para monitorar solicitações de interrupção. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Retorna ou define a interface de callback que gerencia o carregamento de recursos externos. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Retorna ou define a interface de callback que gerencia o carregamento de recursos externos. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Representa opções que podem ser usadas para especificar comportamento adicional de planilhas. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Representa opções que podem ser usadas para especificar comportamento adicional de planilhas. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Retorna ou define o idioma padrão para o texto da apresentação. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Retorna ou define o idioma padrão para o texto da apresentação. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Determina se o Aspose.Slides excluirá todos os objetos binários incorporados ao carregar a apresentação. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Determina se o Aspose.Slides excluirá todos os objetos binários incorporados ao carregar a apresentação. |
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Retorna ou define o formato de uma apresentação a ser carregada. Leitura/gravação [LoadFormat](../../com.aspose.slides/loadformat).

**Retorna:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

Retorna ou define o formato de uma apresentação a ser carregada. Leitura/gravação [LoadFormat](../../com.aspose.slides/loadformat).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Retorna ou define a fonte Regular usada caso a fonte de origem não seja encontrada. Leitura-gravação String.

**Retorna:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Retorna ou define a fonte Regular usada caso a fonte de origem não seja encontrada. Leitura-gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

Retorna ou define a fonte Symbol usada caso a fonte de origem não seja encontrada. Leitura-gravação String.

**Retorna:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

Retorna ou define a fonte Symbol usada caso a fonte de origem não seja encontrada. Leitura-gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

Retorna ou define a fonte Asian usada caso a fonte de origem não seja encontrada. Leitura-gravação String.

**Retorna:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

Retorna ou define a fonte Asian usada caso a fonte de origem não seja encontrada. Leitura-gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Obtém ou define a senha. Leitura-gravação String.

Valor: A senha.

**Retorna:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Obtém ou define a senha. Leitura-gravação String.

Valor: A senha.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

Esta propriedade faz sentido se o arquivo de apresentação estiver protegido por senha. Valor true significa que apenas as propriedades do documento devem ser carregadas de um arquivo de apresentação criptografado e a senha deve ser ignorada. Valor false significa que a apresentação criptografada inteira deve ser carregada usando a senha correta. Se a apresentação não estiver criptografada, o valor da propriedade é sempre ignorado. Se as propriedades do documento de um arquivo criptografado não forem públicas e o valor da propriedade for true, as propriedades do documento não poderão ser carregadas e será lançada uma exceção. Leitura-gravação boolean.

**Retorna:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

Esta propriedade faz sentido se o arquivo de apresentação estiver protegido por senha. Valor true significa que apenas as propriedades do documento devem ser carregadas de um arquivo de apresentação criptografado e a senha deve ser ignorada. Valor false significa que a apresentação criptografada inteira deve ser carregada usando a senha correta. Se a apresentação não estiver criptografada, o valor da propriedade é sempre ignorado. Se as propriedades do documento de um arquivo criptografado não forem públicas e o valor da propriedade for true, as propriedades do documento não poderão ser carregadas e será lançada uma exceção. Leitura-gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Leitura/gravação [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Retorna:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Leitura/gravação [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |
### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

Representa as opções que podem ser usadas para gerenciar o comportamento de manipulação de Binary Large Objects (BLOBs), como uso de arquivos temporários ou máximo de bytes BLOBs na memória. Essas opções destinam-se a definir a melhor relação desempenho/consumo de memória para um ambiente ou requisitos específicos.

--------------------

Um Binary Large Object (BLOB) é um dado binário armazenado como uma única entidade – ou seja, um BLOB pode ser um áudio, vídeo ou a própria apresentação.

**Retorna:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

Representa as opções que podem ser usadas para gerenciar o comportamento de manipulação de Binary Large Objects (BLOBs), como uso de arquivos temporários ou máximo de bytes BLOBs na memória. Essas opções destinam-se a definir a melhor relação desempenho/consumo de memória para um ambiente ou requisitos específicos.

--------------------

Um Binary Large Object (BLOB) é um dado binário armazenado como uma única entidade – ou seja, um BLOB pode ser um áudio, vídeo ou a própria apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |
### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

Especifica fontes externas a serem usadas pela apresentação. Essas fontes ficam disponíveis para a apresentação durante todo o seu ciclo de vida e não são compartilhadas com outras apresentações.

**Retorna:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

Especifica fontes externas a serem usadas pela apresentação. Essas fontes ficam disponíveis para a apresentação durante todo o seu ciclo de vida e não são compartilhadas com outras apresentações.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |
### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

O token para monitorar solicitações de interrupção.

--------------------

Este token gerencia toda a vida útil da instância [IPresentation](../../com.aspose.slides/ipresentation). Qualquer operação de longa duração, como carregamento ou salvamento de apresentação, será interrompida ao chamar o método [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) do [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Retorna:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

O token para monitorar solicitações de interrupção.

--------------------

Este token gerencia toda a vida útil da instância [IPresentation](../../com.aspose.slides/ipresentation). Qualquer operação de longa duração, como carregamento ou salvamento de apresentação, será interrompida ao chamar o método [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) do [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |
### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

Retorna ou define a interface de callback que gerencia o carregamento de recursos externos. Leitura/gravação [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Retorna:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Retorna ou define a interface de callback que gerencia o carregamento de recursos externos. Leitura/gravação [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |
### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

Representa opções que podem ser usadas para especificar comportamento adicional de planilhas.

**Retorna:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Representa opções que podem ser usadas para especificar comportamento adicional de planilhas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |
### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

Retorna ou define o idioma padrão para o texto da apresentação. Leitura/gravação String.

--------------------

> ```
> Example:
>   
>  // Use opções de carregamento para definir a cultura de texto padrão
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Adicionar nova forma de retângulo com texto
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Verificar a linguagem da primeira porção
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```

Retorna ou define o idioma padrão para o texto da apresentação. Leitura/gravação String.

--------------------

> ```
> Example:
>   
>  // Usar opções de carregamento para definir a cultura de texto padrão
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Adicionar nova forma de retângulo com texto
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Verificar a linguagem da primeira porção
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

Determina se o Aspose.Slides excluirá todos os objetos binários incorporados ao carregar a apresentação.

Os tipos dos objetos binários incorporados:

 *  
 *  
 *  

Leitura/gravação booleano.

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

O padrão é **false**.

**Retorna:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

Determina se o Aspose.Slides excluirá todos os objetos binários incorporados ao carregar a apresentação.

Os tipos dos objetos binários incorporados:

 *  
 *  
 *  

Leitura/gravação booleano.

--------------------

> ```
> O exemplo a seguir mostra como carregar a apresentação sem quaisquer objetos binários incorporados.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

O padrão é **false**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |