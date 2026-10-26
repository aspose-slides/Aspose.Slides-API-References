---
title: IDocumentProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents properties of a presentation.
type: docs
url: /pt/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

Representa as propriedades de uma apresentação.
## Métodos

| Method | Description |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Retorna a versão do aplicativo. |
| [getNameOfApplication()](#getNameOfApplication--) | Retorna ou define o nome do aplicativo. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Retorna ou define o nome do aplicativo. |
| [getCompany()](#getCompany--) | Retorna ou define a propriedade da empresa. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Retorna ou define a propriedade da empresa. |
| [getManager()](#getManager--) | Retorna ou define a propriedade do gerente. |
| [setManager(String value)](#setManager-java.lang.String-) | Retorna ou define a propriedade do gerente. |
| [getPresentationFormat()](#getPresentationFormat--) | Retorna ou define o formato pretendido de uma apresentação. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Retorna ou define o formato pretendido de uma apresentação. |
| [getSharedDoc()](#getSharedDoc--) | Determina se a apresentação é compartilhada entre várias pessoas. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Determina se a apresentação é compartilhada entre várias pessoas. |
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
| [getRevisionNumber()](#getRevisionNumber--) | Retorna ou define o número de revisão da apresentação. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Retorna ou define o número de revisão da apresentação. |
| [getContentStatus()](#getContentStatus--) | Retorna ou define o status do conteúdo de uma apresentação. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Retorna ou define o status do conteúdo de uma apresentação. |
| [getContentType()](#getContentType--) | Retorna ou define o tipo de conteúdo de uma apresentação. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Retorna ou define o tipo de conteúdo de uma apresentação. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Retorna ou define a propriedade HyperlinkBase do documento. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Retorna ou define a propriedade HyperlinkBase do documento. |
| [getScaleCrop()](#getScaleCrop--) | Indica o modo de exibição da miniatura do documento. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Indica o modo de exibição da miniatura do documento. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Indica se os hiperlinks em um documento estão atualizados. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Indica se os hiperlinks em um documento estão atualizados. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Especifica que um ou mais hiperlinks nesta parte foram atualizados exclusivamente nesta parte por um produtor. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Especifica que um ou mais hiperlinks nesta parte foram atualizados exclusivamente nesta parte por um produtor. |
| [getSlides()](#getSlides--) | Especifica o número total de slides em um documento de apresentação. |
| [getHiddenSlides()](#getHiddenSlides--) | Especifica o número de slides ocultos em um documento de apresentação. |
| [getNotes()](#getNotes--) | Especifica o número de slides em uma apresentação que contém notas. |
| [getParagraphs()](#getParagraphs--) | Especifica o número total de parágrafos encontrados em um documento, se aplicável. |
| [getWords()](#getWords--) | Especifica o número total de palavras contidas em um documento. |
| [getMultimediaClips()](#getMultimediaClips--) | Especifica o número total de clipes de som ou vídeo presentes no documento. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Especifica o título de cada parte do documento. |
| [getHeadingPairs()](#getHeadingPairs--) | Indica o agrupamento das partes do documento e o número de partes em cada grupo. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Retorna o número de propriedades personalizadas realmente contidas em uma coleção. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Retorna o nome de uma propriedade personalizada no índice especificado. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Remove uma propriedade personalizada associada a um nome especificado. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Verifica a presença de uma propriedade personalizada com um nome especificado. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Retorna ou define a propriedade personalizada associada a um nome especificado. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Retorna ou define a propriedade personalizada associada a um nome especificado. |
| [clearCustomProperties()](#clearCustomProperties--) | Remove todas as propriedades personalizadas. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Limpa e define valores padrão para todas as propriedades builtIn. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Define uma propriedade personalizada booleana nomeada. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Define uma propriedade personalizada inteira nomeada. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Define uma propriedade personalizada DateTime nomeada. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Define uma propriedade personalizada string nomeada. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Define uma propriedade personalizada float nomeada. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Define uma propriedade personalizada double nomeada. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Obtém uma matriz de rótulos de sensibilidade das propriedades personalizadas do documento (Microsoft Information Protection SDK Metadata). |
### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

Retorna a versão do aplicativo. Somente leitura String.

--------------------

O conteúdo deste elemento deve estar no formato XX.YYYY, onde X e Y representam valores numéricos; caso contrário, o documento será considerado não conforme. Aspose.Slides representa sua versão no formato XX.YY.ZZ, onde: XX – versão majoritária YY – versão secundária ZZ – versão de patch. Por exemplo, o valor 23.0105 significa a versão 23.1.5 do Aspose.Slides.

**Retorna:**  
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

Retorna ou define o nome do aplicativo. Leitura/gravação String.

**Retorna:**  
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

Retorna ou define o nome do aplicativo. Leitura/gravação String.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

Retorna ou define a propriedade da empresa. Leitura/gravação String.

**Retorna:**  
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

Retorna ou define a propriedade da empresa. Leitura/gravação String.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getManager() {#getManager--}
```
public abstract String getManager()
```

Retorna ou define a propriedade do gerente. Leitura/gravação String.

**Retorna:**  
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

Retorna ou define a propriedade do gerente. Leitura/gravação String.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

Retorna ou define o formato pretendido de uma apresentação. Leitura/gravação String.

**Retorna:**  
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

Retorna ou define o formato pretendido de uma apresentação. Leitura/gravação String.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

Determina se a apresentação é compartilhada entre várias pessoas. Leitura/gravação boolean.

**Retorna:**  
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

Determina se a apresentação é compartilhada entre várias pessoas. Leitura/gravação boolean.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

Retorna ou define o modelo de um aplicativo. Leitura/gravação String.

**Retorna:**  
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

Retorna ou define o modelo de um aplicativo. Leitura/gravação String.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

Tempo total de edição de uma apresentação. Leitura/gravação double.

**Retorna:**  
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

Tempo total de edição de uma apresentação. Leitura/gravação double.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

Retorna ou define o título de uma apresentação. Leitura/gravação String.

**Retorna:**  
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

Retorna ou define o título de uma apresentação. Leitura/gravação String.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

Retorna ou define o assunto de uma apresentação. Leitura/gravação String.

**Retorna:**  
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

Retorna ou define o assunto de uma apresentação. Leitura/gravação String.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

Retorna ou define o autor de uma apresentação. Leitura/gravação String.

**Retorna:**  
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

Retorna ou define o autor de uma apresentação. Leitura/gravação String.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

Retorna ou define as palavras-chave de uma apresentação. Leitura/gravação String.

**Retorna:**  
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

Retorna ou define as palavras-chave de uma apresentação. Leitura/gravação String.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract String getComments()
```

Retorna ou define os comentários de uma apresentação. Leitura/gravação String.

**Retorna:**  
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

Retorna ou define os comentários de uma apresentação. Leitura/gravação String.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

Retorna ou define a categoria de uma apresentação. Leitura/gravação String.

**Retorna:**  
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

Retorna ou define a categoria de uma apresentação. Leitura/gravação String.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Retorna a data em que a apresentação foi criada. Os valores estão em UTC. Leitura/gravação java.util.Date.

**Retorna:**  
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Retorna a data em que a apresentação foi criada. Os valores estão em UTC. Leitura/gravação java.util.Date.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

Retorna a data em que a apresentação foi modificada pela última vez. Os valores estão em UTC. Somente leitura no caso de Presentation.DocumentProperties (porque será atualizado internamente durante o processo de salvamento do objeto IPresentation). Pode ser alterado via instância DocumentProperties retornada pelo método [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Consulte o exemplo no resumo do método [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Retorna:**  
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

Retorna a data em que a apresentação foi modificada pela última vez. Os valores estão em UTC. Somente leitura no caso de Presentation.DocumentProperties (porque será atualizado internamente durante o processo de salvamento do objeto IPresentation). Pode ser alterado via instância DocumentProperties retornada pelo método [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Consulte o exemplo no resumo do método [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

Retorna a data em que a apresentação foi impressa pela última vez. Leitura/gravação java.util.Date.

**Retorna:**  
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

Retorna a data em que a apresentação foi impressa pela última vez. Leitura/gravação java.util.Date.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

Retorna ou define o nome da última pessoa que modificou a apresentação. Leitura/gravação String.

**Retorna:**  
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

Retorna ou define o nome da última pessoa que modificou a apresentação. Leitura/gravação String.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

Retorna ou define o número de revisão da apresentação. Leitura/gravação int.

**Retorna:**  
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

Retorna ou define o número de revisão da apresentação. Leitura/gravação int.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

Retorna ou define o status do conteúdo de uma apresentação. Leitura/gravação String.

**Retorna:**  
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

Retorna ou define o status do conteúdo de uma apresentação. Leitura/gravação String.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Retorna ou define o tipo de conteúdo de uma apresentação. Leitura/gravação String.

**Retorna:**  
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

Retorna ou define o tipo de conteúdo de uma apresentação. Leitura/gravação String.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

Retorna ou define a propriedade HyperlinkBase do documento. Leitura/gravação String.

**Retorna:**  
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

Retorna ou define a propriedade HyperlinkBase do documento. Leitura/gravação String.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

Indica o modo de exibição da miniatura do documento. Defina este elemento como **true** para habilitar o dimensionamento da miniatura ao display. Defina como **false** para habilitar o recorte da miniatura para mostrar apenas as seções que cabem na tela. Leitura/gravação boolean.

**Retorna:**  
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

Indica o modo de exibição da miniatura do documento. Defina este elemento como **true** para habilitar o dimensionamento da miniatura ao display. Defina como **false** para habilitar o recorte da miniatura para mostrar apenas as seções que cabem na tela. Leitura/gravação boolean.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

Indica se os hiperlinks em um documento estão atualizados. Defina este elemento como **true** para indicar que os hiperlinks foram atualizados. Defina como **false** para indicar que os hiperlinks estão desatualizados. Leitura/gravação boolean.

**Retorna:**  
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

Indica se os hiperlinks em um documento estão atualizados. Defina este elemento como **true** para indicar que os hiperlinks foram atualizados. Defina como **false** para indicar que os hiperlinks estão desatualizados. Leitura/gravação boolean.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

Especifica que um ou mais hiperlinks nesta parte foram atualizados exclusivamente nesta parte por um produtor. O próximo produtor a abrir este documento atualizará os relacionamentos de hiperlink com os novos hiperlinks especificados nesta parte. Leitura/gravação boolean.

**Retorna:**  
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

Especifica que um ou mais hiperlinks nesta parte foram atualizados exclusivamente nesta parte por um produtor. O próximo produtor a abrir este documento atualizará os relacionamentos de hiperlink com os novos hiperlinks especificados nesta parte. Leitura/gravação boolean.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

Especifica o número total de slides em um documento de apresentação. Somente leitura int.

**Retorna:**  
int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

Especifica o número de slides ocultos em um documento de apresentação. Somente leitura int.

**Retorna:**  
int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

Especifica o número de slides em uma apresentação que contém notas. Somente leitura int.

**Retorna:**  
int
### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

Especifica o número total de parágrafos encontrados em um documento, se aplicável. Somente leitura int.

**Retorna:**  
int
### getWords() {#getWords--}
```
public abstract int getWords()
```

Especifica o número total de palavras contidas em um documento. Somente leitura int.

**Retorna:**  
int
### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

Especifica o número total de clipes de som ou vídeo presentes no documento. Somente leitura int.

**Retorna:**  
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

Especifica o título de cada parte do documento. Essas partes não são partes reais do documento, mas representações conceituais de seções do documento. Somente leitura String[].

**Retorna:**  
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

Indica o agrupamento das partes do documento e o número de partes em cada grupo. Somente leitura IHeadingPair[].

**Retorna:**  
com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

Retorna o número de propriedades personalizadas realmente contidas em uma coleção. Somente leitura int.

**Retorna:**  
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

Retorna o nome de uma propriedade personalizada no índice especificado.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero da propriedade personalizada a ser obtida. |

**Retorna:**  
java.lang.String - Nome da propriedade personalizada no índice especificado.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
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
public abstract boolean containsCustomProperty(String name)
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
public abstract Object get_Item(String name)
```

Retorna ou define a propriedade personalizada associada a um nome especificado. Leitura/gravação Object.

--------------------

O valor pode ser **int**, **float**, **double**, **String**, **boolean** ou **Date**.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String |  |

**Retorna:**  
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

Retorna ou define a propriedade personalizada associada a um nome especificado. Leitura/gravação Object.

--------------------

O valor pode ser **int**, **float**, **double**, **String**, **boolean** ou **Date**.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |
### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

Remove todas as propriedades personalizadas.
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

Limpa e define valores padrão para todas as propriedades builtIn.
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

Obtém um valor booleano nomeado das propriedades personalizadas.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser obtida |
| value | boolean[] | Valor da propriedade personalizada |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

Obtém um valor inteiro nomeado das propriedades personalizadas.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser obtida |
| value | int[] | Valor da propriedade personalizada |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

Obtém um valor DateTime nomeado das propriedades personalizadas.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser obtida |
| value | java.util.Date[] | Valor da propriedade personalizada |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

Obtém um valor string nomeado das propriedades personalizadas.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser obtida |
| value | java.lang.String[] | Valor da propriedade personalizada |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

Obtém um valor float nomeado das propriedades personalizadas.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser obtida |
| value | float[] | Valor da propriedade personalizada |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

Obtém um valor double nomeado das propriedades personalizadas.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser obtida. |
| value | double[] | Valor da propriedade personalizada |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

Define uma propriedade personalizada booleana nomeada.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser definida |
| value | boolean | Valor da propriedade personalizada |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

Define uma propriedade personalizada inteira nomeada.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser definida |
| value | int | Valor da propriedade personalizada |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

Define uma propriedade personalizada DateTime nomeada.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser definida |
| value | java.util.Date | Valor da propriedade personalizada |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

Define uma propriedade personalizada string nomeada.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser definida |
| value | java.lang.String | Valor da propriedade personalizada |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```




```

Define uma propriedade personalizada float nomeada.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser definida |
| value | float | Valor da propriedade personalizada |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

Define uma propriedade personalizada double nomeada.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da propriedade personalizada a ser definida |
| value | double | Valor da propriedade personalizada |
### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

Obtém uma matriz de rótulos de sensibilidade das propriedades personalizadas do documento (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Get sensitivity labels from the custom document properties
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Add label to the collection
>          // Here you can add a check for the validity of the label information (the label is available, etc)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**  
com.aspose.slides.ISensitivityLabel[]