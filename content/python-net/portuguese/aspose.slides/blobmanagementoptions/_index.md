---
title: BlobManagementOptions class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions classe

Representa opções que podem ser usadas para gerenciar regras de tratamento de BLOB e outras configurações de BLOB.

O tipo BlobManagementOptions expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides/blobmanagementoptions/__init__/#) | Cria novas opções padrão de gerenciamento de blob. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/pt/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | Esta propriedade define se uma instância da classe Presentation pode ser proprietária da fonte - arquivo <br/>            ou fluxo durante a vida útil da instância. Se a instância for proprietária, ela bloqueia a fonte. Isso ajuda <br/>            a melhorar o consumo de memória e o desempenho ao trabalhar com BLOBs, mas a fonte (fluxo ou arquivo) <br/>            não pode ser alterada durante a vida útil da instância da Presentation. |
| [`is_temporary_files_allowed`](/slides/python-net/pt/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | Esta propriedade define se arquivos temporários podem ser criados ao trabalhar com BLOBs, o que diminui significativamente <br/>            o consumo de memória, mas requer permissões para criar arquivos.<br/>            Todos os arquivos serão excluídos após a conclusão do trabalho com a apresentação. |
| [`temp_files_root_path`](/slides/python-net/pt/aspose.slides/blobmanagementoptions/temp_files_root_path/) | O caminho raiz onde os arquivos temporários serão criados. O diretório temporário do sistema será usado por padrão. <br/>            O processo de hospedagem deve ter permissões para <br/>            criar arquivos e pastas lá. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/pt/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. Por padrão, todos os BLOBs<br/>            são carregados na memória; somente quando esse limite é atingido são empregados mecanismos alternativos (como arquivos temporários). Manter os BLOBs na memória maximiza o desempenho, mas pode levar a alto uso de memória. Use<br/>            esta propriedade para adaptar o comportamento ao seu ambiente ou requisitos. |

### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)