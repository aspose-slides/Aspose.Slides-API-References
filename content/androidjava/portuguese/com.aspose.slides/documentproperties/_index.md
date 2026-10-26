---
title: DocumentProperties
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa propriedades de uma apresentação.
type: docs
url: /pt/com.aspose.slides/documentproperties/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

Representa propriedades de uma apresentação.

--------------------

> ```
>  // Instancie a classe Presentation que representa a apresentação
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Crie uma referência ao objeto IDocumentProperties associado à Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Exiba as propriedades internas
>      System.out.println("Category : " + documentProperties.getCategory());
>      System.out.println("Current Status : " + documentProperties.getContentStatus());
>      System.out.println("Creation Date : " + documentProperties.getCreatedTime());
>      System.out.println("Author : " + documentProperties.getAuthor());
>      System.out.println("Description : " + documentProperties.getComments());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  // Instancie a classe Presentation que representa a Presentation
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Crie uma referência ao objeto IDocumentProperties associado à Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Defina as propriedades internas
>      documentProperties.setAuthor("Aspose.Slides for Android via Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // Salve sua apresentação em um arquivo
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```
## Construtores

| Construtor | Descrição |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | Inicializa nova instância da classe [DocumentProperties](../../com.aspose.slides/documentproperties). |
## Métodos

| Método | Descrição |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Retorna a versão do aplicativo. |
| [getNameOfApplication()](#getNameOfApplication--) | Retorna ou define o nome do aplicativo. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Retorna ou define o nome do aplicativo. |
| [getCompany()](#getCompany--) | Retorna ou define a propriedade da empresa. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Retorna ou define a propriedade da empresa. |
| [getManager()](#getManager--) | Retorna ou define a propriedade do gerente. |
| [setManager(String value)](#setManager-java.lang.String-) | Retorna ou define a propriedade do gerente. |
| [getPresentationFormat()](#getPresentationFormat--) | Retorna ou define o formato esperado de uma apresentação. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Retorna ou define o formato esperado de uma apresentação. |
| [getSharedDoc()](#getSharedDoc--) | Determina se a apresentação está compartilhada entre várias pessoas. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Determina se a apresentação está compartilhada entre várias pessoas. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Retorna ou define o modelo de um aplicativo. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Retorna ou define o modelo de um aplicativo. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Tempo total de edição de uma apresentação. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Tempo total de edição de uma apresentação. |
| [getTitle()](#getTitle--) | Retorna ou define o título de uma apresentação. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Retorna ou define o título de uma apresentação. |
| [getSubject()](#getSubject--) | Retorna ou define o assunto de uma apresentação. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Retorna ou define o assunto de uma apresentação. |
| [getAuthor()](#getAuthor--) | Retorna ou define o autor de uma apresentação. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Retorna ou define o autor de uma apresentação. |
| [getKeywords()](#getKeywords--) | Retorna ou define as palavras-chave de uma apresentação. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Retorna ou define as palavras-chave de uma apresentação. |
| [getComments()](#getComments--) | Retorna ou define os comentários de uma apresentação. |
| [setComments(String value)](#setComments-java.lang.String-) | Retorna ou define os comentários de uma apresentação. |
| [getCategory()](#getCategory--) | Retorna ou define a categoria de uma apresentação. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Retorna ou define a categoria de uma apresentação. |
| [getCreatedTime()](#getCreatedTime--) | Retorna a data em que a apresentação foi criada. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Retorna a data em que a apresentação foi criada. |
| [getLastSavedTime()](#getLastSavedTime--) | Retorna a data em que a apresentação foi modificada pela última vez. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Retorna a data em que a apresentação foi modificada pela última vez. |
| [getLastPrinted()](#getLastPrinted--) | Retorna a data em que a apresentação foi impressa pela última vez. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Retorna a data em que a apresentação foi impressa pela última vez. |
| [getLastSavedBy()](#getLastSavedBy--) | Retorna ou define o nome da última pessoa que modificou a apresentação. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Retorna ou define o nome da última pessoa que modificou a apresentação. |
| [getRevisionNumber()](#getRevisionNumber--) | Retorna ou define o número da revisão da apresentação. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Retorna ou define o número da revisão da apresentação. |
| [getContentStatus()](#getContentStatus--) | Retorna ou define o status do conteúdo da apresentação. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Retorna ou define o status do conteúdo da apresentação. |
| [getContentType()](#getContentType--) | Retorna ou define o tipo de conteúdo da apresentação. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Retorna ou define o tipo de conteúdo da apresentação. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Retorna ou define a propriedade de documento HyperlinkBase. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Retorna ou define a propriedade de documento HyperlinkBase. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Retorna o número de propriedades personalizadas realmente contidas em uma coleção. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Retorna um nome de propriedade personalizada no índice especificado. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Remove uma propriedade personalizada associada a um nome especificado. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Verifica a presença de uma propriedade personalizada com um nome especificado. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Retorna ou define a propriedade personalizada associada a um nome especificado. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Retorna ou define a propriedade personalizada associada a um nome especificado. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Obtém um valor booleano nomeado das propriedades personalizadas. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Obtém um valor inteiro nomeado das propriedades personalizadas. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Obtém um valor DateTime nomeado das propriedades personalizadas. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Obtém um valor string nomeado das propriedades personalizadas. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Obtém um valor float nomeado das propriedades personalizadas. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Obtém um valor double nomeado das propriedades personalizadas. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Define uma propriedade personalizada boolean nomeada. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Define uma propriedade personalizada inteira nomeada. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Define uma propriedade personalizada DateTime nomeada. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Define uma propriedade personalizada string nomeada. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Define uma propriedade personalizada float nomeada. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Define uma propriedade personalizada double nomeada. |
| [clearCustomProperties()](#clearCustomProperties--) | Remove todas as propriedades personalizadas. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Obtém um array de rótulos de sensibilidade das propriedades de documento personalizadas (Metadados do Microsoft Information Protection SDK). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Limpa e define valores padrão para todas as propriedades builtIn. |
| [getScaleCrop()](#getScaleCrop--) | Indica o modo de exibição da miniatura do documento. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Indica o modo de exibição da miniatura do documento. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Indica se os hiperlinks em um documento estão atualizados. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Indica se os hiperlinks em um documento estão atualizados. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Especifica que um ou mais hiperlinks nesta parte foram atualizados exclusivamente nesta parte por um produtor. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Especifica que um ou mais hiperlinks nesta parte foram atualizados exclusivamente nesta parte por um produtor. |
| [getSlides()](#getSlides--) | Retorna o número total de slides em um documento de apresentação. |
| [getHiddenSlides()](#getHiddenSlides--) | Retorna o número de slides ocultos em um documento de apresentação. |
| [getNotes()](#getNotes--) | Retorna o número de slides em uma apresentação que contém notas. |
| [getParagraphs()](#getParagraphs--) | Retorna o número total de parágrafos encontrados em um documento, se aplicável. |
| [getWords()](#getWords--) | Retorna o número total de palavras contidas em um documento. |
| [getMultimediaClips()](#getMultimediaClips--) | Retorna o número total de clipes de som ou vídeo presentes no documento. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Especifica o título de cada parte do documento. |
| [getHeadingPairs()](#getHeadingPairs--) | Indica a agrupamento das partes do documento e o número de partes em cada grupo. |
| [deepClone()](#deepClone--) | Clona o objeto atual |
| [cloneT()](#cloneT--) | Clona o objeto atual |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

Inicializa nova instância da classe [DocumentProperties](../../com.aspose.slides/documentproperties).

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

Retorna a versão do aplicativo. Somente leitura String.

**Retorna:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

Retorna ou define o nome do aplicativo. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

Retorna ou define o nome do aplicativo. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getCompany() {#getCompany--}
```
public final String getCompany()
```

Retorna ou define a propriedade da empresa. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

Retorna ou define a propriedade da empresa. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getManager() {#getManager--}
```
public final String getManager()
```

Retorna ou define a propriedade do gerente. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

Retorna ou define a propriedade do gerente. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

Retorna ou define o formato esperado de uma apresentação. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

Retorna ou define o formato esperado de uma apresentação. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

Determina se a apresentação está compartilhada entre várias pessoas. Leitura/Gravação boolean.

**Retorna:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

Determina se a apresentação está compartilhada entre várias pessoas. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

Retorna ou define o modelo de um aplicativo. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

Retorna ou define o modelo de um aplicativo. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

Tempo total de edição de uma apresentação. Leitura/Gravação double.

**Retorna:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

Tempo total de edição de uma apresentação. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getTitle() {#getTitle--}
```
public final String getTitle()
```

Retorna ou define o título de uma apresentação. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

Retorna ou define o título de uma apresentação. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getSubject() {#getSubject--}
```
public final String getSubject()
```

Retorna ou define o assunto de uma apresentação. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

Retorna ou define o assunto de uma apresentação. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

Retorna ou define o autor de uma apresentação. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

Retorna ou define o autor de uma apresentação. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

Retorna ou define as palavras-chave de uma apresentação. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

Retorna ou define as palavras-chave de uma apresentação. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public final String getComments()
```

Retorna ou define os comentários de uma apresentação. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Retorna ou define os comentários de uma apresentação. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getCategory() {#getCategory--}
```
public final String getCategory()
```

Retorna ou define a categoria de uma apresentação. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

Retorna ou define a categoria de uma apresentação. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Retorna a data em que a apresentação foi criada. Valores estão em UTC. Leitura/Gravação java.util.Date.

**Retorna:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Retorna a data em que a apresentação foi criada. Valores estão em UTC. Leitura/Gravação java.util.Date.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

Retorna a data em que a apresentação foi modificada pela última vez. Valores estão em UTC. Somente leitura no caso de Presentation.DocumentProperties (porque será atualizado internamente durante o processo de salvamento do objeto IPresentation). Pode ser alterado via instância DocumentProperties retornada pelo método [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Consulte o exemplo no resumo do método [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Retorna:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

Retorna a data em que a apresentação foi modificada pela última vez. Valores estão em UTC. Somente leitura no caso de Presentation.DocumentProperties (porque será atualizado internamente durante o processo de salvamento do objeto IPresentation). Pode ser alterado via instância DocumentProperties retornada pelo método [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Consulte o exemplo no resumo do método [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

Retorna a data em que a apresentação foi impressa pela última vez. Leitura/Gravação java.util.Date.

**Retorna:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

Retorna a data em que a apresentação foi impressa pela última vez. Leitura/Gravação java.util.Date.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

Retorna ou define o nome da última pessoa que modificou a apresentação. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

Retorna ou define o nome da última pessoa que modificou a apresentação. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

Retorna ou define o número da revisão da apresentação. Leitura/Gravação int.

**Retorna:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

Retorna ou define o número da revisão da apresentação. Leitura/Gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```

Retorna ou define o status do conteúdo da apresentação. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

Retorna ou define o status do conteúdo da apresentação. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Retorna ou define o tipo de conteúdo da apresentação. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Retorna ou define o tipo de conteúdo da apresentação. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

Retorna ou define a propriedade de documento HyperlinkBase. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

Retorna ou define a propriedade de documento HyperlinkBase. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

Retorna o número de propriedades personalizadas realmente contidas em uma coleção. Somente leitura int.

**Retorna:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

Retorna um nome de propriedade personalizada no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero da propriedade personalizada a ser obtida. |

**Retorna:**
java.lang.String - Nome da propriedade personalizada no índice especificado.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

Remove uma propriedade personalizada associada a um nome especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser removida. |

**Retorna:**
boolean - Retorna true se a propriedade foi removida, false caso contrário.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

Verifica a presença de uma propriedade personalizada com um nome especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser verificada. |

**Retorna:**
boolean - Retorna true se a propriedade existe, false caso contrário.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

Retorna ou define a propriedade personalizada associada a um nome especificado. Leitura/Gravação Object.

--------------------

O valor pode ser **int**, **float**, **String**, **boolean** ou **Date**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String |  |

**Retorna:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```

Retorna ou define a propriedade personalizada associada a um nome especificado. Leitura/Gravação Object.

--------------------

O valor pode ser **int**, **float**, **String**, **boolean** ou **Date**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

Obtém um valor booleano nomeado das propriedades personalizadas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser obtida |
| value | boolean[] | Valor da propriedade personalizada |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

Obtém um valor inteiro nomeado das propriedades personalizadas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser obtida |
| value | int[] | Valor da propriedade personalizada |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

Obtém um valor DateTime nomeado das propriedades personalizadas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser obtida |
| value | java.util.Date[] | Valor da propriedade personalizada |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

Obtém um valor string nomeado das propriedades personalizadas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser obtida |
| value | java.lang.String[] | Valor da propriedade personalizada |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

Obtém um valor float nomeado das propriedades personalizadas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser obtida |
| value | float[] | Valor da propriedade personalizada |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

Obtém um valor double nomeado das propriedades personalizadas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser obtida. |
| value | double[] | Valor da propriedade personalizada |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

Define uma propriedade personalizada boolean nomeada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser definida |
| value | boolean | Valor da propriedade personalizada |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

Define uma propriedade personalizada inteira nomeada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser definida |
| value | int | Valor da propriedade personalizada |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

Define uma propriedade personalizada DateTime nomeada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser definida |
| value | java.util.Date | Valor da propriedade personalizada |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public  



The 







It 







 



 















 







OMIC


















What







The 


```

Define uma propriedade personalizada string nomeada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser definida |
| value | java.lang.String | Valor da propriedade personalizada |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

Define uma propriedade personalizada float nomeada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser definida |
| value | float | Valor da propriedade personalizada |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

Define uma propriedade personalizada double nomeada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser definida |
| value | double | Valor da propriedade personalizada |
### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```

Remove todas as propriedades personalizadas.
### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

Obtém um array de rótulos de sensibilidade das propriedades de documento personalizadas (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Obtém rótulos de sensibilidade das propriedades de documento personalizadas
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Adiciona rótulo à coleção
>          // Aqui você pode adicionar uma verificação da validade das informações do rótulo (se o rótulo está disponível, etc)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public 


```

Limpa e define valores padrão para todas as propriedades builtIn.
### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

Indica o modo de exibição da miniatura do documento. Defina este elemento como **true** para habilitar o dimensionamento da miniatura do documento para a exibição. Defina como **false** para habilitar o recorte da miniatura do documento para mostrar apenas as seções que se ajustam à exibição. Leitura/Gravação boolean.

**Retorna:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

Indica o modo de exibição da miniatura do documento. Defina este elemento como **true** para habilitar o dimensionamento da miniatura do documento para a exibição. Defina como **false** para habilitar o recorte da miniatura do documento para mostrar apenas as seções que se ajustam à exibição. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

Indica se os hiperlinks em um documento estão atualizados. Defina este elemento como **true** para indicar que os hiperlinks foram atualizados. Defina como **false** para indicar que os hiperlinks estão desatualizados. Leitura/Gravação boolean.

**Retorna:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```

Indica se os hiperlinks em um documento estão atualizados. Defina este elemento como **true** para indicar que os hiperlinks foram atualizados. Defina como **false** para indicar que os hiperlinks estão desatualizados. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Especifica que um ou mais hiperlinks nesta parte foram atualizados exclusivamente nesta parte por um produtor. O próximo produtor a abrir este documento deverá atualizar as relações de hiperlink com os novos hiperlinks especificados nesta parte. Leitura/Gravação boolean.

**Retorna:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Especifica que um ou mais hiperlinks nesta parte foram atualizados exclusivamente nesta parte por um produtor. O próximo produtor a abrir este documento deverá atualizar as relações de hiperlink com os novos hiperlinks especificados nesta parte. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getSlides() {#getSlides--}
```
public final int getSlides()
```

Retorna o número total de slides em um documento de apresentação. Somente leitura int.

**Retorna:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Retorna o número de slides ocultos em um documento de apresentação. Somente leitura int.

**Retorna:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

Retorna o número de slides em uma apresentação que contém notas. Somente leitura int.

**Retorna:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

Retorna o número total de parágrafos encontrados em um documento, se aplicável. Somente leitura int.

**Retorna:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

Retorna o número total de palavras contidas em um documento. Somente leitura int.

**Retorna:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Retorna o número total de clipes de som ou vídeo presentes no documento. Somente leitura int.

**Retorna:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Especifica o título de cada parte do documento. Essas partes não são partes de documento, mas representações conceituais de seções do documento. Somente leitura String[].

**Retorna:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public



It appears

The

It appears
The

```

Indica a agrupamento das partes do documento e o número de partes em cada grupo. Somente leitura IHeadingPair[].

**Retorna:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Clona o objeto atual

**Retorna:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Clona o objeto atual

**Retorna:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone