---
title: ReportProgress()
second_title: Référence API Aspose.Slides pour C++
description: "Déclenche l'événement System::ComponentModel::BackgroundWorker::ProgressChanged."
type: docs
weight: 40
url: /fr/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) méthode

Déclenche l'événement **System::ComponentModel::BackgroundWorker::ProgressChanged**.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| percentProgress | int | Le pourcentage, de 0 à 100, de l'opération en arrière-plan qui est terminée. |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) méthode

Déclenche l'événement **System::ComponentModel::BackgroundWorker::ProgressChanged** avec l'objet userState.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| percentProgress | int | Le pourcentage, de 0 à 100, de l'opération en arrière-plan qui est terminée. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | L'objet d'état passé à System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object). |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [BackgroundWorker](../)
* Classe [Object](../../../system/object/)
* Espace de noms [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)