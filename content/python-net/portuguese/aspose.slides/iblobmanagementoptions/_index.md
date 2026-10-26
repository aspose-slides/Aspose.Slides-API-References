---
title: IBlobManagementOptions class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions classe

Um Binary Large Object (BLOB) é um dado binário armazenado como uma única entidade — ou seja, o BLOB pode ser um 
            áudio, vídeo ou a própria apresentação. Uma série de técnicas é usada para otimizar o consumo de memória 
            ao trabalhar com BLOBs — que já foram armazenados na apresentação ou podem ser adicionados posteriormente de forma programática. 
            Usando [`IBlobManagementOptions`](/slides/python-net/pt/aspose.slides/iblobmanagementoptions) você pode alterar diferentes aspectos de comportamento relacionados ao tratamento de BLOBs 
            para a vida útil da instância [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation).

O tipo IBlobManagementOptions expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/pt/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | Esta propriedade define se uma instância da classe Presentation pode ser proprietária da fonte — arquivo <br/>            ou fluxo durante a vida útil da instância. Se a instância for proprietária, ela bloqueia a fonte. Isso ajuda <br/>            a melhorar o consumo de memória e o desempenho ao trabalhar com BLOBs, mas a fonte (fluxo ou arquivo) <br/>            não pode ser alterada durante a vida útil da instância da Presentation. Este é um exemplo: |
| [`is_temporary_files_allowed`](/slides/python-net/pt/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | Esta propriedade define se arquivos temporários podem ser criados ao trabalhar com BLOBs, o que diminui <br/>            consideravelmente o consumo de memória, mas requer permissões para criar arquivos.<br/>            Todos os arquivos serão excluídos após a conclusão do trabalho com a apresentação. |
| [`temp_files_root_path`](/slides/python-net/pt/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | O caminho raiz onde os arquivos temporários serão criados. O diretório temporário do sistema será usado por padrão. <br/>            O processo de hospedagem deve ter permissões para <br/>            criar arquivos e pastas lá. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/pt/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. Por padrão, todos os BLOBs<br/>            são carregados na memória; somente quando esse limite é atingido mecanismos alternativos (como arquivos<br/>            temporários) são utilizados. Manter os BLOBs na memória maximiza o desempenho, mas pode gerar alto consumo de memória. Use<br/>            esta propriedade para ajustar o comportamento ao seu ambiente ou requisitos. |

### Veja Também
* classe [`IBlobManagementOptions`](/slides/python-net/pt/aspose.slides/iblobmanagementoptions)
* classe [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)