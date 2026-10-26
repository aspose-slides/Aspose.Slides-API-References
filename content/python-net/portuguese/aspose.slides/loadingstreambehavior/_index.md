---
title: LoadingStreamBehavior enumeration
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/loadingstreambehavior/
---
## enumeração LoadingStreamBehavior

O **io.RawIOBase** passado para um método é considerado como um Binary Large Object (BLOB) (veja a descrição [`IBlobManagementOptions`](/slides/python-net/pt/aspose.slides/iblobmanagementoptions)). Os valores desta enumeração identificam como o **io.RawIOBase** deve ser tratado quando passado para o método. Dependendo dos requisitos, diferentes decisões podem ser tomadas para fornecer o comportamento mais eficiente.

O tipo LoadingStreamBehavior expõe os seguintes membros:

## Campos

| Campo | Descrição |
| :- | :- |
| READ_STREAM_AND_RELEASE | O fluxo será lido até o final e então liberado - ou seja, será garantido que este fluxo <br/>            não será usado pela instância [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation) no futuro. Ele pode ser fechado pelo código do cliente <br/>            ou usado de qualquer outra forma. |
| KEEP_LOCKED | O fluxo será bloqueado dentro do objeto [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation), ou seja, a propriedade do <br/>            fluxo será transferida. O objeto [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation) será responsável por <br/>            descartar corretamente o fluxo quando este objeto for descartado. <br/>            Esse comportamento é extremamente útil quando você precisa serializar um grande arquivo BLOB (como um grande <br/>            vídeo ou áudio - veja a descrição [`IBlobManagementOptions`](/slides/python-net/pt/aspose.slides/iblobmanagementoptions)) e deseja evitar o carregamento <br/>            deste arquivo na memória ou outros problemas de desempenho. Você pode simplesmente abrir o **System.IO.FileStream** <br/>            para este arquivo e passá-lo a um método, escolhendo [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/pt/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior. |

### Ver também
* classe [`IBlobManagementOptions`](/slides/python-net/pt/aspose.slides/iblobmanagementoptions)
* classe [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)