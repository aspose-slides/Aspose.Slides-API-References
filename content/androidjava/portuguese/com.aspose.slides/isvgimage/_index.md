---
title: ISvgImage
second_title: Aspose.Slides for Android via Java API Reference
description: Representa uma imagem SVG.
type: docs
url: /pt/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Representa uma imagem SVG.
## Métodos

| Método | Descrição |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | Retorna o conteúdo SVG. |
| [getSvgData()](#getSvgData--) | Retorna os dados SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Retorna a interface de callback usada para resolver recursos externos durante a importação de documentos SVG. |
| [getBaseUri()](#getBaseUri--) | Retorna o URI base do SVG especificado. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Salva a imagem SVG como um arquivo EMF. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```

Retorna o conteúdo SVG. Somente leitura String.

**Retorna:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```

Retorna os dados SVG. Somente leitura byte[].

**Retorna:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```

Retorna a interface de callback usada para resolver recursos externos durante a importação de documentos SVG. Somente leitura [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Retorna:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```

Retorna o URI base do SVG especificado. Usado para resolver links relativos. Somente leitura String.

**Retorna:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

Salva a imagem SVG como um arquivo EMF.

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
>  
>  // Cria a nova imagem SVG
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Salva a imagem SVG como um arquivo Metafile
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
>      // Salva a imagem SVG como um arquivo Metafile
>      svgImage.writeAsEmf(byteStream);
>      // Adiciona o Metafile à coleção de imagens
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | Fluxo de destino |