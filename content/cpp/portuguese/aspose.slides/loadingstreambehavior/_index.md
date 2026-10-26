---
title: LoadingStreamBehavior
second_title: Aspose.Slides para C++ Referência da API
description: "O System::IO::Stream passado para um método é considerado como um Binary Large Object (BLOB) (veja a descrição de IBlobManagementOptions). Os valores desta enumeração identificam como o System::IO::Stream deve ser tratado quando passado para o método. Dependendo dos requisitos, diferentes decisões podem ser tomadas para proporcionar o comportamento mais eficiente."
type: docs
weight: 6735
url: /pt/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enum

O [System::IO::Stream](../../system.io/stream/) passado para um método é considerado como um Binary Large Object (BLOB) (veja a descrição de [IBlobManagementOptions](../iblobmanagementoptions/)). Os valores desta enumeração identificam como o [System::IO::Stream](../../system.io/stream/) deve ser tratado quando passado para o método. Dependendo dos requisitos, diferentes decisões podem ser tomadas para proporcionar o comportamento mais eficiente.

```cpp
enum class LoadingStreamBehavior
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | O fluxo será lido até o fim e então liberado - ou seja, será garantido que este fluxo não será usado pela instância [IPresentation](../ipresentation/) no futuro. Ele pode ser fechado pelo código do cliente ou usado de qualquer outra forma. |
| KeepLocked | 1 | O fluxo será bloqueado dentro do objeto [IPresentation](../ipresentation/), ou seja, a propriedade do fluxo será transferida. O objeto [IPresentation](../ipresentation/) será responsável por descartar corretamente o fluxo quando este objeto for descartado. Esse comportamento é extremamente útil quando você precisa serializar um arquivo BLOB grande (como um vídeo ou áudio grande - veja a descrição de [IBlobManagementOptions](../iblobmanagementoptions/)) e deseja impedir o carregamento deste arquivo na memória ou outros problemas de desempenho. Você pode simplesmente abrir o [System::IO::FileStream](../../system.io/filestream/) para este arquivo e passá-lo para um método, escolhendo [LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior. |

## Veja Também

* Espaço de nomes [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)