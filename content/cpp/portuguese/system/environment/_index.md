---
title: Environment
second_title: Referência da API Aspose.Slides para C++
description: Serviços do Environment. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por nenhum meio.
type: docs
weight: 1626
url: /pt/system/environment/
---
## Estrutura Environment


[Environment](./) services. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por nenhum meio.

```cpp
class Environment
```

## Métodos

| Método | Descrição |
| --- | --- |
| static void [Exit](./exit/)(int) | Encerra o processo atual e retorna o código de saída especificado ao sistema operacional. |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | Substitui os nomes das variáveis de ambiente encontradas na string especificada pelos valores dessas variáveis e retorna a string resultante. |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | Interrompe o processo atual. |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | Retorna a linha de comando usada para iniciar o processo atual. |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | Retorna o caminho para o diretório de trabalho atual. |
| static int [get_ExitCode](./get_exitcode/)() | Retorna o código de saída do processo atual. |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | Verifica se o desligamento está em andamento. Not implemented. |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | Retorna true para executáveis/bibliotecas de plataforma de 64 bits. |
| static [String](../string/) [get_MachineName](./get_machinename/)() | Retorna o nome NetBIOS deste computador. |
| static [String](../string/) [get_NewLine](./get_newline/)() | Retorna a string de nova linha definida para o ambiente atual. |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | Retorna o objeto [OperatingSystem](../operatingsystem/) que contém informações sobre o sistema operacional atual. |
| static int [get_ProcessorCount](./get_processorcount/)() | Retorna o número de processadores da máquina atual. |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | Retorna a string que contém a informação da pilha de chamadas atual. |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | Retorna o caminho para o diretório do sistema. |
| static int [get_TickCount](./get_tickcount/)() | Retorna o número de milissegundos transcorridos desde que o sistema foi iniciado. |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | Retorna o nome de domínio de rede do usuário atual. |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | Determina se o processo atual está sendo executado no modo interativo do usuário. |
| static [String](../string/) [get_UserName](./get_username/)() | Retorna o nome do usuário atualmente logado no OS [Windows](../../system.windows/). |
| static [Version](../version/) [get_Version](./get_version/)() | Retorna o objeto [Version](../version/) que representa as informações sobre a versão do runtime da linguagem comum. O número da versão retornado por este método é bastante fictício e não significa que todas as classes da biblioteca se comportem de acordo com a versão retornada. |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | Retorna a quantidade de memória física mapeada para o contexto do processo. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | Retorna um array contendo os argumentos da linha de comando usados para iniciar o processo atual. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | Retorna o valor da variável de ambiente especificada associada ao processo atual. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | Retorna o valor da variável de ambiente especificada a partir da localização especificada. |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | Retorna o valor da variável de ambiente especificada associada ao processo atual. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | Retorna um dicionário contendo todos os nomes das variáveis de ambiente e seus valores associados ao processo atual. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | Retorna um dicionário contendo todos os nomes das variáveis de ambiente e seus valores a partir da localização especificada. |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | Retorna o valor da variável de ambiente especificada associada ao processo atual. |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | Retorna o caminho totalmente qualificado para a pasta do sistema especificada. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | Retorna um array contendo os nomes de todas as unidades lógicas no computador atual. |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | Retorna true apenas para WSL. |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | Define o diretório especificado como o diretório de trabalho atual. |
| static void [set_ExitCode](./set_exitcode/)(int) | Define o valor especificado como código de saída para o processo atual. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | NOT IMPLEMENTED. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | NOT IMPLEMENTED. |

## Enumerações

| Enum | Descrição |
| --- | --- |
| [SpecialFolder](./specialfolder/) | Representa pastas especiais do sistema. |

## Veja Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)