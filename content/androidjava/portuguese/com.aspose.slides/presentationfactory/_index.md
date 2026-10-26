---
title: PresentationFactory
second_title: Aspose.Slides para Android via Referência da API Java
description: Permite criar apresentação via interface COM
type: docs
url: /pt/com.aspose.slides/presentationfactory/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

Permite criar apresentações via interface COM

--------------------

> ```
> The following example shows how to checking a Presentation Format.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  System.out.println(info.getLoadFormat()); // PPTX
>  IPresentationInfo info2 = PresentationFactory.getInstance().getPresentationInfo("pres.ppt");
>  System.out.println(info2.getLoadFormat()); // PPT
>  IPresentationInfo info3 = PresentationFactory.getInstance().getPresentationInfo("pres.odp");
>  System.out.println(info3.getLoadFormat()); // ODP
>  
>  The following example shows how to getting the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  System.out.println(props.getCreatedTime());
>  System.out.println(props.getSubject());
>  System.out.println(props.getTitle());
>  // ..
>  
>  The following example shows how to updating the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setTitle("My title");
>  info.updateDocumentProperties(props);
> ```
## Construtores

| Construtor | Descrição |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [getInstance()](#getInstance--) | Instância estática da fábrica de apresentações. |
| [createPresentation()](#createPresentation--) | Cria uma nova apresentação. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Cria uma nova apresentação com opções de carregamento adicionais |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Cria um objeto PresentationInfo a partir de um arquivo e vincula a apresentação a ele. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Cria um objeto PresentationInfo a partir de um fluxo e vincula a apresentação a ele. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Lê uma apresentação existente a partir de um array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Lê uma apresentação existente a partir de um array com opções de carregamento adicionais |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Lê uma apresentação existente a partir de um fluxo |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Lê uma apresentação existente a partir de um fluxo com opções de carregamento adicionais |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Lê uma apresentação existente a partir de um arquivo |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Lê uma apresentação existente a partir de um fluxo com opções de carregamento adicionais |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Recupera o texto bruto dos slides |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Recupera o texto bruto dos slides |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Recupera o texto bruto dos slides |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```

### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```

Instância estática da fábrica de apresentações. Somente leitura [PresentationFactory](../../com.aspose.slides/presentationfactory).

**Retorna:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```

Cria uma nova apresentação.

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nova apresentação
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```

Cria uma nova apresentação com opções de carregamento adicionais

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opções de carregamento |

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nova apresentação
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```

Cria um novo objeto PresentationInfo a partir de um arquivo e vincula a apresentação a ele.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| file | java.lang.String | Arquivo da apresentação. |

**Retorna:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informação da apresentação vinculada à apresentação.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```

Cria um novo objeto PresentationInfo a partir de um fluxo e vincula a apresentação a ele. Obtém informações sobre a apresentação no fluxo especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Fluxo da apresentação. |

**Retorna:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informação da apresentação vinculada à apresentação.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```

Lê uma apresentação existente a partir de um array

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | byte[] | Array a ser lido |

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation) - Apresentação lida
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```

Lê uma apresentação existente a partir de um array com opções de carregamento adicionais

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | byte[] | Array a ser lido |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opções de carregamento |

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation) - Apresentação lida
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```

Lê uma apresentação existente a partir de um fluxo

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Fluxo de entrada a ser lido |

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation) - Apresentação lida
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Lê uma apresentação existente a partir de um fluxo com opções de carregamento adicionais

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Fluxo de entrada a ser lido |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opções de carregamento |

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation) - Apresentação lida
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```

Lê uma apresentação existente a partir de um arquivo

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| file | java.lang.String | Nome do arquivo |

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation) - Apresentação lida
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(String file, ILoadOptions options)
```

Lê uma apresentação existente a partir de um stream com opções de carregamento adicionais

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| file | java.lang.String | Nome do arquivo |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opções de carregamento |

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation) - Apresentação lida
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```

Recupera o texto bruto dos slides

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| file | java.lang.String | Arquivo de entrada |
| mode | int | Modo de extração |

**Retorna:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - A instância de PresentationText contendo o array SlideText representando o texto bruto dos slides
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```

Recupera o texto bruto dos slides

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Fluxo de entrada |
| mode | int | Modo de extração |

**Retorna:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - A instância de PresentationText contendo o array SlideText representando o texto bruto dos slides
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

Recupera o texto bruto dos slides

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Fluxo de entrada |
| mode | int | Modo de extração |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opções de carregamento |

**Retorna:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - A instância de PresentationText contendo o array SlideText representando o texto bruto dos slides