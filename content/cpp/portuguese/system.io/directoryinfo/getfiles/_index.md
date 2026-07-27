---
title: GetFiles()
second_title: Referência da API Aspose.Slides para C++
description: Retorna uma matriz contendo ponteiros compartilhados para objetos FileInfo que representam todos os diretórios localizados no diretório representado pelo objeto atual.
type: docs
weight: 157
url: /pt/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() método

Retorna uma matriz contendo ponteiros compartilhados para objetos [FileInfo](../../fileinfo/) que representam todos os diretórios localizados no diretório representado pelo objeto atual.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) método

Pesquisa os arquivos que atendem ao critério de busca especificado no diretório representado pelo objeto atual.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | O padrão de nome dos arquivos a serem procurados |

### Valor de Retorno

Uma matriz de ponteiros compartilhados para objetos [FileInfo](../../fileinfo/) que representam os arquivos encontrados cujos nomes correspondem a **searchPattern**

## DirectoryInfo::GetFiles(const String\&, SearchOption) método

Pesquisa os arquivos que atendem ao critério de busca especificado, seja no diretório representado pelo objeto atual ou em toda a árvore de diretórios enraizada no diretório representado pelo objeto atual.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | O padrão de nome dos arquivos a serem procurados |
| searchOption | [SearchOption](../../searchoption/) | Especifica se a busca deve ser realizada apenas no diretório representado pelo objeto atual ou em toda a árvore de diretórios enraizada no diretório representado pelo objeto atual |

### Valor de Retorno

Uma matriz de ponteiros compartilhados para objetos [FileInfo](../../fileinfo/) que representam os arquivos encontrados cujos nomes correspondem a **searchPattern**

## Ver também

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Classe [DirectoryInfo](../)
* Classe [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)