---
title: IPresentationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Permite criar apresentação via interface COM
type: docs
url: /pt/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

Permite criar apresentação via interface COM.

## Métodos

| Método | Descrição |
| --- | --- |
| [createPresentation()](#createPresentation--) | Cria nova apresentação. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Cria nova apresentação com opções de carregamento adicionais |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Obtém informações sobre a apresentação no arquivo especificado. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Obtém informações sobre a apresentação no stream especificado. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Lê uma apresentação existente a partir de um array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Lê uma apresentação existente a partir de um array com opções de carregamento adicionais |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Lê uma apresentação existente a partir de um stream |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Lê uma apresentação existente a partir de um stream com opções de carregamento adicionais |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Lê uma apresentação existente a partir de um arquivo |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Lê uma apresentação existente a partir de um stream com opções de carregamento adicionais |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Recupera o texto bruto dos slides |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Recupera o texto bruto dos slides |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Recupera o texto bruto dos slides |

### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```

Cria nova apresentação.

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nova apresentação

### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
```

Cria nova apresentação com opções de carregamento adicionais

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opções de carregamento |

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nova apresentação

### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public abstract IPresentationInfo getPresentationInfo(String file)
```

Obtém informações sobre a apresentação no arquivo especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| file | java.lang.String | Arquivo de apresentação. |

**Retorna:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informações da apresentação

### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```

Obtém informações sobre a apresentação no stream especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Stream da apresentação. |

**Retorna:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informações da apresentação.

### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
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
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
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
public abstract IPresentation readPresentation(InputStream stream)
```

Lê uma apresentação existente a partir de um stream

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Stream de entrada a ser lido |

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation) - Apresentação lida

### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Lê uma apresentação existente a partir de um stream com opções de carregamento adicionais

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Stream de entrada a ser lido |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opções de carregamento |

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation) - Apresentação lida

### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
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
public abstract IPresentation readPresentation(String file, ILoadOptions options)
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
public abstract IPresentationText getPresentationText(String file, int mode)
```

Recupera o texto bruto dos slides

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| file | java.lang.String | Arquivo de entrada |
| mode | int | Modo de extração |

**Retorna:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - A instância de PresentationText contendo o array SlideText que representa o texto bruto dos slides

### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```

Recupera o texto bruto dos slides

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Stream de entrada |
| mode | int | Modo de extração |

**Retorna:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - A instância de PresentationText contendo o array SlideText que representa o texto bruto dos slides

### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

Recupera o texto bruto dos slides

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Stream de entrada |
| mode | int | Modo de extração |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opções de carregamento |

**Retorna:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - A instância de PresentationText contendo o array SlideText que representa o texto bruto dos slides