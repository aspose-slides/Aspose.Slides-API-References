---
title: AsyncCompletedEventArgs()
second_title: Aspose.Slides for C++ API Referansı
description: Yapıcı.
type: docs
weight: 1
url: /tr/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() constructor


Yapıcı.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) constructor


Yeni bir [System.ComponentModel.AsyncCompletedEventArgs](../) sınıfı örneği oluşturur.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | Asenkron işlem sırasında oluşan herhangi bir hata. |
| canceled | **bool** | Asenkron işlemin iptal edilip edilmediğini gösteren bir değer. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | İsteğe bağlı olarak kullanıcı tarafından sağlanan ve [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) yöntemine geçirilen durum nesnesi. |

## İlgili

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [AsyncCompletedEventArgs](../)
* Sınıf [Object](../../../system/object/)
* Ad alanı [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)