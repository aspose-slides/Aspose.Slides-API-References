---
title: ReportProgress()
second_title: Referência da API Aspose.Slides para C++
description: "Aciona o evento System::ComponentModel::BackgroundWorker::ProgressChanged."
type: docs
weight: 40
url: /pt/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) método

Aciona o evento **System::ComponentModel::BackgroundWorker::ProgressChanged**.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| percentProgress | int | A porcentagem, de 0 a 100, da operação em segundo plano que está concluída. |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) método

Aciona o evento **System::ComponentModel::BackgroundWorker::ProgressChanged** com o objeto userState.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| percentProgress | int | A porcentagem, de 0 a 100, da operação em segundo plano que está concluída. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | O objeto de estado passado para System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object). |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [BackgroundWorker](../)
* Classe [Object](../../../system/object/)
* Espaço de nomes [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)