---
title: IPresentation
second_title: Aspose.Slides para Android via Referência da API Java
description: Documento de apresentação
type: docs
url: /pt/com.aspose.slides/ipresentation/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Documento de apresentação
## Métodos

| Método | Descrição |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Retorna ou define a data e hora que substituirá o conteúdo dos campos datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Retorna ou define a data e hora que substituirá o conteúdo dos campos datetime. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retorna o gerenciador HeaderFooter da apresentação. |
| [getProtectionManager()](#getProtectionManager--) | Obtém o gerenciador das permissões para esta apresentação. |
| [getSlides()](#getSlides--) | Retorna uma lista de todos os slides definidos na apresentação. |
| [getSections()](#getSections--) | Retorna uma lista de todas as seções de slides definidas na apresentação. |
| [getSlideSize()](#getSlideSize--) | Retorna o objeto de tamanho do slide. |
| [getNotesSize()](#getNotesSize--) | Retorna o objeto de tamanho do slide de notas. |
| [getLayoutSlides()](#getLayoutSlides--) | Retorna uma lista de todos os slides de layout definidos na apresentação. |
| [getMasters()](#getMasters--) | Retorna uma lista de todos os slides mestre definidos na apresentação. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Retorna o gerenciador do mestre de notas. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Retorna o gerenciador do mestre de folhetos. |
| [getFontsManager()](#getFontsManager--) | Retorna o gerenciador de fontes. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Retorna o estilo de texto padrão para formas. |
| [getCommentAuthors()](#getCommentAuthors--) | Retorna a coleção de autores de comentários. |
| [getDocumentProperties()](#getDocumentProperties--) | Retorna o objeto DocumentProperties que contém propriedades de documento padrão e personalizadas. |
| [getImages()](#getImages--) | Retorna a coleção de todas as imagens na apresentação. |
| [getAudios()](#getAudios--) | Retorna a coleção de todos os arquivos de áudio incorporados na apresentação. |
| [getVideos()](#getVideos--) | Retorna a coleção de todos os arquivos de vídeo incorporados na apresentação. |
| [getCustomData()](#getCustomData--) | Retorna os dados personalizados da apresentação. |
| [getVbaProject()](#getVbaProject--) | Obtém o projeto VBA com macros da apresentação. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Obtém o projeto VBA com macros da apresentação. |
| [getSourceFormat()](#getSourceFormat--) | Retorna informações sobre o formato a partir do qual a apresentação foi carregada. |
| [getMasterTheme()](#getMasterTheme--) | Retorna o tema mestre da apresentação. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fornece acesso fácil a todos os hiperlinks contidos em todos os slides da apresentação (exceto em mestre, layout e slides de notas). |
| [getViewProperties()](#getViewProperties--) | Obtém as propriedades de visualização de toda a apresentação. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Representa o número do primeiro slide na apresentação. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Representa o número do primeiro slide na apresentação. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Retorna todas as partes de dados personalizados na apresentação. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Retorna a coleção de assinaturas usadas para assinar a apresentação. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Retorna a coleção de rótulos de sensibilidade aplicados ao documento da apresentação. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Salva todos os slides de uma apresentação em um arquivo com o formato especificado. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Salva todos os slides de uma apresentação em um fluxo no formato especificado. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Salva todos os slides de uma apresentação em um arquivo com o formato especificado e com opções adicionais. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Salva todos os slides de uma apresentação em um fluxo no formato especificado e com opções adicionais. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Salva slides especificados de uma apresentação em um arquivo com o formato especificado. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Salva slides especificados de uma apresentação em um arquivo com o formato especificado. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Salva slides especificados de uma apresentação em um fluxo no formato especificado. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Salva slides especificados de uma apresentação em um fluxo no formato especificado. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Salva todos os slides de uma apresentação em um conjunto de arquivos que representam marcação XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Retorna objetos de imagem miniatura para todos os slides de uma apresentação. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Retorna objetos IImage em miniatura para slides especificados de uma apresentação. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Retorna objetos de imagem miniatura para todos os slides de uma apresentação com dimensionamento personalizado. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Retorna objetos de imagem miniatura para slides especificados de uma apresentação com dimensionamento personalizado. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Retorna objetos de imagem miniatura para todos os slides de uma apresentação com tamanho especificado. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Retorna objetos de imagem miniatura para slides especificados de uma apresentação com tamanho especificado. |
| [getSlideById(long id)](#getSlideById-long-) | Retorna um Slide, MasterSlide ou LayoutSlide por Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Junta execuções com a mesma formatação em todos os parágrafos em todas as formas aceitáveis em todos os slides. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Destaca todas as correspondências do texto de amostra com a cor especificada. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Destaca todas as correspondências do texto de amostra com a cor especificada. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Destaca todas as correspondências da expressão regular com a cor especificada. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Substitui todas as ocorrências do texto especificado por outro texto especificado. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Substitui todas as correspondências da expressão regular pela string especificada. |
### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Retorna ou define a data e hora que substituirá o conteúdo dos campos datetime. Hora de criação deste objeto Presentation por padrão. Leitura/gravação java.util.Date.

**Retorna:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Retorna ou define a data e hora que substituirá o conteúdo dos campos datetime. Hora de criação deste objeto Presentation por padrão. Leitura/gravação java.util.Date.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.util.Date |  |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Retorna o gerenciador HeaderFooter da apresentação. Somente leitura [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Retorna:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Obtém o gerenciador das permissões para esta apresentação. Somente leitura [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Retorna:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Retorna uma lista de todos os slides definidos na apresentação. Somente leitura [ISlideCollection](../../com.aspose.slides/islidecollection).

**Retorna:**
[ISlideCollection](../../com.aspose.slides/islidecollection)
### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Retorna uma lista de todas as seções de slides definidas na apresentação. Somente leitura [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Retorna:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)
### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Retorna o objeto de tamanho do slide. Somente leitura [ISlideSize](../../com.aspose.slides/islidesize).

**Retorna:**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Retorna o objeto de tamanho do slide de notas. Somente leitura [INotesSize](../../com.aspose.slides/inotessize).

**Retorna:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Retorna uma lista de todos os slides de layout definidos na apresentação. Somente leitura [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Você pode acessar a API alternativa para adicionar/inserir/remover/clonar slides de layout usando a propriedade IMasterSlide.LayoutSlides.

**Retorna:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Retorna uma lista de todos os slides mestre definidos na apresentação. Somente leitura [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Retorna:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Retorna o gerenciador do mestre de notas. Somente leitura [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Retorna:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Retorna o gerenciador do mestre de folhetos. Somente leitura [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Retorna:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Retorna o gerenciador de fontes. Somente leitura [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Retorna:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Retorna o estilo de texto padrão para formas. Somente leitura [ITextStyle](../../com.aspose.slides/itextstyle).

**Retorna:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Retorna a coleção de autores de comentários. Somente leitura [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Retorna:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Retorna o objeto DocumentProperties que contém propriedades de documento padrão e personalizadas. Somente leitura [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Retorna:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Retorna a coleção de todas as imagens na apresentação. Somente leitura [IImageCollection](../../com.aspose.slides/iimagecollection).

**Retorna:**
[IImageCollection](../../com.aspose.slides/iimagecollection)
### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Retorna a coleção de todos os arquivos de áudio incorporados na apresentação. Somente leitura [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Retorna:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Retorna a coleção de todos os arquivos de vídeo incorporados na apresentação. Somente leitura [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Retorna:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Retorna os dados personalizados da apresentação. Somente leitura [ICustomData](../../com.aspose.slides/icustomdata).

**Retorna:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Obtém o projeto VBA com macros da apresentação. Leitura/gravação [IVbaProject](../../com.aspose.slides/ivbaproject).

**Retorna:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Obtém o projeto VBA com macros da apresentação. Leitura/gravação [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |
### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Retorna informações sobre o formato a partir do qual a apresentação foi carregada. Somente leitura [SourceFormat](../../com.aspose.slides/sourceformat).

**Retorna:**
int
### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Retorna o tema mestre da apresentação. Somente leitura [IMasterTheme](../../com.aspose.slides/imastertheme).

**Retorna:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Fornece acesso fácil a todos os hiperlinks contidos em todos os slides da apresentação (não nos slides mestre, de layout ou de notas). Somente leitura [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Retorna:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Obtém as propriedades de visualização de toda a apresentação. Somente leitura [IViewProperties](../../com.aspose.slides/iviewproperties).

**Retorna:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

Representa o número do primeiro slide na apresentação. Leitura/gravação int.

**Retorna:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

Representa o número do primeiro slide na apresentação. Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Retorna todas as partes de dados personalizados na apresentação. Somente leitura ICustomXmlPart[].

**Retorna:**
com.aspose.slides.ICustomXmlPart[]
### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Retorna a coleção de assinaturas usadas para assinar a apresentação. Somente leitura [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                    + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

Retorna a coleção de rótulos de sensibilidade aplicados ao documento da apresentação. Somente leitura [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Imprime os rótulos aplicados
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Adiciona o novo rótulo
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Obtém o Id do rótulo de sensibilidade da política
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Obtém o identificador do site Azure AD da política
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```

**Retorna:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

Salva todos os slides de uma apresentação em um arquivo com o formato especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fname | java.lang.String | Caminho para o arquivo criado. |
| format | int | Formato dos dados exportados. |
### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Salva todos os slides de uma apresentação em um fluxo no formato especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | Fluxo de saída. |
| format | int | Formato dos dados exportados. |
### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

Salva todos os slides de uma apresentação em um arquivo com o formato especificado e com opções adicionais.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fname | java.lang.String | Caminho para o arquivo criado. |
| format | int | Formato dos dados exportados. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opções adicionais de formato. |
### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Salva todos os slides de uma apresentação em um fluxo no formato especificado e com opções adicionais.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | Fluxo de saída. |
| format | int | Formato dos dados exportados. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opções adicionais de formato. |
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

Salva slides especificados de uma apresentação em um arquivo com o formato especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fname | java.lang.String | Caminho para o arquivo criado. |
| slides | int[] | Array com posições dos slides, começando em 1. |
| format | int | Formato dos dados exportados. |
### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISSaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Salva slides especificados de uma apresentação em um arquivo com o formato especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fname | java.lang.String | Caminho para o arquivo criado. |
| slides | int[] | Array com posições dos slides, começando em 1. |
| format | int | Formato dos dados exportados. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opções adicionais de formato. |
### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Salva slides especificados de uma apresentação em um fluxo no formato especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | Fluxo de saída. |
| slides | int[] | Array com posições dos slides, começando em 1. |
| format | int | Formato dos dados exportados. |
### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISSaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Salva slides especificados de uma apresentação em um fluxo no formato especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | Fluxo de saída. |
| slides | int[] | Array com posições dos slides, começando em 1. |
| format | int | Formato dos dados exportados. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opções adicionais de formato. |
### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

Salva todos os slides de uma apresentação em um conjunto de arquivos que representam marcação XAML.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | As opções de formato XAML. |
### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

Retorna objetos de imagem miniatura para todos os slides da apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opções de renderização. |
**Retorna:**
com.aspose.slides.IImage[] - objetos IImage.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Retorna objetos IImage em miniatura para slides especificados da apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opções de renderização. |
| slides | int[] | Array com posições dos slides, começando em 1. |
**Retorna:**
com.aspose.slides.IImage[] - objetos IImage.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Retorna objetos IImage em miniatura para todos os slides da apresentação com dimensionamento personalizado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opções de renderização. |
| scaleX | float | Valor pelo qual dimensionar esta miniatura no eixo X. |
| scaleY | float | Valor pelo qual dimensionar esta miniatura no eixo Y. |
**Retorna:**
com.aspose.slides.IImage[] - objetos Bitmap.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Retorna objetos IImage em miniatura para slides especificados da apresentação com dimensionamento personalizado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opções de renderização. |
| slides | int[] | Array com posições dos slides, começando em 1. |
| scaleX | float | Valor pelo qual dimensionar esta miniatura no eixo X. |
| scaleY | float | Valor pelo qual dimensionar esta miniatura no eixo Y. |
**Retorna:**
com.aspose.slides.IImage[] - objetos IImage.
### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Retorna objetos de imagem miniatura para todos os slides da apresentação com tamanho especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opções de renderização. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Tamanho da imagem a ser criada. |
**Retorna:**
com.aspose.slides.IImage[] - objetos IImage.
### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Retorna objetos de imagem miniatura para slides especificados da apresentação com tamanho especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opções de renderização. |
| slides | int[] | Array com posições dos slides, começando em 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Tamanho da imagem a ser criada. |
**Retorna:**
com.aspose.slides.IImage[] - objetos IImage.
### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Retorna um Slide, MasterSlide ou LayoutSlide por Id.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| id | long | Id de um slide. |
**Retorna:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Junta execuções com a mesma formatação em todos os parágrafos em todas as formas aceitáveis em todos os slides.
### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Destaca todas as correspondências do texto de amostra com a cor especificada.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // destacando todas as ocorrências distintas de 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | O texto a ser destacado. |
| highlightColor | java.lang.Integer | A cor para destacar o texto. |
### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Destaca todas as correspondências do texto de amostra com a cor especificada.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // destacando todas as ocorrências distintas de 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | O texto a ser destacado. |
| highlightColor | java.lang.Integer | A cor para destacar o texto. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opções de busca de texto [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | O objeto de retorno de chamada para receber resultados de busca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Destaca todas as correspondências da expressão regular com a cor especificada.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // destacando todas as ocorrências distintas de 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| regex | java.util.regex.Pattern | A expressão regular java.util.regex.Pattern para obter strings a serem destacadas. |
| highlightColor | java.lang.Integer | A cor para destacar o texto. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | O objeto de retorno de chamada para receber resultados de busca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Substitui todas as ocorrências do texto especificado por outro texto especificado.

--------------------

> ```
> O código de exemplo a seguir mostra como substituir uma string especificada por outra string especificada.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Substitui todas as ocorrências distintas de 'the' por '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| oldText | java.lang.String | A string a ser substituída. |
| newText | java.lang.String | A string para substituir todas as ocorrências de oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opções de busca de texto [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | O objeto de retorno de chamada para receber resultados de busca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Substitui todas as correspondências da expressão regular pela string especificada.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Substitui todas as ocorrências distintas de 'the' por '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| regex | java.util.regex.Pattern | A expressão regular java.util.regex.Pattern para obter strings a serem substituídas. |
| newText | java.lang.String | A string para substituir todas as ocorrências das strings a serem substituídas. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | O objeto de retorno de chamada para receber resultados de busca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback).