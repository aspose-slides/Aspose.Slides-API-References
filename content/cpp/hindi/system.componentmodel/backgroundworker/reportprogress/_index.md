---
title: ReportProgress()
second_title: Aspose.Slides for C++ API संदर्भ
description: "उठाता है System::ComponentModel::BackgroundWorker::ProgressChanged इवेंट।"
type: docs
weight: 40
url: /hi/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) मेथड

Raises the **System::ComponentModel::BackgroundWorker::ProgressChanged** event.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| percentProgress | int | पृष्ठभूमि प्रक्रिया के पूर्ण होने का प्रतिशत, 0 से 100 तक। |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) मेथड

Raises the **System::ComponentModel::BackgroundWorker::ProgressChanged** event with userState object.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| percentProgress | int | पृष्ठभूमि प्रक्रिया के पूर्ण होने का प्रतिशत, 0 से 100 तक। |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object) को पास किया गया स्थिति ऑब्जेक्ट। |

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [BackgroundWorker](../)
* क्लास [Object](../../../system/object/)
* नेमस्पेस [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)