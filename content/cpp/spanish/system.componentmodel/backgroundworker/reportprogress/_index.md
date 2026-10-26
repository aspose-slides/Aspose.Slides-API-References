---
title: ReportProgress()
second_title: Referencia de API de Aspose.Slides para C++
description: "Genera el evento System::ComponentModel::BackgroundWorker::ProgressChanged."
type: docs
weight: 40
url: /es/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) método

Genera el evento **System::ComponentModel::BackgroundWorker::ProgressChanged**.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| percentProgress | int | El porcentaje, de 0 a 100, de la operación en segundo plano que está completa. |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) método

Genera el evento **System::ComponentModel::BackgroundWorker::ProgressChanged** con el objeto userState.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| percentProgress | int | El porcentaje, de 0 a 100, de la operación en segundo plano que está completa. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | El objeto de estado pasado a System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object). |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [BackgroundWorker](../)
* Clase [Object](../../../system/object/)
* Espacio de nombres [System::ComponentModel](../../)
* Biblioteca [Aspose.Slides](../../../)