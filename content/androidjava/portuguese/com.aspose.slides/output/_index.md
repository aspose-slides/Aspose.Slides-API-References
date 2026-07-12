---
title: Output
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de elementos de saída para IWebDocument.
type: docs
url: /pt/com.aspose.slides/output/
---
**Herança:**
java.lang.Object
```
public final class Output
```

Representa uma coleção de elementos de saída para IWebDocument.
## Métodos

| Método | Descrição |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Adiciona um elemento de saída para o objeto de contexto. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Adiciona um elemento de saída para a imagem. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Adiciona um elemento de saída para a imagem. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Adiciona um elemento de saída para o vídeo. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Cria e adiciona um elemento de arquivo de saída para a fonte especificada. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Adiciona um elemento de saída para o conteúdo de texto. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Associa recurso ao arquivo de saída. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Retorna o caminho para um recurso dado. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```


Adiciona um elemento de saída para o objeto de contexto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | java.lang.String | Caminho de saída. |
| templateKey | java.lang.String | A chave do modelo usado para a transformação do objeto de contexto antes da saída. |
| contextObject | TContextObject | Objeto de contexto. |

**Retorna:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objeto para o objeto de contexto.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```


Adiciona um elemento de saída para a imagem.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | java.lang.String | Caminho de saída. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Imagem a ser exportada. |

**Retorna:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objeto para a imagem.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```


Adiciona um elemento de saída para a imagem.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | java.lang.String | Caminho de saída. |
| image | [IImage](../../com.aspose.slides/iimage) | Imagem a ser exportada. |

**Retorna:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objeto para a imagem.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```


Adiciona um elemento de saída para o vídeo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | java.lang.String | Caminho de saída. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Vídeo a ser exportado. |

**Retorna:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objeto para o vídeo.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```


Cria e adiciona um elemento de arquivo de saída para a fonte especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | java.lang.String | O caminho do arquivo onde a saída da fonte será salva. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Os dados da fonte a serem gravados na saída. |
| fontStyle | int | O estilo da fonte (por exemplo, Regular, Bold, Italic). |

**Retorna:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - Uma instância [IOutputFile](../../com.aspose.slides/ioutputfile) para a fonte gerada.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```


Adiciona um elemento de saída para o conteúdo de texto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | java.lang.String | Caminho de saída. |
| textContent | java.lang.String | Conteúdo a ser exportado. |

**Retorna:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objeto para o conteúdo de texto.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```


Associa recurso ao arquivo de saída.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Arquivo de saída. |
| obj | java.lang.Object | Objeto de recurso. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```


Retorna o caminho para um recurso dado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | Objeto de recurso. |

**Retorna:**
java.lang.String - Caminho do recurso.