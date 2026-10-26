---
title: LoadOptions
second_title: Aspose.Slides para Android via Referência da API Java
description: Permite especificar opções adicionais, como formato ou fonte padrão, ao carregar uma apresentação.
type: docs
url: /pt/com.aspose.slides/loadoptions/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Permite especificar opções adicionais (como formato ou fonte padrão) ao carregar uma apresentação.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Cria novas opções de carregamento padrão. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Cria novas opções de carregamento. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Retorna ou define o formato de uma apresentação a ser carregada. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Retorna ou define o formato de uma apresentação a ser carregada. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Retorna ou define a fonte Regular usada caso a fonte original não seja encontrada. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Retorna ou define a fonte Regular usada caso a fonte original não seja encontrada. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Retorna ou define a fonte Symbol usada caso a fonte original não seja encontrada. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Retorna ou define a fonte Symbol usada caso a fonte original não seja encontrada. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Retorna ou define a fonte Asiática usada caso a fonte original não seja encontrada. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Retorna ou define a fonte Asiática usada caso a fonte original não seja encontrada. |
| [getPassword()](#getPassword--) | Obtém ou define a senha. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Obtém ou define a senha. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Esta propriedade faz sentido se o arquivo de apresentação estiver protegido por senha. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Esta propriedade faz sentido se o arquivo de apresentação estiver protegido por senha. |
| [getWarningCallback()](#getWarningCallback--) | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Representa as opções que podem ser usadas para gerenciar o comportamento de manipulação de Binary Large Objects (BLOBs), como o uso de arquivos temporários ou bytes máximos de BLOBs na memória. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Representa as opções que podem ser usadas para gerenciar o comportamento de manipulação de Binary Large Objects (BLOBs), como o uso de arquivos temporários ou bytes máximos de BLOBs na memória. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Especifica fontes externas a serem usadas pela apresentação. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Especifica fontes externas a serem usadas pela apresentação. |
| [getInterruptionToken()](#getInterruptionToken--) | O token para monitorar solicitações de interrupção. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | O token para monitorar solicitações de interrupção. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Retorna ou define a interface de callback que gerencia o carregamento de recursos externos. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Retorna ou define a interface de callback que gerencia o carregamento de recursos externos. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Obtém opções para planilhas. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Obtém opções para planilhas. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Retorna ou define o idioma padrão para o texto da apresentação. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Retorna ou define o idioma padrão para o texto da apresentação. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Determina se o Aspose.Slides excluirá todos os objetos binários incorporados durante o carregamento da apresentação. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Determina se o Aspose.Slides excluirá todos os objetos binários incorporados durante o carregamento da apresentação. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

Cria novas opções de carregamento padrão.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

Cria novas opções de carregamento.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| loadFormat | int | Formato de uma apresentação a ser carregada. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Retorna ou define o formato de uma apresentação a ser carregada. Leitura/Gravação [LoadFormat](../../com.aspose.slides/loadformat).

**Retorna:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

Retorna ou define o formato de uma apresentação a ser carregada. Leitura/Gravação [LoadFormat](../../com.aspose.slides/loadformat).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Retorna ou define a fonte Regular usada caso a fonte original não seja encontrada. Leitura/Gravação String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Use load options to define the default regular and asian fonts
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Load the presentation
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Generate slide thumbnail
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // Generate PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Generate XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Retorna ou define a fonte Regular usada caso a fonte original não seja encontrada. Leitura/Gravação String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Use load options to define the default regular and asian fonts
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Load the presentation
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Generate slide thumbnail
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // Generate PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Generate XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

Retorna ou define a fonte Symbol usada caso a fonte original não seja encontrada. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Retorna ou define a fonte Symbol usada caso a fonte original não seja encontrada. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Retorna ou define a fonte Asiática usada caso a fonte original não seja encontrada. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Retorna ou define a fonte Asiática usada caso a fonte original não seja encontrada. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Obtém ou define a senha. Leitura/Gravação String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // trabalhar com a apresentação descriptografada
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Valor: A senha.

**Retorna:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Obtém ou define a senha. Leitura/Gravação String.

--------------------

> ```
> O código de exemplo a seguir mostra como abrir uma apresentação PowerPoint protegida por senha.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // trabalhar com a apresentação descriptografada
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Valor: A senha.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

Esta propriedade faz sentido se o arquivo de apresentação estiver protegido por senha. Valor true significa que apenas as propriedades do documento devem ser carregadas de um arquivo de apresentação criptografado e a senha deve ser ignorada. Valor false significa que toda a apresentação criptografada deve ser carregada usando a senha correta. Se a apresentação não estiver criptografada, o valor da propriedade será sempre ignorado. Se as propriedades do documento de um arquivo criptografado não forem públicas e o valor da propriedade for true, as propriedades do documento não poderão ser carregadas e uma exceção será lançada. Leitura/Gravação boolean.

**Retorna:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

Esta propriedade faz sentido se o arquivo de apresentação estiver protegido por senha. Valor true significa que apenas as propriedades do documento devem ser carregadas de um arquivo de apresentação criptografado e a senha deve ser ignorada. Valor false significa que toda a apresentação criptografada deve ser carregada usando a senha correta. Se a apresentação não estiver criptografada, o valor da propriedade será sempre ignorado. Se as propriedades do documento de um arquivo criptografado não forem públicas e o valor da propriedade for true, as propriedades do documento não poderão ser carregadas e uma exceção será lançada. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Leitura/Gravação [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Retorna:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Leitura/Gravação [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Representa as opções que podem ser usadas para gerenciar o comportamento de manipulação de Binary Large Objects (BLOBs), como o uso de arquivos temporários ou bytes máximos de BLOBs na memória. Essas opções visam configurar a melhor relação desempenho/consumo de memória para um ambiente ou requisitos específicos.

--------------------

Um Binary Large Object (BLOB) é um dado binário armazenado como uma única entidade – ou seja, o BLOB pode ser um áudio, vídeo ou a própria apresentação.

**Retorna:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Representa as opções que podem ser usadas para gerenciar o comportamento de manipulação de Binary Large Objects (BLOBs), como o uso de arquivos temporários ou bytes máximos de BLOBs na memória. Essas opções visam configurar a melhor relação desempenho/consumo de memória para um ambiente ou requisitos específicos.

--------------------

Um Binary Large Object (BLOB) é um dado binário armazenado como uma única entidade – ou seja, o BLOB pode ser um áudio, vídeo ou a própria apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

Especifica fontes externas a serem usadas pela apresentação. Essas fontes estão disponíveis para a apresentação durante todo o seu ciclo de vida e não são compartilhadas com outras apresentações

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //work with the presentation
>  //CustomFont1, CustomFont2 as well as fonts from assets\fonts & global\fonts folders and their subfolders are available to the presentation
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retorna:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

Especifica fontes externas a serem usadas pela apresentação. Essas fontes estão disponíveis para a apresentação durante todo o seu ciclo de vida e não são compartilhadas com outras apresentações

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //work with the presentation
>  //CustomFont1, CustomFont2 as well as fonts from assets\fonts & global\fonts folders and their subfolders are available to the presentation
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

O token para monitorar solicitações de interrupção.

Este token gerencia todo o ciclo de vida da instância [IPresentation](../../com.aspose.slides/ipresentation). Qualquer operação de longa duração, como carregar ou salvar a apresentação, será interrompida ao chamar o método [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) do [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Retorna:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

O token para monitorar solicitações de interrupção.

Este token gerencia todo o ciclo de vida da instância [IPresentation](../../com.aspose.slides/ipresentation). Qualquer operação de longa duração, como carregar ou salvar a apresentação, será interrompida ao chamar o método [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) do [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

Retorna ou define a interface de callback que gerencia o carregamento de recursos externos. Leitura/Gravação [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Retorna:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Retorna ou define a interface de callback que gerencia o carregamento de recursos externos. Leitura/Gravação [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

Obtém opções para planilhas. Por exemplo, essas opções afetam o cálculo de fórmulas para gráficos.

**Retorna:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Obtém opções para planilhas. Por exemplo, essas opções afetam o cálculo de fórmulas para gráficos.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

Retorna ou define o idioma padrão para o texto da apresentação. Leitura/Gravação String.

--------------------

> ```
> Example:
>   
>  // Use load options to define the default text culture
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Add new rectangle shape with text
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Check the first portion language
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

Retorna ou define o idioma padrão para o texto da apresentação. Leitura/Gravação String.

--------------------

> ```
> Example:
>   
>  // Use load options to define the default text culture
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Add new rectangle shape with text
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Check the first portion language
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
public final boolean getDeleteEmbeddedBinaryObjects()
```

Determina se o Aspose.Slides excluirá todos os objetos binários incorporados durante o carregamento da apresentação.

Os tipos dos objetos binários incorporados:

Leitura/Gravação  boolean .

--------------------

> ```
> O exemplo a seguir mostra como carregar a apresentação sem objetos binários incorporados.
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


O padrão é  **false** .

**Retorna:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

Determina se o Aspose.Slides excluirá todos os objetos binários incorporados durante o carregamento da apresentação.

Os tipos dos objetos binários incorporados:

Leitura/Gravação  boolean .

--------------------

> ```
> O exemplo a seguir mostra como carregar a apresentação sem objetos binários incorporados.
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


O padrão é  **false** .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |