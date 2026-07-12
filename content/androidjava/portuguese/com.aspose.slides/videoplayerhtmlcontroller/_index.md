---
title: VideoPlayerHtmlController
second_title: Aspose.Slides para Android via Referência da API Java
description: Esta classe permite a exportação de arquivos de vídeo e áudio para um HTML
type: docs
url: /pt/com.aspose.slides/videoplayerhtmlcontroller/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IVideoPlayerHtmlController](../../com.aspose.slides/ivideoplayerhtmlcontroller)
```
public class VideoPlayerHtmlController implements IVideoPlayerHtmlController
```

Esta classe permite a exportação de arquivos de vídeo e áudio para um HTML
## Construtores

| Construtor | Descrição |
| --- | --- |
| [VideoPlayerHtmlController(String path, String fileName, String baseUri)](#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-) | Cria uma nova instância do controlador |
## Métodos

| Método | Descrição |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) |  |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) |  |
| [getUrl(int id, int referrer)](#getUrl-int-int-) |  |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) |  |
### VideoPlayerHtmlController(String path, String fileName, String baseUri) {#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-}
```
public VideoPlayerHtmlController(String path, String fileName, String baseUri)
```


Cria uma nova instância do controlador

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | java.lang.String | O caminho onde os arquivos de vídeo e áudio serão gerados |
| fileName | java.lang.String | O nome do arquivo HTML |
| baseUri | java.lang.String | O URI base que será usado para gerar links |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Chamado para escrever o cabeçalho do documento HTML. Chamado uma vez por conversão de apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Chamado para escrever o rodapé do documento HTML. Chamado uma vez por conversão de apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Chamado para escrever o cabeçalho do slide HTML. Chamado uma vez por cada slide.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Chamado para escrever o rodapé do slide HTML. Chamado uma vez por cada slide.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Chamado antes da renderização da forma. Chamado uma vez por cada forma. Se esta função escrever algo no gerador, a geração da imagem do slide atual será finalizada, o fragmento HTML adicionado será inserido e uma nova imagem será iniciada sobre a anterior.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Chamado antes da renderização da forma. Chamado uma vez por cada forma. Se esta função escrever algo no gerador, a geração da imagem do slide atual será finalizada, o fragmento HTML adicionado será inserido e uma nova imagem será iniciada sobre a anterior.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public final void formatShape(ISvgShape svgShape, IShape shape)
```


Esta função é chamada antes da renderização da forma para SVG para permitir que o usuário controle o SVG resultante.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public final int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Determina onde o objeto deve ser armazenado. Este método é chamado uma vez para cada ID de objeto. Não há garantia de que não existam dois objetos com os mesmos dados, semanticName e contentType, mas com IDs diferentes.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |
| semanticName | java.lang.String |  |
| contentType | java.lang.String |  |
| recomendedExtension | java.lang.String |  |

**Retorna:**
int
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public final String getUrl(int id, int referrer)
```


Retorna uma URL para um objeto externo. Este método sempre é chamado se #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) retornou [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) e pode ser chamado se #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) retornou [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) mas a incorporação é impossível. Pode ser chamado várias vezes para o mesmo ID de objeto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| id | int |  |
| referrer | int |  |

**Retorna:**
java.lang.String
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public final void saveExternal(int id, byte[] entityData)
```


Salva o objeto externo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |