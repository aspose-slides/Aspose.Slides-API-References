---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides para Python via referência de API .NET
description: 
type: docs
url: /pt/aspose.slides/presentationlockingbehavior/
---
## Enumeração PresentationLockingBehavior

Representa o comportamento em relação ao tratamento da [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation) fonte (arquivo ou **io.RawIOBase**) ao carregar e trabalhar com uma instância de [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation).

O tipo PresentationLockingBehavior expõe os seguintes membros:

## Campos

| Campo | Descrição |
| :- | :- |
| LOAD_AND_RELEASE | A fonte será bloqueada apenas durante a execução do construtor [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation).<br/>            Se [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/pt/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) for definido como false, todos os BLOBs <br/>            serão carregados na memória. Caso contrário, outros meios como arquivos temporários podem ser usados. Esse comportamento é mais lento que [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/pt/aspose.slides/presentationlockingbehavior/KEEP_LOCKED), e se for possível passar a <br/>            propriedade da fonte para [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation), recomenda-se usar [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/pt/aspose.slides/presentationlockingbehavior/KEEP_LOCKED). |
| KEEP_LOCKED | A fonte será bloqueada durante toda a vida útil da instância [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation), até que ela seja <br/>            descartada.<br/>            [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/pt/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) deve ser definido como true para usar <br/>            esse comportamento, caso contrário uma exceção será lançada. Esse comportamento é recomendado, é mais rápido e consome menos memória que [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/pt/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE). |


### Observações

A fonte é o parâmetro passado ao construtor [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). No exemplo abaixo, a fonte é o arquivo "pres.pptx": Para este exemplo, a fonte ("pres.pptx" file) será bloqueada durante a vida útil de uma instância [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation), ou seja, não pode ser alterada ou excluída por outro processo.


### Veja Também
* classe [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)