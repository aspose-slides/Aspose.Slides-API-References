---
title: IBlobManagementOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Um objeto binário grande (BLOB) é um dado binário armazenado como uma única entidade - i.e.
type: docs
url: /pt/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Um objeto binário grande (BLOB) é um dado binário armazenado como uma única entidade - i.e. BLOB pode ser um áudio, vídeo ou a própria apresentação. Várias técnicas são usadas para otimizar o consumo de memória ao trabalhar com BLOBs - que já estavam armazenados na apresentação ou podem ser adicionados posteriormente programaticamente. Usando [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) você pode alterar diferentes aspectos de comportamento relacionados ao manuseio de BLOBs para a instância [IPresentation](../../com.aspose.slides/ipresentation).

## Métodos

| Método | Descrição |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Esta propriedade define se uma instância da classe Presentation pode ser proprietária da fonte - arquivo ou fluxo durante a vida útil da instância. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Esta propriedade define se uma instância da classe Presentation pode ser proprietária da fonte - arquivo ou fluxo durante a vida útil da instância. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Esta propriedade define se arquivos temporários podem ser criados ao trabalhar com BLOBs, o que diminui drasticamente o consumo de memória, mas requer permissões para criar arquivos. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Esta propriedade define se arquivos temporários podem ser criados ao trabalhar com BLOBs, o que diminui drasticamente o consumo de memória, mas requer permissões para criar arquivos. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | O caminho raiz onde arquivos temporários serão criados. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | O caminho raiz onde arquivos temporários serão criados. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Esta propriedade define se uma instância da classe Presentation pode ser proprietária da fonte - arquivo ou fluxo durante a vida útil da instância. Se a instância for proprietária, ela bloqueia a fonte. Isso ajuda a melhorar o consumo de memória e o desempenho ao trabalhar com BLOBs, mas a fonte (fluxo ou arquivo) não pode ser alterada durante a vida útil da instância Presentation. Este é um exemplo:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException será lançada porque pres.pptx está bloqueado por toda a vida da Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // após o objeto Presentation ser descartado, o arquivo é desbloqueado e pode ser excluído
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Retorna:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Esta propriedade define se uma instância da classe Presentation pode ser proprietária da fonte - arquivo ou fluxo durante a vida útil da instância. Se a instância for proprietária, ela bloqueia a fonte. Isso ajuda a melhorar o consumo de memória e o desempenho ao trabalhar com BLOBs, mas a fonte (fluxo ou arquivo) não pode ser alterada durante a vida útil da instância Presentation. Este é um exemplo:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException será lançada porque pres.pptx está bloqueado por toda a vida da Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // após o objeto Presentation ser descartado, o arquivo é desbloqueado e pode ser excluído
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

Esta propriedade define se arquivos temporários podem ser criados ao trabalhar com BLOBs, o que diminui drasticamente o consumo de memória, mas requer permissões para criar arquivos.

--------------------

Todos os arquivos serão deletados após a conclusão do trabalho com a apresentação.

**Retorna:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

Esta propriedade define se arquivos temporários podem ser criados ao trabalhar com BLOBs, o que diminui drasticamente o consumo de memória, mas requer permissões para criar arquivos.

--------------------

Todos os arquivos serão deletados após a conclusão do trabalho com a apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

O caminho raiz onde arquivos temporários serão criados. O diretório temporário do sistema será usado por padrão. O processo de hospedagem deve ter permissões para criar arquivos e pastas nele.

**Retorna:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

O caminho raiz onde arquivos temporários serão criados. O diretório temporário do sistema será usado por padrão. O processo de hospedagem deve ter permissões para criar arquivos e pastas nele.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. Por padrão, todos os BLOBs são carregados na memória; somente quando esse limite é atingido mecanismos alternativos (como arquivos temporários) são empregados. Manter BLOBs na memória maximiza o desempenho, mas pode gerar alto uso de memória. Use esta propriedade para ajustar o comportamento ao seu ambiente ou requisitos.

--------------------

Esta propriedade é ignorada se \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) for definido como false, já que a memória passa a ser o único local de armazenamento disponível e limitar o uso de BLOBs em memória não tem efeito.

--------------------

O valor padrão é 629.145.600 bytes (600 MB).

--------------------

Você pode definir esta propriedade como zero, mas ainda será reservada uma pequena quantidade mínima de memória.

**Retorna:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. Por padrão, todos os BLOBs são carregados na memória; somente quando esse limite é atingido mecanismos alternativos (como arquivos temporários) são empregados. Manter BLOBs na memória maximiza o desempenho, mas pode gerar alto uso de memória. Use esta propriedade para ajustar o comportamento ao seu ambiente ou requisitos.

--------------------

Esta propriedade é ignorada se \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) for definido como false, já que a memória passa a ser o único local de armazenamento disponível e limitar o uso de BLOBs em memória não tem efeito.

--------------------

O valor padrão é 629.145.600 bytes (600 MB).

--------------------

Você pode definir esta propriedade como zero, mas ainda será reservada uma pequena quantidade mínima de memória.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |