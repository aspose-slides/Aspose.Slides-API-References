---
title: BlobManagementOptions
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa opções que podem ser usadas para gerenciar regras de manipulação de BLOB e outras configurações de BLOB.
type: docs
url: /pt/com.aspose.slides/blobmanagementoptions/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

Representa opções que podem ser usadas para gerenciar regras de manipulação de BLOB e outras configurações de BLOB.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Cria novas opções de gerenciamento de blob padrão. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Esta propriedade define se uma instância da classe Presentation pode ser proprietária da fonte – arquivo ou fluxo durante a vida útil da instância. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Esta propriedade define se uma instância da classe Presentation pode ser proprietária da fonte – arquivo ou fluxo durante a vida útil da instância. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Esta propriedade define se arquivos temporários podem ser criados ao trabalhar com BLOBs, o que diminui drasticamente o consumo de memória, mas requer permissões para criar arquivos. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Esta propriedade define se arquivos temporários podem ser criados ao trabalhar com BLOBs, o que diminui drasticamente o consumo de memória, mas requer permissões para criar arquivos. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | O caminho raiz onde os arquivos temporários serão criados. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | O caminho raiz onde os arquivos temporários serão criados. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. |
### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

Cria novas opções de gerenciamento de blob padrão.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

Esta propriedade define se uma instância da classe Presentation pode ser proprietária da fonte – arquivo ou fluxo durante a vida útil da instância. Se a instância for proprietária, ela bloqueia a fonte. Isso ajuda a melhorar o consumo de memória e o desempenho ao trabalhar com BLOBs, mas a fonte (fluxo ou arquivo) não pode ser alterada durante a vida útil da instância da Presentation.

**Retorna:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

Esta propriedade define se uma instância da classe Presentation pode ser proprietária da fonte – arquivo ou fluxo durante a vida útil da instância. Se a instância for proprietária, ela bloqueia a fonte. Isso ajuda a melhorar o consumo de memória e o desempenho ao trabalhar com BLOBs, mas a fonte (fluxo ou arquivo) não pode ser alterada durante a vida útil da instância da Presentation.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

Esta propriedade define se arquivos temporários podem ser criados ao trabalhar com BLOBs, o que diminui drasticamente o consumo de memória, mas requer permissões para criar arquivos.

--------------------

Todos os arquivos serão deletados após o término do trabalho com a apresentação.

**Retorna:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

Esta propriedade define se arquivos temporários podem ser criados ao trabalhar com BLOBs, o que diminui drasticamente o consumo de memória, mas requer permissões para criar arquivos.

--------------------

Todos os arquivos serão deletados após o término do trabalho com a apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

O caminho raiz onde os arquivos temporários serão criados. O diretório temporário do sistema será usado por padrão. O processo de hospedagem deve ter permissões para criar arquivos e pastas lá.

**Retorna:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

O caminho raiz onde os arquivos temporários serão criados. O diretório temporário do sistema será usado por padrão. O processo de hospedagem deve ter permissões para criar arquivos e pastas lá.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. Por padrão, todos os BLOBs são carregados na memória; somente quando esse limite é alcançado são empregados mecanismos alternativos (como arquivos temporários). Manter os BLOBs na memória maximiza o desempenho, mas pode levar a alto consumo de memória. Use esta propriedade para ajustar o comportamento ao seu ambiente ou requisitos.

--------------------

Esta propriedade é ignorada se \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) estiver definido como false, já que a memória será então o único local de armazenamento disponível e limitar o uso de BLOBs na memória não terá efeito.

--------------------

O valor padrão é 629.145.600 bytes (600 MB).

--------------------

Você pode definir esta propriedade como zero, mas ainda será reservada uma pequena quantidade mínima de memória.

**Retorna:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. Por padrão, todos os BLOBs são carregados na memória; somente quando esse limite é alcançado são empregados mecanismos alternativos (como arquivos temporários). Manter os BLOBs na memória maximiza o desempenho, mas pode levar a alto consumo de memória. Use esta propriedade para ajustar o comportamento ao seu ambiente ou requisitos.

--------------------

Esta propriedade é ignorada se \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) estiver definido como false, já que a memória será então o único local de armazenamento disponível e limitar o uso de BLOBs na memória não terá efeito.

--------------------

O valor padrão é 629.145.600 bytes (600 MB).

--------------------

Você pode definir esta propriedade como zero, mas ainda será reservada uma pequena quantidade mínima de memória.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |