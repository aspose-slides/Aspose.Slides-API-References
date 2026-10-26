---
title: Start()
second_title: Referência da API Aspose.Slides para C++
description: Inicia o processo com parâmetros predefinidos.
type: docs
weight: 14
url: /pt/system.diagnostics/process/start/
---
## Process::Start() método


Inicia o processo com parâmetros predefinidos.

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) método


Inicia o processo com o caminho e argumentos especificados.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) caminho. |
| arguments | const [String](../../../system/string/)\& | [Process](../) parâmetros. |

### Valor de Retorno

[Object](../../../system/object/) anexado ao processo recém-iniciado.

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) método


Inicia o processo com o caminho e argumentos especificados.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | Informações sobre o processo a ser iniciado. |

### Valor de Retorno

[Object](../../../system/object/) anexado ao processo recém-iniciado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Process](../)
* Class [String](../../../system/string/)
* Class [ProcessStartInfo](../../processstartinfo/)
* Namespace [System::Diagnostics](../../)
* Library [Aspose.Slides](../../../)