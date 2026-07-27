---
title: Start()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicia el proceso con parámetros predefinidos.
type: docs
weight: 14
url: /es/system.diagnostics/process/start/
---
## Process::Start() método

Inicia el proceso con parámetros predefinidos.

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) método

Inicia el proceso con la ruta y los argumentos especificados.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) ruta. |
| arguments | const [String](../../../system/string/)\& | [Process](../) parámetros. |

### Valor de retorno

[Object](../../../system/object/) asociado al proceso recién iniciado.

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) método

Inicia el proceso con la ruta y los argumentos especificados.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | Información sobre el proceso a iniciar. |

### Valor de retorno

[Object](../../../system/object/) asociado al proceso recién iniciado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Process](../)
* Clase [String](../../../system/string/)
* Clase [ProcessStartInfo](../../processstartinfo/)
* Espacio de nombres [System::Diagnostics](../../)
* Library [Aspose.Slides](../../../)