---
title: SvgImage
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma imagem SVG.
type: docs
url: /pt/com.aspose.slides/svgimage/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

Representa uma imagem SVG.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | Cria um novo objeto SvgImage. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | Cria um novo objeto SvgImage. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Cria um novo objeto SvgImage. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Cria um novo objeto SvgImage. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Cria um novo objeto SvgImage. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Cria um novo objeto SvgImage. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getSvgData()](#getSvgData--) | Retorna os dados SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Retorna a interface de callback usada para resolver recursos externos durante a importação de documentos Svg. |
| [getBaseUri()](#getBaseUri--) | Retorna a URI base do SVG especificado. |
| [getSvgContent()](#getSvgContent--) | Retorna o conteúdo SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Salva a imagem SVG como um arquivo EMF. |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```


Cria um novo objeto SvgImage.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | byte[] | Dados SVG. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```


Cria um novo objeto SvgImage.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| svgContent | java.lang.String | Conteúdo SVG. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```


Cria um novo objeto SvgImage.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Fluxo SVG. |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```


Cria um novo objeto SvgImage.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | byte[] | Dados SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Um objeto de callback usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| baseUri | java.lang.String | URI base do SVG especificado. Usada para resolver links relativos. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```


Cria um novo objeto SvgImage.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| svgContent | java.lang.String | Conteúdo SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Um objeto de callback usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| baseUri | java.lang.String | URI base do SVG especificado. Usada para resolver links relativos. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```


Cria um novo objeto SvgImage.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Fluxo SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Um objeto de callback usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| baseUri | java.lang.String | URI base do SVG especificado. Usada para resolver links relativos. |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```


Retorna os dados SVG. Somente leitura byte[].

**Retorna:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```


Retorna a interface de callback usada para resolver recursos externos durante a importação de documentos Svg. Somente leitura [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Retorna:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```


Retorna a URI base do SVG especificado. Usada para resolver links relativos. Somente leitura String.

**Retorna:**
java.lang.String
### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```


Retorna o conteúdo SVG. Somente leitura String.

**Retorna:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```


Salva a imagem SVG como um arquivo EMF.

--------------------

> ```
> The following example shows how to save the SVG image to the metafile.
>  
>  // Cria a nova imagem SVG
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Salva a imagem SVG como um metafille
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Cria a nova imagem SVG
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Salva a imagem SVG como um metafille
>      svgImage.writeAsEmf(byteStream);
>      // Adiciona o metafile à coleção de imagens
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | Fluxo de destino |