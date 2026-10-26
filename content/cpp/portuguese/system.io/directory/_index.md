---
title: Directory
second_title: Referência da API Aspose.Slides for C++
description: Contém métodos para manipular diretórios. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por qualquer meio.
type: docs
weight: 235
url: /pt/system.io/directory/
---
## classe Directory

Contém métodos para manipular diretórios. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por qualquer meio.

```cpp
class Directory
```

## Métodos

| Método | Descrição |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | Cria todos os diretórios no caminho especificado se eles não existirem. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | Remove o arquivo ou diretório especificado. Não lança exceção. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Procura pelos diretórios que atendem aos critérios de pesquisa especificados, seja no diretório especificado ou em toda a árvore de diretórios enraizada no diretório especificado. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Procura pelos arquivos que atendem aos critérios de pesquisa especificados, seja no diretório especificado ou em toda a árvore de diretórios enraizada no diretório especificado. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Procura pelos arquivos e diretórios que atendem aos critérios de pesquisa especificados, seja no diretório especificado ou em toda a árvore de diretórios enraizada no diretório especificado. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Determina se o caminho especificado refere-se a um diretório existente. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Retorna o horário de criação da entidade especificada como hora local. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Retorna o horário de criação da entidade especificada como hora UTC. |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | Retorna o nome completo (incluindo o caminho) do diretório atual. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Procura pelos diretórios que atendem aos critérios de pesquisa especificados, seja no diretório especificado ou em toda a árvore de diretórios enraizada no diretório especificado. |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | Retorna o diretório raiz do caminho especificado. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Procura pelos arquivos que atendem aos critérios de pesquisa especificados, seja no diretório especificado ou em toda a árvore de diretórios enraizada no diretório especificado. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Procura pelos arquivos e diretórios que atendem aos critérios de pesquisa especificados, seja no diretório especificado ou em toda a árvore de diretórios enraizada no diretório especificado. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Retorna o horário do último acesso da entidade especificada como hora local. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Retorna o horário do último acesso da entidade especificada como hora UTC. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Retorna o horário da última gravação da entidade especificada como hora local. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Retorna o horário da última gravação da entidade especificada como hora UTC. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | NÃO IMPLEMENTADO. |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | Retorna um ponteiro compartilhado para o objeto [DirectoryInfo](../directoryinfo/) que representa o diretório pai da entidade especificada. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Move a entidade especificada para a nova localização. Se a entidade a ser movida for um diretório, ela é movida com todo o seu conteúdo. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Define o horário de criação da entidade especificada como hora local. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Define o horário de criação da entidade especificada como hora UTC. |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | Define o diretório atual. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Define o horário do último acesso da entidade especificada como hora local. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Define o horário do último acesso da entidade especificada como hora UTC. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Define o horário da última gravação da entidade especificada como hora local. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Define o horário da última gravação da entidade especificada como hora UTC. |

## Typedefs

| Typedef | Descrição |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | Um alias para um ponteiro compartilhado para um objeto IEnumerable que enumera um conjunto de objetos [String](../../system/string/). |

## Observações



```cpp
#include "system/io/directory.h"
#include "system/io/path.h"
#include "system/string.h"
#include <iostream>

void PrintMessage(const System::String &path)
{
  std::cout << "Directory '" << path << (System::IO::Directory::Exists(path) ? "' exists." : "' doesn't exist.") << std::endl;
}

int main()
{
  // Cria strings que contêm caminhos para diretórios.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // Verifica se os diretórios existem.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // Imprime as informações do diretório temporário.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
Este exemplo de código produz a saída a seguir:
Diretório 'C:\' existe.
Diretório 'C:\Some directory' não existe.
Diretório 'C:\Users\lanor\AppData\Local\Temp\' existe.
Hora de Criação: 27.08.2021 14:21:42
Último Horário de Acesso: 07.10.2021 12:16:41
Último Horário de Gravação: 07.10.2021 12:16:41
*/
```

## Veja Também

* Namespace [System::IO](../)
* Biblioteca [Aspose.Slides](../../)