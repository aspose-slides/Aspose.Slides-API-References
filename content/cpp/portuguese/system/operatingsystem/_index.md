---
title: OperatingSystem
second_title: Referência da API Aspose.Slides para C++
description: "Representa um sistema operacional específico e fornece informações sobre ele. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 1171
url: /pt/system/operatingsystem/
---
## OperatingSystem classe

Representa um sistema operacional específico e fornece informações sobre ele. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class OperatingSystem
```

## Métodos

| Método | Descrição |
| --- | --- |
| [PlatformID](../platformid/) [get_Platform](./get_platform/)() const | Retorna o identificador da plataforma do sistema operacional representado pelo objeto atual. |
| [String](../string/) [get_ServicePack](./get_servicepack/)() const | Retorna o nome do service pack do sistema operacional representado pelo objeto atual. |
| const [Version](../version/)\& [get_Version](./get_version/)() const | Retorna uma referência constante a um objeto [Version](../version/) que representa a versão do sistema operacional representado pelo objeto atual. |
| [String](../string/) [get_VersionString](./get_versionstring/)() const | Retorna a representação em cadeia de caracteres da versão do sistema operacional representado pelo objeto atual. |
| static **bool** [IsFreeBSD](./isfreebsd/)() | Indica se a aplicação atual está sendo executada no FreeBSD. |
| static **bool** [IsLinux](./islinux/)() | Indica se a aplicação atual está sendo executada no Linux. |
| static **bool** [IsMacOS](./ismacos/)() | Indica se a aplicação atual está sendo executada no MacOS. |
| static **bool** [IsOSPlatform](./isosplatform/)(const [String](../string/)\&) | Indica se a aplicação atual está sendo executada na plataforma especificada. |
| static **bool** [IsWindows](./iswindows/)() | Indica se a aplicação atual está sendo executada em [Windows](../../system.windows/). |
| [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&) | Constrói uma instância que representa um sistema operacional especificado por um ID de plataforma e versão específicos. |
| [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&, const [String](../string/)\&) | Constrói uma instância que representa um sistema operacional especificado por um ID de plataforma, versão e service pack. |
| [String](../string/) [ToString](./tostring/)() const | Retorna a representação em cadeia de caracteres da versão do sistema operacional representado pelo objeto atual. |

## Veja Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)